该码表在 fcitx 4.2.9.1上测试通过，但不支持 fcitx5。  
在个人用户目录下操作即可，无需 root 权限和 sudo 命令，**需重启fcitx**

##1. 使用码表
将 `wb98.mb` 、`wb98.conf` 拷入`～/.config/fcitx/table/` 目录  

	mkdir -p ~/.config/fcitx/table/
	cp wb98.mb wb98.conf ~/.config/fcitx/table

##2. 使用自定义图标
将`wubi98.png`拷入 `～/.config/fcitx/imicon` 目录  

	mkdir -p ~/.config/fcitx/imicon/
	cp wubi98.png ~/.config/fcitx/imicon/
	
##3. 输入特殊符号
将`QuickPhrase.mb`拷入`～/.config/fcitx/data/`目录  

	mkdir -p ~/.config/fcitx/data/
	cp QuickPhrase.mb ~/.config/fcitx/data/
	
**使用方法**
>在任意输入界面先按 `;` 即分号键进入快捷输入，然后输入特殊符号对应编码  

**QuickPhrase.mb**可直接用文本编辑器打开后添加或查找特殊符号  

##4. 图标

![](wubi98.png)
