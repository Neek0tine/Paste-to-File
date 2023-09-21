# Paste-To-File


<a href="https://github.com/Neek0tine/Paste-to-File"><img src="https://github.com/Neek0tine/Neek0tine/blob/main/stuff/paste-to-file-banner.gif" alt="Procrastinate" width="1080"/></a><br>

Paste-To-File is a simple Python programs that lets you paste image or text from your clipboard straight into a file. A roundabout way to achieve similar thing is to firstly paste the content of the clipboard into notepad or paint app if it's an image data and saving it. For extra simplicity, this program adds a new command item to Explorer's right-click context menu to paste clipboard items into the directory the right-click is placed on.

## Installation

<img src="https://github.com/Neek0tine/Neek0tine/blob/main/stuff/disclaimer.png" alt="BE CAREFUL." width="1080"/>

This program is dependent on these modules:
- `winreg`
- `pillow`
- `pywin23`

Which could be installed by using `pip`

1. Download and extract the project into a directory
2. Running `make_reg.py` will create a shortcut to the program in your right-click context menu.
3. Running `delete_reg.py` will delete the shortcut from your right-click context menu
4. Running `paste2file.py` by itself will paste whatever you have on your clipboard last to be saved in current directory.

You can edit the `make_reg.py` file to set which python environment you will use. (the default is global)

The registry will target the extracted project directory by default (portable installation). Make sure to extract the project files somewhere permanent.

Deletion of the `src` directory after `make_reg.py` has been run WILL NOT delete the command from the right-click context menu, but doing so will render the command unusable.

## End-User License Agreement
As per the MIT License:

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
1. The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

2. THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


## Authors
* **Nicholas Juan Kalvin**  [Neek0tine](https://github.com/Neek0tine)

## Contributing
Pull requests are welcome. For major changes, how-to, and in-depth explanation, please contact one of the authors.
## License
<br>
This project is licensed under GNU General Public License v3.0 - see the [LICENSE](https://github.com/Neek0tine/Paste-To-File/blob/main/LICENSE) file for details.