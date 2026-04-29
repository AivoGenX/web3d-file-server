# Web3D 文件服务器

用于 Three.js、Cesium、WebGPU、Vue.js 等 Web3D 技术的资源文件存储服务器

## 📋 项目简介

这是一个专门为 Web3D 开发提供资源文件的静态文件服务器，包含各种 3D 模型、贴图、地图瓦片、音频视频等资源文件。

**GitHub 主项目**: https://github.com/threelab/three-lab-demos

## ⚠️ 版权声明与使用条款

### 📄 重要声明

**本资源库中的所有文件仅供学习、研究和开发测试使用，严禁用于任何商业用途或违法活动。**

### 🔒 使用限制

1. **仅供学习使用**：所有资源仅限于个人学习、教育研究和技术开发测试目的
2. **禁止商业用途**：严禁将本资源用于任何商业项目、产品发布或盈利性活动
3. **遵守法律法规**：使用者必须严格遵守所在国家/地区的法律法规，不得用于任何违法活动
4. **版权归属**：资源库中可能包含第三方版权内容，使用者需自行确认版权状态并承担相应责任

### ⚖️ 法律责任

- **使用者自行承担风险**：使用本资源库即表示您同意自行承担所有使用风险
- **免责声明**：资源提供方不对使用本资源库导致的任何直接或间接损失负责
- **法律后果**：若因违反使用条款导致法律纠纷，责任由使用者自行承担
## 🌐 访问地址

- **主页面**: https://threelab.github.io/web3d-file-server/
- **资源链接页面**: https://threelab.github.io/web3d-file-server/link.html

## 📁 资源分类

### 🏠 3D Tiles 瓦片数据
- **房屋模型**: https://threelab.github.io/web3d-file-server/3dtiles/house/tileset.json
- **测试瓦片**: https://threelab.github.io/web3d-file-server/3dtiles/test/tileset.json

### 🎨 贴图资源
- **法线贴图**: https://threelab.github.io/web3d-file-server/images/channels/n.png
- **HDR 贴图**: https://threelab.github.io/web3d-file-server/files/hdr/1k.hdr
- **天空盒**: https://threelab.github.io/web3d-file-server/files/sky/skyBox0/1.png
- **地球贴图**: https://threelab.github.io/web3d-file-server/threeExamples/application/flyLine/earth.jpeg

### 🦊 3D 模型 (GLB格式)
- **狐狸模型**: https://threelab.github.io/web3d-file-server/files/model/Fox.glb
- **电脑模型**: https://threelab.github.io/web3d-file-server/models/glb/computer.glb
- **咖啡模型**: https://threelab.github.io/web3d-file-server/examples/coffeeMug/coffeeMug.glb
- **建筑模型**: https://threelab.github.io/web3d-file-server/models/glb/build.glb
- **导弹模型**: https://threelab.github.io/web3d-file-server/models/glb/daodan.glb
- **飞机模型**: https://threelab.github.io/web3d-file-server/models/glb/feiji.glb
- **地面模型**: https://threelab.github.io/web3d-file-server/models/glb/foorGround.glb
- **工人模型**: https://threelab.github.io/web3d-file-server/models/glb/gongren.glb
- **雷达模型**: https://threelab.github.io/web3d-file-server/models/glb/leida.glb
- **飞机模型**: https://threelab.github.io/web3d-file-server/models/glb/plane.glb
- **机器人模型**: https://threelab.github.io/web3d-file-server/models/glb/robot.glb
- **挖掘机模型**: https://threelab.github.io/web3d-file-server/models/glb/wajueji.glb
- **展馆模型**: https://threelab.github.io/web3d-file-server/models/glb/zhanguan.glb
- **追踪器模型**: https://threelab.github.io/web3d-file-server/models/glb/zhuizi.glb

### 📄 其他格式模型
- **城市白膜 (FBX)**: https://threelab.github.io/web3d-file-server/models/fbx/shanghai.FBX

### 📊 JSON 数据文件
- **英文字体**: https://threelab.github.io/web3d-file-server/files/json/font.json
- **中文字体**: https://threelab.github.io/web3d-file-server/files/json/font_zn.json
- **广东地理数据**: https://threelab.github.io/web3d-file-server/files/json/guangdong.json

### 🎵 多媒体资源
- **视频文件**: https://threelab.github.io/web3d-file-server/files/video/video.mp4
- **音频文件**: https://threelab.github.io/web3d-file-server/files/audio/Avicii-WeBurn.mp3

### 🗺️ 地图瓦片
- **离线地图**: https://threelab.github.io/web3d-file-server/map/[Baidu-Gaode]/tiles/{z}/{x}/{y}.jpg

## 🚀 使用方法

1. **直接访问**: 在浏览器中打开上述链接即可下载或查看资源
2. **在代码中使用**: 将资源链接作为 URL 直接用于 Three.js、Cesium 等 Web3D 框架
3. **资源管理**: 访问 [link.html](https://threelab.github.io/web3d-file-server/link.html) 查看所有资源的分类列表

## 📂 目录结构

```
web3d-file-server/
├── 3dtiles/          # 3D Tiles 瓦片数据
├── files/            # 各类资源文件
│   ├── audio/        # 音频文件
│   ├── hdr/          # HDR 贴图
│   ├── json/         # JSON 数据
│   ├── model/        # 3D 模型
│   ├── sky/          # 天空盒资源
│   └── video/        # 视频文件
├── images/           # 图片资源
├── map/              # 地图瓦片
├── models/           # 模型文件
│   ├── glb/         # GLB 格式模型
│   └── fbx/         # FBX 格式模型
└── js/               # JavaScript 库文件
```

## 🔧 技术栈

- **静态文件服务**: GitHub Pages
- **3D 技术**: Three.js、Cesium、WebGPU
- **前端框架**: Vue.js
- **资源格式**: GLB、FBX、JSON、PNG、JPG、HDR、MP4、MP3

## 🚨 侵权处理机制

### 📧 版权投诉与删除请求

如果您认为本资源库中的任何内容侵犯了您的合法权益，请通过以下方式联系我们：

**联系方式**: 通过 GitHub Issues 提交侵权投诉

**投诉内容需包含**:
1. 权利人的身份证明和联系方式
2. 涉嫌侵权内容的详细描述和具体位置
3. 权利证明文件（如版权登记证书、授权文件等）
4. 侵权声明的法律依据

### 🔄 处理流程

1. **收到投诉**：我们将在收到有效投诉后立即核实
2. **快速响应**：确认侵权事实后，将在24小时内删除相关内容
3. **公开说明**：重大侵权事件将在项目页面进行公开说明
4. **预防措施**：加强内容审核，防止类似问题再次发生

### ⚖️ 法律合规承诺

- 严格遵守《中华人民共和国著作权法》等相关法律法规
- 积极响应国家关于网络版权保护的政策要求
- 建立完善的侵权投诉处理机制
- 定期进行内容自查，确保合规性

## 🤝 贡献

欢迎提交 Issue 和 Pull Request 来完善资源库！

**重要提示**: 贡献者需确保提交的内容不侵犯第三方版权，否则责任自负。

## 📄 最终声明

**本资源库仅为技术学习交流平台，不承担任何版权责任。使用者必须自行确认内容的合法性，如发现侵权内容请立即停止使用并联系我们处理。**

---

*最后更新: 2026年4月7日*