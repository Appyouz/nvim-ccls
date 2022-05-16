# nvim

A personal Neovim config 

## Installation 
Takes arch linux as a platform, just use your respective package manager for installing packages(for eg:- `sudo apt install` for debian)

1. Install [Node.js](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwiehrffoeT3AhWeRmwGHcKWAoYQFnoECAgQAQ&url=https%3A%2F%2Fnodejs.org%2F&usg=AOvVaw1tY2p-vJFWJmxWlq4sTxCn)
``` bash 
sudo pacman -S nodejs
``` 
2. Install [Ccls](https://github.com/MaskRay/ccls)

 ``` bash
 sudo pacman -S ccls
 ```
 
3. You will be needing [vim-plug](https://github.com/junegunn/vim-plug#installation) to install the required plugins.



## Usage
 - Once you are done installing vim-plug, 
 - Make a new directory inside `.config` folder named as `nvim` ( `mkdir .config/nvim`) or just clone it inside .config <br>
 - open up the `init.vim` file and use the following commands<br>
 - (you might see some warnings just dont freak out, everything will be fine once we done installing plugins) :

```bash
:PlugInstall
```
That's it you are now good to go if no errors were occured



## License
[MIT](https://choosealicense.com/licenses/mit/)
