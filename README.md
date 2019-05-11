# NAME

md2html bash script extending `markdown` command.

# SYNOPSIS

- md2html [input path]
- md2html [input path] > [output path]

# DEPENDENCY

- [markdown](https://manpages.debian.org/stretch/markdown/markdown.1.en.html)
- [envsubst (in gettext)](https://manpages.debian.org/jessie-backports/gettext-base/envsubst.1.en.html)

`sudo apt install markdown gettext` to install them.

# INSTALL

Simply download `md2html` and put it on your $PATH, and execute `chmod 755 md2html` to make it executable.

# CUSTOMISE

Simply edit `md2html`. The html template is directly written there.
