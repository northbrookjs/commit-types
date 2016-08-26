# @northbrook/commit-types

Commit types used by [northbrook](https://gitub.com/TylorS/northbrook)

Can be used easily with [validate-commit-msg](https://github.com/kentcdodds/validate-commit-msg)

```js
// package.json
{
  "config": {
    "ghooks": {
      "commit-msg": "node ./node_modules/.bin/validate-commit-msg"
    },
    "validate-commit-msg": {
      "types": "@northbrook/commit-types"
    }
  }
}
```
