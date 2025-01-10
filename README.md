# 1、Qt的应用开发 之 Demo_MessageChat_Qt
Qt5气泡式聊天框——QListWidget+QPainter。<BR/>
气泡式聊天的显示是由QListWidget作为控件，每个气泡是由QListWidgetItem提升成QWidget来实现的。每个气泡可以理解为可以自由布置里面内容的QWidget。每个Item保存聊天的对话、发送状态、时间、种类等。这个QWidget主要是显示一个头像+气泡，气泡里面是聊天的内容等。气泡是在paintEvent事件中，采用QPainter来绘制的。 