# OWL Tool
## Description
<p>Every time a consultant completes an OWL, 
they have to insert a page break, copy over their front note, 
fill it out the front note, rename the document, 
and save the document to wherever they want to permanently save it. 
This script automates that process.</p>

## Use
<p>Create a template file. The beginning of the template text within the template file
is denoted by and opening ```#``` and a closing ```#```. Within the template text, 
there are fillable regions. Fillable regions are marked with an opening
```<``` and a closing ```>```.</p>

### Configuration
<p>This script will check, by default the ```~/.config/owl_tool/config``` file. You can
save your download, template, and save path using the following format: ```download_path 
= path```.</p>

<p>These paths can also be passed using flags. ```-s``` or ```--save``` for save path, 
```-t``` or ```--template``` for template path, and ```-d``` or ```--download``` for download path.</p>

<p>Finally, if no paths are passed, or if no config file is found, then the user
will be prompted for these variables when running the script.</p>
