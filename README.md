# O2j-Eslint

![](https://img.shields.io/badge/vue--cli-3.0-brightgreen.svg)
![](https://img.shields.io/badge/vue-2.0%2B-green.svg)

[o2jteam](https://o2jteam.github.io/)前端团队代码规范v 1.0

`.eslintrc.js`：eslint规则配置文件
`.eslintignore`：eslint忽略检查配置文件


## js使用eslint检查
#### 1.初始化项目
```
npm install
```
#### 2.将js文件放入src目录下运行
```$xslt
npm run build
```

## vue 

#### 1.安装vue-cli 3.0
```
npm install -g @vue/cli
```

#### 2.创建项目
```
vue create project-name
```
#### 3.选择启用Eslint
```
? Please pick a preset: Manually select features
? Check the features needed for your project: Router, Vuex, CSS Pre-processors, Linter, Unit
? Pick a CSS pre-processor (PostCSS, Autoprefixer and CSS Modules are supported by default): Stylus
? Pick a linter / formatter config: (Use arrow keys)
  ESLint with error prevention only
  ESLint + Airbnb config
> ESLint + Standard config
  ESLint + Prettier
```
#### 4.选择/vue下的.eslintrc.js
替换.eslintrc.js文件

## editTool
### webstorm(js&vue)
#### 1.选择file->Settings
![setting](https://i.imgur.com/VB9NQE5.png)
#### 2.选择Languages->Code Quality->Eslint
选择`Manual Eslint configuration`选项；`Node interpreter`选择`node`程序所在路径；选择`Configuration file`配置`Eslint`规则。
![配置eslint](https://i.imgur.com/u1ktLEZ.png)
#### 3.应用
选择你要进行格式化规范的代码文件，点击右键选择`Fix Eslint Problems`进行代码检测修复
![代码修复](https://i.imgur.com/yu5WYXh.png)

