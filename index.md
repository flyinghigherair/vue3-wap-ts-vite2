1.nodejs

| 步骤                                    | 说明                                                         |
| --------------------------------------- | ------------------------------------------------------------ |
| nodejs14.19.0<br >node-v14.19.0-x64.msi | http://nodejs.cn/download/current/<br>https://registry.npmmirror.com/binary.html?path=node/v14.19.0/ |
| powershell设置                          | 执行set-ExecutionPolicy RemoteSigned，选择[Y] 是(Y)          |

2.npm配置

| 步骤          | 说明                                                         |
| ------------- | ------------------------------------------------------------ |
| 查看npm默认源 | npm config get registry（请记住返回的网址，一般是https://registry.npmjs.com） |
| 修改npm源     | npm config set registry https://registry.npmmirror.com       |

3.yarn配置

| 步骤           | 说明                                                         |
| -------------- | ------------------------------------------------------------ |
| 安装yarn       | npm install -g yarn                                          |
| 查看yarn默认源 | yarn config get registry（请记住返回的网址，一般是https://registry.npmjs.com） |
| 修改yarn源     | yarn config set registry https://registry.npmmirror.com      |

4.pnpm配置

| 步骤           | 说明                                                         |
| -------------- | ------------------------------------------------------------ |
| 安装pnpm       | npm install -g pnpm                                          |
| 查看pnpm默认源 | pnpm config get registry（请记住返回的网址，一般是https://registry.npmjs.com） |
| 修改pnpm源     | pnpm config set registry https://registry.npmmirror.com      |

5.VSCode插件

| 插件                 | 说明         |
| -------------------- | ------------ |
| ESLint               |              |
| Vetur                | vue2语法     |
| Visual Studio Keymap | vs用户快捷键 |

