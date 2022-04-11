# 使用 Prettier 和 ESLint 自动格式化和修复 JavaScript

[参考 1](https://blog.logrocket.com/using-prettier-eslint-automate-formatting-fixing-javascript/)

[参考 2](https://khalilstemmler.com/blogs/tooling/prettier/)

```bash
npm install --save-dev eslint
npm install --save-dev prettier

# eslint 初始化
npx eslint --init

# 关掉与Prettier产生冲突的ESlint格式相关配置,使用eslint-config-prettier这个插件
npm install --save-dev eslint-config-prettier

# 运行 Prettier 作为 ESLint 规则，安装这个插件之后，
# 修改之前
# extends: ['eslint:recommended', 'prettier'],
# 需要修改.eslintrc.js
# ...
# extends: ['eslint:recommended', 'plugin:prettier/recommended'],
#...
npm install --save-dev  eslint-plugin-prettier


```
