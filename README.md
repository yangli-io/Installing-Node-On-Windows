# Installing Node On Windows
An attempt at fixing the windows node installation issues

### Installing node
Installing node is not the hard bit, simply go to [the node.js homepage](https://nodejs.org/en/) to download the latest version of node or if you need an earlier version then [go to here](https://nodejs.org/dist/).  Once you have this installed, you can run node on your windows machine. However! Some node modules requires node-gyp which in turn requires python and c++, this becomes an issue. So we'll need to install those.

### Installing Python
Go to the [Python homepage](https://www.python.org/downloads/) and download/install a 2.7.x version of python.  Find this version of Python in your file system, it's usually under C://.  Find the path and add it to your environment path

### Install Visual Studio Express 2013
You will need this to run some of the node-gyp packages, you can find and install [VS express 2013 here](http://www.microsoft.com/en-au/download/details.aspx?id=44914).  Once you install this, go into your powershell terminal and enter 

```
npm config set msvs_version 2013 --global
```
