彻底解决PIN码不可用



1. 按住shift重启→高级选项→cmd→regedit回车→选中HKEY LOCAL MACHINE→文件→配置单元→选择系统盘（可能不是C）Windows/system32lconfig/→打开software文件→输入自定义名称

2. 在注册表主界面定位到HKEYLOCALMACHINE/自定义项/Microsoft/WindowsNT/currentrersion/passwordless/Device

3. 将值devisepasswordlesbvcersion由2改为0

4 返回注册表最最上端选中自定义的项→点击文件→卸载配置单元

5.继续使用Window→在登录界面的pin不可用下方找到登录选项→输入密码进去桌面。
