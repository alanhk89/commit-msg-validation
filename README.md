# commit-msg-validation

### Validate rules:

- `[StoryNumber / Type] commit purpose`

## Installation

```shell
yarn add -D commit-msg-validation
```

## How to use

This `validate` need to be used with [Husky](https://github.com/typicode/husky) .
Add this config to package.json

```
"scripts": {
   "commitmsg": "commit-msg-validation",
   ....
}
```
