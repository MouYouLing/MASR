<div align="center">

# MaaAssistantHonkaiStarRail

基于MAA全新架构的 星穹铁道 小助手

图像技术 + 模拟控制，解放双手！

由 [MaaFramework](https://github.com/MaaAssistantArknights/MaaFramework) 强力驱动！

</div>

## 功能&TODO

- [x] 启动游戏
    - [x] 等待更新下载
    - [x] 进入游戏
- [x] 派遣委托
    - [x] 一键收取并再次派遣
    - [ ] 自动选人
- [x] 刷开拓力
    - [x] 拟造花萼（金）
    - [x] 拟造花萼（赤）
    - [x] 凝滞虚影
    - [x] 历战余响
    - [x] 侵蚀隧洞
    - [ ] 饰品提取
- [x] 领取奖励
    - [x] 每日任务及每日奖励
    - [ ] 自动兑换码
    - [x] 领取邮件
    - [x] 领取无名勋礼
    - [ ] 领取列车补给凭证

## 即刻开始

下载地址：<https://github.com/MouYouLing/MASR/releases>

- 开发和测试环境为蓝叠模拟器、1920*1080分辨率、240DPI，其他模拟器如有问题，可提交反馈
- 请尽量保证实际运行分辨率不低于1280*720，并保持显示比例为16:9

## 生态共建

TODO:

- 打包为Release 
- 撰写使用说明
- GUI使用

## 其他说明

- 安卓端开发和测试环境为蓝叠模拟器、1920*1080分辨率、240DPI
- 桌面端运行时需保证游戏窗口始终处于最前端，以免影响识别结果
- 添加 `-d` 参数可跳过交互直接运行任务，如 `./MaaPiCli.exe -d`
- 反馈问题请附上日志文件 `debug/maa.log`，谢谢！

## How to build

**如果你要编译源码才看这节，否则直接 [下载](https://github.com/MouYouLing/MASR/releases) 即可**

0. 完整克隆本项目及子项目

    ```bash
    git clone --recursive https://github.com/MouYouLing/MASR.git
    ```

1. 下载 MaaFramework 的 [Release 包](https://github.com/MaaXYZ/MaaFramework/releases)，解压到 `deps` 文件夹中
2. 安装

    ```python
    python ./install.py
    ```

生成的二进制及相关资源文件在 `install` 目录下

## 鸣谢

本项目由 **[MaaFramework](https://github.com/MaaXYZ/MaaFramework)** 强力驱动！

### 开发者

感谢以下开发者对 MASR 作出的贡献：

<a href="https://github.com/MouYouLing/MASR/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=MouYouLing/MASR&max=1000" />
</a>

