# jupyter-notebook-configs
some configurations after RE-INSTALL jupyter-notebook


1. 修改jupyter-notebook默认工作路径
  在C://Users/Administrater/.jupyter/jupyter_notebook_config.py中找到#c.NotebookApp.notebook_dir =' '，删掉开头的注释"#"，在路径中输入要启动的目录路径。
  在jupyter的开始菜单快捷方式上右键属性，删除【目标】属性中的【%USERPROFILE%】，点击【应用】–【确定】。
 
# anaconda3

1. 完全删除anaconda需要在anaconda安装目录下找到Uninstall-anaconda3.exe，卸载后重新启动
2. 环境配置 Path中添加"D://Anaconda"和"D://Anaconda/Scripts"和"D://Anaconda/Library/bin"
