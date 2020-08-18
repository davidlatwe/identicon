# Identicon

Identicon is a python 3 script which generates Github like identicons (the 
default avatar you get when you sign up for a Github account).

# Installation

```
git clone https://github.com/davidlatwe/identicon.git
```

# Usage

Generate an identicon image with any text input:

> python identicon.py hello world

Output:

<img src="https://github.com/davidlatwe/identicon/blob/master/hello-world.png" width="250" height="250"/>

> python identicon.py Thy bones are marrowless, thy blood is cold.

Ouput:

<img src="https://github.com/davidlatwe/identicon/blob/master/Thy-bones-are-marrowless--thy-blood-is-cold-.png" width="250" height="250"/>

> python identicon.py bill.gates@microsoft.com

Output:

<img src="https://github.com/davidlatwe/identicon/blob/master/bill-gates-microsoft-com.png" width="250" height="250"/>

**Output image will be saved in current working directory.**

Help information:

> python identicon.py -h

# License

See the [LICENSE](LICENSE.md) file for license rights and limitations (MIT).

