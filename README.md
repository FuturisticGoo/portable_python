#  Python Portable

## What's this

This repository contains Python versions `2.6, 2.7, 3.1, 3.2, 3.3, 3.4, 3.5, 3.6, 3.7, 3.8` with some preinstalled packages, all in the form of portable software.  Tried doing it in `2.5` and `3.0` but failed miserably, so those versions aren't there.   

All of them are 32 bit for maximum compatibility, also this is Python for Windows, if that wasn't clear.

Each version has 3 zips - one with pip, setuptools, wheel installed, another with uncompyle6 installed and another one with both installed. This is the resource for the project [UnPYC](https://github.com/FuturisticGoo/UnPYC). 

## Codes

`wpsw` means it is **w**ith **p**ip, **s**etuptools, and **w**heel installed

`wu6` means it is **w**ith [**u**ncompyle**6**](https://github.com/rocky/python-uncompyle6) installed. This zip doesn't contain pip, setuptools or wheel.

`wpsw_wu6` means it is **w**ith **p**ip, **s**etuptools, **w**heel and **w**ith [**u**ncompyle**6**](https://github.com/rocky/python-uncompyle6) installed.

## Important info

pip only installs offline packages (`.whl`) in Python `2.6`, and needs to be invoked by python -m pip.\_\_main\_\_ <command>

pip only installs offline packages (`.whl`) in Python `3.1,3.2,`.

pip will get deprecated in Python `2.7, 3.3, 3.4, 3.5`

Python `3.5 - 3.8` are [Python embedded](https://www.python.org/downloads/windows/) with the above mentioned packages installed.

## License

Python is licensed under [PSF license](https://docs.python.org/3/license.html), and Uncompyle6 is licensed under [GPL v3](https://github.com/rocky/python-uncompyle6/blob/master/COPYING). This project is under MIT License, but doesn't cover uncompyle6, where it has it's own license applies.

## Contributing

If there's any issue with any of these zips, please open an issue. If you want to contribute by adding versions which aren't here, please create a pull request, containing both Python wpsw and Python wu6. Also, Python 3.9 isn't included here because uncompyle6 doesn't support it yet, so no need to add that now.
