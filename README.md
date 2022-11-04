# booky

booky is a very simple (KISS) and easily hackable bookmark manager written in pure POSIX sh!

**Usage:**

```
booky [-o|-c|-s]
        -a  Add selected bookmark to list
        -o  Select and open a URL in the browser
        -c  Copy selected URL to clipboard
        -d  Dump all bookmarks to stdout
        -s  Show statistics
        -v  Show version number
```


**Requirements:**
- xclip
- dmenu
- notify-send

**Install:**
1. Clone this repository
2. Change into the cloned directory
3. Run booky: **./booky**


**Note:**

booky by default accesses **$HOME/.bookmarks** as your bookmark file. This can be changed in the script via the **BOOKMARKS** variable.
