# Financial_Application
A digital mortgage loan qualifier app that runs on the comand line, there we can ask our client/user for there information that the app requaier and the right path to set the new csv_file for the qualify loans if any.

---
## Technologies
This python 3.8.3 program use the following libraries: sys, fire, questionary, and pathlib current on 10/2/2021. It was tested in a git bash/ power-shell/ VScode environment in Windows 10.

It uses calculator functions like: calculate debt, loan to value ratios and more, also we have filters functions like: debt to income ratio, loan to value ratio compared to the user entered amounts, loan size and credit score.

It has already implemented functions to load and save CSV files.

---

## Installation Guide
Installation of Python, gitbash for windows users, questionary, and fire. It was tested on Python 3.8.3.

**Check:** 
- [Python](https://www.python.org/downloads/)
- [Gitbash](https://gitforwindows.org/)

For questionary and fire to work, you must type in git bash/power-shell/comand-line or mac terminal:

> pip install questionary

> pip install fire

**Documentation Links:**

- [Pathlib](https://docs.python.org/3/library/pathlib.html)

- [Questionary](https://pypi.org/project/questionary/)

- [Sys](https://docs.python.org/3/library/sys.html)

- [Fire](https://google.github.io/python-fire/guide/)

---

## Usage
We need to input the csv_file, as in the following example:

![](https://github.com/rulo96z/Financial_Application/blob/master/pics/cvs_file_pic.png?raw=true)

The git-bash, command-line or power-shell can run this app program with the following code line: 

> ```python app.py```

As we can see all this line is doing is calling python and inputting the name of the file of our application, in this case ```app.py```.

In the following example we can see some usage functionality: 

![](https://github.com/rulo96z/Financial_Application/blob/master/pics/example-of-use.png?raw=true)

---
## Contributors
This code was shared in 2021 Education Services at UCB. 

Additional updates/ uploads for usability was added by raul@nogalesfundmgmt.com

---

## License
MIT License

Copyright (c) 2021 Raul 

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

