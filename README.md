# angular-strict-tslint-rules

Stricts rules to enforce a consistent code style for **Angular** development

## Tsconfig

For better consistency, please, i suggest you to add this to your `tsconfig.json` :

```javascript
{
  "compilerOptions": {
    "esModuleInterop": true, // Disables namespace imports (import * as fs from "fs") and enables CJS/AMD/UMD style imports (import fs from "fs")
    "noImplicitAny": true // Raise error on expressions and declarations with an implied any type.
    "noUnusedLocals": true, // Report errors on unused locals
    "noUnusedParameters": true, // Report errors on unused parameters
    "noImplicitReturns": true, // Report an error when not all code paths in function return a value.
    "strict": true, // Enable all strict type checking options
  }
}
```

## Installation

```sh
npm install angular-strict-tslint-rules --save-dev
```

or

```sh
yarn add angular-strict-tslint-rules --dev
```

## Usage

In `tslint.json`:

```json
{
  "extends": "angular-strict-tslint-rules"
}
```

## Rules
* [TSLint](https://github.com/palantir/tslint)
* [codelyzer](https://github.com/mgechev/codelyzer)
* [tslint-consistent-codestyle](https://github.com/ajafff/tslint-consistent-codestyle)
* [tslint-eslint-rule](https://github.com/buzinas/tslint-eslint-rules)
* [tslint-microsoft-contrib](https://github.com/Microsoft/tslint-microsoft-contrib)

## Extends
* [angular-tslint-rules](https://github.com/fulls1z3/angular-tslint-rules)
