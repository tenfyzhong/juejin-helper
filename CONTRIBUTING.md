# 参与贡献

## 项目结构
- packages 掘金API工程
- workflows 掘金自动化工作流项目

### 本地运行
- Node.js >= 22.23.4 < 23（推荐使用 `.nvmrc` 指定的版本）
- `yarn` 安装依赖
- `yarn dev` 启动开发模式

### 本地运行工作流项目
- `cd workflows`
- `/utils/env.js` 替换本地测试所需的环境变量
```javascript
module.exports = {
  COOKIE: "测试掘金Cookie",
  // ...
};
```
- `yarn checkin` 运行掘金签到脚本
- `yarn seagold` 运行海底掘金游戏脚本
