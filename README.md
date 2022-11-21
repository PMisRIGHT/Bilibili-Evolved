<div align="center">

Bilibili Evolved v1.12.22 功能修复

</div>
</br></br>

基于[the1812](https://github.com/the1812)的[Bilibili Evolved](https://github.com/the1812/Bilibili-Evolved) v1.12.22离线版(v1215.24)，在此感谢大佬的付出！
</br></br>
主要为了我自己能用，不喜欢v2，但是大佬不维护了（这不是很正常吗.jpg），所以自己修修v1接着用，你也可以使用
</br></br>
脚本有问题请在我这儿提issue，请不要去原作者那里提issue，如果喜欢此脚本请支持原作者，谢谢！

# 安装
[点我](https://github.com/PMisRIGHT/Bilibili-Evolved/releases/download/v1.12.22-fix/Bilibili.Evolved.Offline.Mod.user.js)

# 使用
额，相信你会来找这个版本就已经会使用了吧，可以导出v1的设置后导入到这个版本里，但是应该不能使用v2的设置

# 修复说明
原脚本不知道是为了节省空间还是提高加载效率，将脚本内容放到了一行里，很难做修改，我使用了Notepad++的JSTool插件将原脚本格式化后做修复，下面修复内容里的行数就是这么来的

--
#### 2022.11.22
修复了导航栏用户头像无法加载的问题：
将6202行和6212行中的replace行为无效化以正确加载导航栏头像

修复了夜间模式无法正确适配页面的问题：
将7357行与7379行offlineData中的style内容替换为[v2最新版夜间模式功能](https://github.com/the1812/Bilibili-Evolved/blob/master/registry/dist/components/style/dark-mode.js)中的style内容以修复夜间模式
