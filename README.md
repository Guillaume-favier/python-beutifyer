# python-beautifyer 

python-beautify is an VSCode extention to beutify python scripts with yapf

## Features

Beautify python scripts using yapf

You can do this in two way :
 * Do `Ctrl+maj+P` and type python beautifyer and select your option
   * `Python beautifyer from all page` who just beautify all the page
   * `Python beautifyer form curent selection` who will beautify what do you have selected (Doesn't work with multiple selection)
   * `Python beautifyer addaptive` who wil check if there is a selection and will make the choice of converting all the page or the selection if there is one
 * In python files a new status will apared called : `python beautifyer` all at the right who will execute the `Python beautifyer addaptive`

![VS code exemple of the status bar](url=https://zupimages.net/viewer.php?id=20/51/r3zq.gif)

## Requirements

You just need python3-pip (what you should already have if you are programing in python) and shelljs

```sh
npm install -g shelljs
```

