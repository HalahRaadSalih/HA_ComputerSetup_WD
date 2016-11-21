## MacBook Settings/Tools for Web Development
So you got a new mac or feeling rusty about web dev? This repo will contain steps/tools to download to get started as a web developer.

### NodeJS

According to [NodeJS](https://nodejs.org/en/) website:

>Node.js® is a JavaScript runtime built on Chrome's V8 JavaScript engine. Node.js uses an event-driven, non-blocking I/O model that makes it lightweight and efficient. Node.js' package ecosystem, npm, is the largest ecosystem of open source libraries in the world.

<br>

 - **What is Javascript Runtime?** It's an environment that provides built in libraries during runtime. For NodeJS, the libraries are  the file system, events, http ... etc.

 - **What is Chrome's V8 Javascript Engine?** [Javascript Engine](https://developers.google.com/v8/) written in C++.

 - **What is the difference between Javascript runtime and Javascript engine?** The engine parses the code and transform it to machine code eventually ( it interprets and executes your code, the runtime is an environment that provides built it libraries during runtime for the browser it would be the window object, DOM API, for NodeJS, it would be processes, the file system, event, http and url.

 - **Event Driven?** The application control flow is determined by events. There is an architecture that listens to events and invoke a callback function once that event take place. The objects that emit events are called **emitters** and the functions listen to those events are called **listeners**.

 - **Non-Blocking I/O Model? How does it make NodeJS efficient and lightweight?**


 - **NPM?**

#### Installation Steps
Check your computer specification before you download NodeJS from [here](ttps://nodejs.org/en/download/).

 - [Git](https://git-scm.com/download/mac)
 - [Oh My Zsh](https://github.com/robbyrussell/oh-my-zsh)
 - [Generate ssh keys and add to user agent](https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/)

 - Set git config globally ( the name an the email must be between quotations)<br>
 	<br>
 	```
 		$ git config --global user.name [your desired name]
 	 ```
 	 ```
 	 	$ git config --global user.email [your github email]
 	 ```
 <br>
 - [Homebrew](http://brew.sh/)
 - [Brew install tree command](https://rschu.me/list-a-directory-with-tree-command-on-mac-os-x/) (must install homebrew first)


 - [Gulp](https://www.npmjs.com/package/gulp), [Tutorial](https://travismaynard.com/writing/getting-started-with-gulp).
 - [Atom](https://atom.io/).
 - apm (atom package manager, installed with atom).
 - Atom packages ([script](https://github.com/rgbkrk/atom-script), [minimap](https://github.com/atom-minimap/minimap), [merge-conflicts](https://github.com/smashwilson/merge-conflicts), [activate-power-mode](https://atom.io/packages/activate-power-mode)(for fun).<br>
 <br>
    `$ apm install script minimap merge-conflicts activate-power-mode`
 <br>
 <br>
 - [MacDown](http://macdown.uranusjr.com/) (in order to use this command `$ macdown [file name]`, make sure you link the macdown bin to usr/local bin using the following command :

  ``$ ln -s [path to your macdown bin] [path to your usr/local/bin]
  ``
  <br>

 - [Java stuff, JSK](http://www.oracle.com/technetwork/java/javase/downloads/index-jsp-138363.html)
