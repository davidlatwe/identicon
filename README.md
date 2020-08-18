# Identicon

Identicon is a python 3 script which generates Github like identicons (the 
default avatar you get when you sign up for a Github account).

### Installation

```
git clone https://github.com/davidlatwe/identicon.git
```

### Usage

```
$ python identicon.py hello world
```

<img src="https://github.com/davidlatwe/identicon/blob/master/hello-world.png" width="250" height="250"/>

```
$ python identicon.py Thy bones are marrowless, thy blood is cold.
```

<img src="https://github.com/davidlatwe/identicon/blob/master/Thy-bones-are-marrowless--thy-blood-is-cold-.png" width="250" height="250"/>

```
$ python identicon.py bill.gates@microsoft.com
```

<img src="https://github.com/davidlatwe/identicon/blob/master/bill-gates-microsoft-com.png" width="250" height="250"/>

### Note

Help message

```
$ python identicon.py -h
```

* Output image will be saved in current working directory.
* Input text will be used as file name, except non-alphanumeric charachter will be replaced with `"-"`.

### License

See the [LICENSE](LICENSE.md) file for license rights and limitations (MIT).

