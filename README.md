# Coding tools

## All the tools I use and their configuration.

In this repository you will find my different IDEs and text editors, configuration files and development advises.

### IDEs: (I no longer use those as I totally replaced them with Vim)
  * [Visual Studio code](https://code.visualstudio.com/)
  * [Android Studio](https://developer.android.com/studio)

### UNIX Text editors:
  * [Vim](https://github.com/vim/vim)
  * [Emacs](https://www.gnu.org/software/emacs/)

### Win Text editors:
  * [Notepad++](https://notepad-plus-plus.org/)
      - [Compare plugin](https://sourceforge.net/projects/npp-compare/) Allows comparing two files like WinMerge.
      - [Converter plugin](https://github.com/npp-plugins/converter) Allows to convert some ASCII in HEX and reverse.

  You will find a list of the plugins I used on my old ST3 setup [here](https://github.com/jelek21/Coding_Tools/blob/master/ST3/STPlugins.md) and a list of config files [there](https://github.com/jelek21/Coding_Tools/blob/master/ST3/ST3Setup.md)
  I stopped using ST because it is not free and open source, making it more difficult to use in a pro environment, also, I did eventually install way too much plugins, making it totally bloated... It has been a fun journey with it, but taking a little bit of training on vim is definitely worth it!

  You will also find my [.gitconfig](https://github.com/jelek21/Coding_Tools/blob/master/.gitconfig) file that is located in your /home/username folder under Linux.

  For coding tools and Tips, there is a cool document in [scrassmussen/tools](https://github.com/scrasmussen/tools) repository.
  Go check it out it is really well written and there are some cool tips and tools for programming.

### Documenting code
  For documentation, I actually use [Doxygen](http://www.doxygen.org/). As I always work with other people and often have to give out my code to other devs, I pay a huge attention to document as well as possible my code, I strongly advise you to do so, not only it helps other devs, but when I get back on my own code I save a lot of time!

### Linux under Windows : I like WSL2!
  I often use Linux to work, even if I am locked on a Windows computer, since Win10, there is the [Windows Subsystem for Linux(WSL)](https://docs.microsoft.com/en-us/windows/wsl/about) that allows you to run a Bash terminal under Windows 10.
  I personally like to work with [Arch WSL](https://github.com/yuk7/ArchWSL) as Archlinux has some of the most up-to-date repositories, allowing me to always work with the latest versions of my software.

  As I often use the WSL and powershell, I installed [Terminus](https://eugeny.github.io/terminus/) on my computers, it is a tool allowing you to emulate a terminal with the specifications and customisation you want to have, it is a pretty and simple to use tool and it changes your life. If you are more on the light size and want something also well customizable, you shall try [alacritty](https://github.com/jwilm/alacritty).

### Some Daily tools
  * [WinMerge](http://winmerge.org/?lang=fr) A very useful tool allowing comparing two files and to merge those files.
  * [SublimeMerge](https://www.sublimemerge.com/) A cool tool developed by the same team as SublimeText which allows you to manage your git repositories very easily and with a nice UI.
  * [MobaXterm](https://winscp.net/eng/index.php) An FTP tool supporting SFTP(FTP under SSH), pretty cool as it supports X11 forwarding (will also allow you to run graphical software with WSL), it also has an SSH client, a WSL terminal, ...
  * [PuTTy](https://www.putty.org/) A very complete SSH client for windows, it also supports Serial communication, Telnet, rlogin and TCP.
  * [gnuplot](http://www.gnuplot.info/) A cool tool, it can read every text file containing column of data and plot it into a very clean graph, it needs a bit of work to learn how to use it but [here](https://people.duke.edu/~hpgavin/gnuplot.html) is a cool tutorial.
