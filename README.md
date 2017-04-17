## Agnoster-kp
___

As a programmer I spend more time in the console than on any other application on my [kde neon](http://neon.kde.org) box so I love the console to be as aesthetically pleasing as possible. So I decided to tweak agnoster ( provided in [robbyrussell's oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) framework. ) to my own taste.

### Installation

- Make sure you have [robbyrussell's oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) framework installed.

- Clone this repository. Or [download](https://github.com/paradzayi/agnoster-kp/archive/master.zip) the zip file.
```sh
 $ git clone https://github.com/paradzayi/agnoster-kp.git
```

- Enter the agnoster directory and copy the ```agnoster-kp.zsh-theme``` file to the ```/home/$USER/.oh-my-zsh/themes``` where ```$USER``` is the name of your account.

- Find the ```/home/$USER/.zshrc``` and open it in your favourite text editor. Locate the line where it says
```
ZSH_THEME="$THEME_NAME"
```
where ```$THEME_NAME``` represents the current active zsh theme.

- You are all set

### How it differs from agnoster

**agnoster-kp is different in that:**
 * you start typing on a new line
 * there is a $ sign before every command you type in.

 >_I think this saves you some space on the screen yet still providing the same comprehensive information that is typical of the original agnoster theme._

It can be best illustrated in images. Spot the difference :wink:

  #### Robby Russell's Agnoster
  ![](/images/agnoster.png)

  #### Kudakwashe Paradzayi's Agnoster-kp
  ![](/images/agnoster-kp.png)

### Supported operating systems

  I tested this theme on [kde neon](http://neon.kde.org) in the terminal app [konsole](https://konsole.kde.org/download.php).

   - [Ubuntu](http://ubuntu.com) and its derivatives ( [kde neon](http://neon.kde.org), [mint](http://linuxmint.org), [elementary os](http://elementary.io), etc )
   - Mac OS
   - Any OS that can have oh-my-zsh installed
   - Anyone to help with windows :cry:

### Licence

  Agnoster-kp theme is released under the MIT licence. [Read more](/README.md)
