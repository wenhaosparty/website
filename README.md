Website
=======

This repository hosts the source code for generating the [Spyder IDE](http://spyder-ide.org) Website using [Pelican](http://getpelican.com), a static python website generator. If you want to give it a try just clone the repository or fork it if you feel like submitting some changes!

Download 
--------
```bash
git clone https://github.com/spyder-ide/website.git spyder-website
cd spyder-website
```

Installation
------------

**Using conda**

You need to have the anaconda distribution by continuum installed.

```bash
conda create --name spyderweb python=2.7 pip --yes 
source activate spyderweb
pip install -r requirements.txt
```

**Using pip and virtual env**

```bash
virtualenv .env
source .env/bin/activate
pip install -r requirements.txt
```

Fresh install (install latest available packages)
-------------------------------------------------

**Using conda**

You need to have the anaconda distribution by continuum installed.

```bash
conda create --name spyderweb python=2.7 pip --yes
source activate spyderweb
pip install fabric pelican markdown beautifulsoup4 libsass
```

**Using pip and virtual env**

```bash
virtualenv .env
source .env/bin/activate
pip install fabric pelican markdown beautifulsoup4 libsass
```

Run test site locally
---------------------

```bash
cd spyder-website
fab reserve
```

TODO LIST:
==========  
* Take better pictures (up to date) for the features page

