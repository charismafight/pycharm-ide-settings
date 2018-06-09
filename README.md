# config_of_IDEs

save configs of pycharm,idea,vscode etc.



# shortcut for idea

sudo vim /usr/share/applications/intellij.desktop
set content as follow:
[Desktop Entry]
Encoding=UTF-8
Version=1.0
Name=IDEA
GenericName=Java IDE
Comment=IntelliJ IDEA is a code-centric IDE focused on developer    productivity. The editor deeply understands your code and knows its way around the codebase, makes great suggestions right when you need them, and is always ready to help you shape your code.
Exec=/home/lee/idea-IU-181.4445.78/bin/idea.sh
Icon=/home/lee/idea-IU-181.4445.78/bin/idea.png
Terminal=false
Type=Application

save and set owner and chmod of this file,then it will searched by value of Name={value}
