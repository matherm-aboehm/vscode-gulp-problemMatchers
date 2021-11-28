# GULP Problem Matchers README

Defines common named problem patterns & matchers for gulp tasks.

## Usage
To use this, add the `gulp-tsc6` or `gulp-tsc6-watch` problem matcher to your tasks.json, as appropriate. For example:

```json
{
  "version": "2.0.0",
  "tasks": [
    {
      "type": "npm",
      "script": "watch",
      "group": "build",
      "problemMatcher": "$gulp-tsc6-watch",
      "isBackground": true,
      "label": "npm: watch"
    },
    {
      "type": "npm",
      "script": "build",
      "group": "build",
      "problemMatcher": "$gulp-tsc6",
      "label": "npm: build"
    }
  ]
}
```

## Features

The following problem patterns are defined:

- gulp-tsc6

The following problem matchers are defined:

- gulp-tsc6
- gulp-tsc6-watch

## Release Notes

### 0.0.2

Remove unnecessary files

### 0.0.1

Initial release of GULP Problem Matchers
