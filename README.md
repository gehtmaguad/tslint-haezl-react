# Overview 

* set of opinionated tslint rules
* tries to make a fair trade-off between productivity, error avoidance and coding style
* targets side or hobby projects

## Setup

### Install

`yarn add --dev tslint-haezl-react`

### Update `tsconfig.json`:

```
{
    "extends": [
        "tslint-haezl-react"
    ],
    "rules": [
        // add/overwrite rules
    ]
}
```