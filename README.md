lchttpd
=======

LiveCode HTTP Server. It is influenced by modern web app server frameworks like express for node.js. You can assign object to act as a Router, and as a MiddleWare stack.

NOT FOR PUBLIC FACING WEB SITES
=======

LiveCode is single threaded and blocking. It will NOT handle many connections.

This is for inter-process or inter-app communications. You could build API's to LiveCode Apps, or communicate back to a LiveCode app from a spawned process that speaks HTTP.

Credits
=======
The code for accepting socket connections and responding was copied from mchttpd.mc, an implementation of a web server written in MetaCard, and maintained by fourthword.com

Installation
======
This code is maintained using lcVCS. If you want to build from srouce or contribute to this project you will need that plugin.  
OR  
You can download the stacks from the [wiki](https://github.com/toddgeist/lchttpd/wiki).

Take a look at the lcHTTPdTest.livecode for how to use it in your project.

Video Intro
======

http://youtu.be/cfHLgHCsZTc
