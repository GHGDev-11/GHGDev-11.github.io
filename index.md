# Welcome to Bare
#### The most human-sounding language in the world!
## Installing and testing
To start off, [download and install Bare from our official website](https://bare-language.carrd.co) if you haven't already.\
After installing Bare, go to directory `C:\Program Files (x86)\Bare\installation` and open `BareInstaller.exe`. This will register Bare in your Windows system.\
To create a new file, right click -> New textdocument and rename it to `[Whatever you'd like].ba`.

# Batl - The Bare Editor Tool
If you want to use Batl, the Bare Editor Tool, open Command prompt (cmd) and type "Batl {Your file name}.ba". It will open Batl with your file.

# Bare's Syntax
Before I show you Bare's syntax, I'm just going to say this: It's really easy. Anyone can understand this. If you don't, don't be demotivated, but [join our discord](https://discord.gg/eNmS9jP) to get help!

# Keywords
Keywords are statements that are defined internally. You don't need any *atoms* (Bare's libraries) to use them.
### Keyword: say
To put text on the screen, (Python: `print()`, Javascript: `console.log()`, C#: `Console.WriteLine()`, etc...) use the keyword "say".
```py
say 'Hello world!'
```
### Keyword: ask
To ask for input, use the keyword "ask".
```py
ask 'Username: '
```
You can also only write "ask", so it will just take someone's input and put nothing on the console.
### Keyword: hyperlink, lookup.key
You can open a link or lookup a keyword through your webbrowser with Bare with `hyperlink` and `lookup.key`. \
**You will always have to have "http://" or "https://" at the start of a link! It will otherwise return an error.**
```py
hyperlink 'bare-language.carrd.co'
lookup.key 'Bare language'
```
