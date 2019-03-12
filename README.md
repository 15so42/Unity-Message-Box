# Unity-Message-Box
自制的消息提示框。

首先导入MessageBox，再把Prefabs里的MessageBox拖到Canvas下即可。

导入后无需禁用messageBox，在启动游戏后脚本会调用HideImmadietly()自动隐藏。

之后在需要的地方使用MessageBox._instance.Show()即可显示消息框.

使用MessageBox._instance.Hide()即可隐藏消息框。

使用MessageBox._instance.AddMessage("内容");即可添加内容,在字符串后添加\n字符即可换行.

按tab可关闭和开启消息提示框

在显示消息六秒后会自动隐藏


