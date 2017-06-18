
# semicolon-rescue
Vim Plugin to highlight characters that look like semicolons, but aren't, e.g. ;

# Semicolon Lookalikes?!
I guess you might have already come across one of these posts:
![a twitter post about replacing ; with ;][tweet]

Most likely you put that away as a silly joke, but would you wanna risk it?  
You don't have to live dangerously any more, you can simply install this plugin and protect yourself!

[tweet]: img/tweet.png
# Installation
Best use a plugin installation tool like [Vundle](https://github.com/VundleVim/Vundle.vim)

```
Plugin 'sterereo/semicolon-rescue'
```
(put in your .vimrc)

# Screenshots
Are you 100% cetain that you could tell this:

![a picture of real semicolons][real]

from this at any point in time, after you worked already for hours after and your coworker *just fixed something*:

![a picture of semicolon-lookalikes ;][lookalike]

Well, now you can:

![a picture of semicolon-lookalikes ; marked][marked]

[real]: img/legit_semicolon.png
[lookalike]: img/lookalike.png 
[marked]: img/marked.png

# Style Options
The semicolon-lookalikes ; are added to the `Error` syntax-highlighting group, so your active colorscheme determines the style.

# About
Created out of pure caution and with absolute seriousness.

Find this project on [GitHub](https://github.com/sterereo/semicolon-rescue).

# License
This project is licensed under the [Do What the Fuck You Want to Public License (WTFPL)](https://www.wtfpl.net/).

```
            DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
                    Version 2, December 2004

 Copyright (C) 2017 Rolf Pfeffertal

 Everyone is permitted to copy and distribute verbatim or modified
 copies of this license document, and changing it is allowed as long
 as the name is changed.

            DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
   TERMS AND CONDITIONS FOR COPYING, DISTRIBUTION AND MODIFICATION

  0. You just DO WHAT THE FUCK YOU WANT TO.
```
