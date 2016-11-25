# ScrapeSnapdeal
>Scrape the Users Review from Snapdeal supports python 3.5

#Installation
1- Install python 3.5 from [Python.org](https://www.python.org)

2- `python setup.py` or `python3 setup.py`

  This will install all these packages

  * `pip install bs4`

  * `pip install requests`

  * `pip install urllib`

  * `pip install selenium`

3- Install Mozilla Firefox V40 or V47 and set the path in the `run.py` by default it is `C:\Program Files (x86)\Mozilla Firefox\Firefox.exe`

4- Install [PhantomJS](http://phantomjs.org/) and set its executable path in the `run.py`

5- Install Chromedriver for Chrome users, it is uploaded in this package there is no need to set path for the chromedriver

After the installation, open terminal at the root folder--

Run `python run.py` or `python3 run.py` to get individual reviews at the terminal screen or cmd.

##Some Useful Installation Tips

If you have already installed python 2.7 install python 3 as well but it may be the problem that the packages installed with respect to python 2.7 and shows error for the python 3 packages,

So you need to install virtual Environment for the python 3 to install python3 packages.

```
    virtualenv -p /usr/bin/python3 py3env
    source py3env/bin/activate
    pip install package-name
```

After setting virtual environment install packages listed above and Enjoy.

##Limitation

Does not work on ubuntu due to some hardware issues, Anyone who would like to contribute are welcomed.

#License

Copyright (c) 2016 Ankit Jain - Released under the MIT License

P.S For more python scripts Go To -> [pythonResources](https://github.com/ankitjain28may/pythonResources)