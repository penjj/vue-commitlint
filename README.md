# vue-commitlint

仅需简单配置，无需单独的配置文件，即可使用vue风格的commit messages检测（类似于angular commitlint）

如果还需快速配置eslint代码风格检测风格，可参考[eslint-plugin-all-in-one](https://github.com/penjj/eslint-plugin-all-in-one)

## Usage
```bash
pnpm install simple-git-hooks vue-commitlint -D
```
change your package.json
```json5
{
  "scripts": {
    "prepare": "simple-git-hooks"
  },
  // Recommend using simple-git-hooks
  "simple-git-hooks": {
    "commit-msg": "pnpm vue-commitlint"
  }
}
```