# Blender-to-Unity-Mirror
Blender to Unity 同步数据插件
# 功能

- unity 到 blender 画面同步
- blender 到 unity 资源同步

使用协议

# 环境要求

- Unity 2022.3 或更高版本
- 仅适用于 URP 和 HDRP – 不能在内置渲染管线中使用它。使用 HDRP 时启用 [Alpha 输出](https://docs.unity3d.com/Packages/com.unity.render-pipelines.high-definition@12.0/manual/Alpha-Output.html) 。
- blender 5

# 技术

画面同步协议 spout，数据同步使用自定义cs格式

### unity 安装

- **MeshSync**
- **manifest.json** 需要手动添加 `"com.unity.settings-manager": "1.0.3"`
- **KlakSpout**

### Blender 安装

- [**TextureSharing**](https://github.com/maybites/TextureSharing)
- **MeshSync**

# 使用

### unity

创建mesh

![image.png](attachment:e39bafd9-f3b4-40dd-81b2-1225a9a7f7b6:image.png)

同步资源

### Blender

**Sharing Textures  分享视图**

![image.png](attachment:ed9e8b32-4768-4ef5-b838-463ee4ef722f:image.png)

**Receiving Shared Textures 接收视图**

![image.png](attachment:356119b7-7fbd-4ef3-894a-074b55c515fc:image.png)

> 接受的Image一定要用Spout的名字
> 

同步资源
