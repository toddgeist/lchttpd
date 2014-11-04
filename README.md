lchttpd
=======

LiveCode HTTP Server. It is influenced by modern web app server frameworks like express for node.js. You can assign object to act as a Router, and as a MiddleWare stack.

NOT FOR PUBLIC FACING WEB SITES
=======

LiveCode is single threaded and blocking. It will NOT handle many connections.

This is for inter-process or inter-app communications. 

Credits
=======
The code for accepting socket connections and responding was copied from mchttpd.mc, an implementation of a web server written in MetaCard, and maintained by fouthword.com
