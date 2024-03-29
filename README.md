# OWL Tool
## Description
Every time a consultant completes an OWL, 
they have to insert a page break, copy over their front note, 
fill out the front note, rename the document, 
and save the document to wherever they want to permanently save it. 
This script automates that process.

## Use
Create a template file. The beginning of the template text within the template file
is denoted by and opening `#` and a closing `#`. Within the template text, 
there are fillable regions. Fillable regions are marked with an opening
`<` and a closing `>`. Also, this script is only compatible with .docx files

### Configuration
This script will check, by default, the `~/.config/owl_tool/config` file. You can
save your download, template, and save path using the following format: `download_path = path`

These paths can also be passed using flags. `-s` or `--save` for the save path, 
`-t` or `--template` for the template path, and `-d` or `--download` for the download path.

Finally, if no paths are passed, or if no config file is found, then the user
will be prompted for these variables when running the script.

## Installation
You can clone this package using `git clone https://github.com/jefrecantuledesma/owl_tool`. 
From there, you must have `python-docs` installed. This can be done by running:
```
pip install python-docx
```
Or, if you're running Arch:
```
pacman -S python-docx
```

From there, all you must do is `python main.py`, and you're good to go!
