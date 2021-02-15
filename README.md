# hackintosh-opencore--UI-theme

操作指南： 仅适用于OC0.6.5 正式版及以上版本 

同步于发布于B站  https://www.bilibili.com/read/cv9315056


若有其他问题请加Q群：1125705781，备注小明或者B站

也欢迎关注B站：小明和他的女朋友

https://space.bilibili.com/591453294?spm_id_from=333.788.b_765f7570696e666f.2


下载此附件中Resources文件夹替换EFI/OC/同名文件夹；

下载此附件OpenCanopy.efi 替换EFI/OC/Drivers/下同名文件，并确认并在config.plist加载该驱动；

EFI/OC/Drivers/中必须存在CrScreenshotDxe.efi（截图快捷键驱动） 并在config.plist加载该驱动；

![](https://github.com/Xmingbai/hackintosh-opencore--UI-theme/blob/main/iShot2021-01-17.png)


EFI/OC/Resources/Audio下仅保留了OCEFIAudio_VoiceOver_Boot.wav 开机启动音，其他精简掉，避免主题文件过大；

![](https://github.com/Xmingbai/hackintosh-opencore--UI-theme/blob/main/audio.png)




# 主题展示


![](https://github.com/Xmingbai/hackintosh-opencore--UI-theme/blob/main/TipsBackground.png)

如何切换到背景无提示的纯净方式呢？

EFI/OC/Resources/Image/NoTipsBackground.icns文件改名为Background.icns即可（先改名同名文件）


![](https://github.com/Xmingbai/hackintosh-opencore--UI-theme/blob/main/NoTipsBackground.png)
