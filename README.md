
# Custom bash and vim settings

### One proposed way to use bash configuration in the __bashrc__<sup>*</sup> file in this repo:
- Make a safe copy of your existing _~/.bashrc_ file
```sh
cp ~/.bashrc ~/.bashrc_backup_$(date +"%Y%d%m_%H%M%S")
```
- Clone this repo or download the raw _bashrc_ file from this repo
- Open __~/.bashrc__ and add _one_ of the following two lines<sup>**</sup> at the end of __~/.bashrc__ file:

```sh
source ~/bashrc_etc/bashrc
```

--OR--

```sh
source ~/bashrc_etc/bashrc --verbose
```
<sup>*</sup>Note that there is __<ins>no</ins> dot . prefix__ in this filename

<sup>**</sup>Adjust the path in these lines to point to the directory where your **_bashrc_** actually is

---

### One proposed way to use vim configuration in the __vimrc__<sup>^</sup> file in this repo:
- Make a safe copy of your existing _~/.vimrc_ file
 e.g.
 ```sh
 mv ~/.vimrc ~/.vimrc_backup_$(date +"%Y%d%m_%H%M%S")
 ```
- Clone this repo or download the raw _.vimrc_ file from this repo
- Make a symbolic link to point __~/.vimrc__ to this repository's __vimrc__<sup>^^</sup>:
```sh
ln -s ~/bashrc_etc/vimrc ~/.vimrc
```
<sup>^</sup>Note that there is __<ins>no</ins> dot . prefix__ in this filename

<sup>^^</sup>Adjust the path in these lines to point to the directory where your *__vimrc__* actually is
---


