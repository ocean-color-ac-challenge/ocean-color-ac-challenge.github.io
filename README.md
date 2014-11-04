# ocean-color-ac-challenge.github.io

Organization ocean-color-ac-challenge website

### Building this documentation

This documentation is generated by [Rgitbook](http://jason.bryer.org/Rgitbook/).

It allows inserting R chunks in the documention and have these executed when building. 

## Install the dependencies

The recipe provided targets a CentOS 6.5 environment. You may have to adapt it to your environment.

**For Rgitbook** 

As root, run the commands: 

```bash
yum install -y R libcurl-devel libxml2-devel npm
npm install gitbook -g
```

Then in an R console, run:

```coffee
install.packages("devtools", dependencies=TRUE)
devtools::install_github("jbryer/Rgitbook")
```

## Building the documentation

* Clone this repository

```bash
cd
git@github.com:ocean-color-ac-challenge/ocean-color-ac-challenge.github.io.git
```

* Checkout the branch you want to publish (e.g. when the Challenge is visible)

```bash
cd ocean-color-ac-challenge.github.io
git checkout visible
mvn site-deploy
```
