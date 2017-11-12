# Angular

### Angular-CLI
- Generate component within a specific folder: `ng g c <folder-name>/<component-name>`
- Use flag --lint-fix on generate command to follow tslint config
- Config:
  - To automatically lint-fix generators:
  ``` json
  {
    "defaults": {
      "lintFix": true
    }
  }
  ```
  - To disable automatic test generation:
  ``` json
  {
    "defaults": {
      "class": {
        "spec": false
      },
      "component": {
        "spec": false
      },
      "directive": {
        "spec": false
      },
      "module": {
        "spec": false
      },
      "pipe": {
        "spec": false
      },
      "service": {
        "spec": false
      }
    }
  }
  ```

### TSLint
- Config:
  - To disable semicolons:
  ``` json
  {
    "rules": {
      "semicolon": [
        true,
        "never"
      ]
    }
  }
  ```
