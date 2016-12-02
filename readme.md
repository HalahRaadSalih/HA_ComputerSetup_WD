## MacBook Settings/Tools for Web Development
So you got a new mac or feeling rusty about web dev? This repo will contain steps/tools to download to get started as a web developer.

**Note:** Unsure whether you have one of these tools installed? Open your terminal and use this command to check:
  ```
  $ [tool name] --version
  ```

**Note:** All commands listed below run in the terminal.

### NodeJS

According to [NodeJS](https://nodejs.org/en/) website:

>Node.js® is a JavaScript runtime built on Chrome's V8 JavaScript engine. Node.js uses an event-driven, non-blocking I/O model that makes it lightweight and efficient. Node.js' package ecosystem, npm, is the largest ecosystem of open source libraries in the world.

<br>
 - **Simpler definition is:** NodeJS is a framework that is asynchronous, event-driven and let's you use JavaScript on the server side.


 - **What is Javascript Runtime?** It's an environment that provides built in libraries during runtime. For NodeJS, the libraries are  the file system, events, http ... etc.

 - **What is Chrome's V8 Javascript Engine?** [Javascript Engine](https://developers.google.com/v8/) written in C++.

 - **What is the difference between Javascript runtime and Javascript engine?** The engine parses the code and transform it to optimized code that can be interpreted by a browser or even embedded into an application ( it interprets and executes your code). The runtime is an environment that provides built it libraries during runtime for the browser it would be the window object, DOM API, for NodeJS, it would be processes, the file system, event, http and url.

 - **Event Driven?** The application control flow is determined by events. There is an architecture that listens to events and invoke a callback function once that event take place. The objects that emit events are called **emitters** and the functions listen to those events are called **listeners**.

 - **Non-Blocking I/O Model? How does it make NodeJS efficient and lightweight?**
 Non-Blocking means code doesn't block execution. When you're reading from a file, you can still have other code execute. More details about how this is more efficient in comparison to other java or php servers [here](http://stackoverflow.com/questions/10570246/what-is-non-blocking-or-asynchronous-i-o-in-node-js).


 - [**NPM?**](https://docs.npmjs.com/getting-started/what-is-npm) It stands for Node Package Manager. Javascript developers made Packages (libraries, modules) for you to reuse. NPM handles the process of installing and updating these packages if there are any updates. These packages are usually small.  Example of how to install a Package:
 ```
  $ npm install express
 ```

#### Installation Steps
Check your computer specification before you download NodeJS from [here](ttps://nodejs.org/en/download/).

### Git & GitHub
Install Git from [here](https://git-scm.com/download/mac).
 - Before generating SSH key, check if you have existing keys:

 ```
 $ ls -al ~/.ssh
 ```
 - If you don't have any keys or you want new ones, proceed to the next step.
 - Best resource for this github itself, so I'll just link you: [Generate ssh keys and add to user agent](https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/).

 - The first thing you need to do once you got git all set is to configure your identity(name, email). To do that use the command `$ git config` and do the following:
  - Set git config globally ( the name and the email must be between quotations)<br>
 	<br>
 	```
 		$ git config --global user.name [your desired name]
 	 ```
 	 ```
 	 	$ git config --global user.email [your github email]
 	 ```

   - to check what is the current name and email just run

   	 `$ git config user.name` , `$ git config user.email`.

 <br>
 - [Oh My Zsh](https://github.com/robbyrussell/oh-my-zsh) (note, must install Git before oh my zsh)
 - [Homebrew](http://brew.sh/)
 - [Brew install tree command](https://rschu.me/list-a-directory-with-tree-command-on-mac-os-x/) (must install homebrew first).
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
 - BABEL JS
 - Browsify