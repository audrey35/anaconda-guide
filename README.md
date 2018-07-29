# What is Conda and why should you install it?

Are you a Python newbie? Or had trouble installing new Python packages? Pulled your hair out trying to figure out why `import <package-name>` doesn't work after installing a package? If you answered yes to any of these questions, Conda might just save your day. Conda is a Python package and environment manager that makes installing Python packages easy and pain-free.

Conda is ideal if you want:

* a way to install Python packages without worrying about dependencies (some packages require installing other packages for them to work)
* install Python packages needed for a project and uninstall the packages easily when you don't need them anymore (install packages in an environment and delete the environment later to free up space)
* need to a easy way to use both Python and R programming languages
* an open-source package manager for Python and R (Anaconda Distribution is the free option)

[More information on Anaconda Distribution](https://docs.anaconda.com/anaconda/)

There are some choices you need to make before installing Conda. 

* Anaconda vs. Miniconda
  * recommend Miniconda, which is lightweight and because you get to choose the packages to be installed
* Python 3.6 vs. Python 2.7: 
  * Python 3.6 recommended even if you plan to use Conda with other software that use Python 2.7 such as ArcGIS Desktop because Conda comes with both Python 3.6 and 2.7
  * the choice is for Conda's default Python version
* 64-bit vs. 32-bit
  * 64-bit recommended if you don't have to worry about compatibility with other software
  * [ArcGIS Pro already has Conda](http://pro.arcgis.com/en/pro-app/arcpy/get-started/what-is-conda.htm) installed by default so no need to install another Conda
  * ArcGIS Desktop is 32-bit so 32-bit Conda should be installed ([Install Anaconda with ArcGIS Desktop](https://my.usgs.gov/confluence/display/EGIS/Using+Anaconda+modules+from+the+ESRI+python+environment))

## Anaconda vs. Miniconda

Anaconda provides two installers: Anaconda or Miniconda. 

[Anaconda or Miniconda? - Official Documentation](https://conda.io/docs/user-guide/install/download.html#anaconda-or-miniconda)

Anaconda is best if you are new to conda/Python and can afford to sacrifice 3GB of your computer space.



Miniconda is best if you are more experienced in conda/Python and want a lightweight installation. Also, you do not mind installing the packages you need on your own.

## Python 3.6 vs. 2.7



## Install Anaconda/Miniconda on Windows

If you figured out which one you'd like to install, go ahead and download the installer.

[Download Anaconda Installer](https://www.anaconda.com/download/#windows)

![DownloadAnaconda](https://github.com/audrey35/anaconda-guide/blob/master/images/DownloadAnaconda.png)

[Download Miniconda Installer](https://conda.io/miniconda.html)

![DownloadMiniconda](https://github.com/audrey35/anaconda-guide/blob/master/images/DownloadMiniconda.png)

Once you have downloaded a conda installer, simply run the downloaded .exe file and follow the instructions on the screen. 

![DownloadedExe](https://github.com/audrey35/anaconda-guide/blob/master/images/DownloadedExe.png)

![Miniconda3Installation](https://github.com/audrey35/anaconda-guide/blob/master/images/Miniconda3Installation.png)

![Miniconda3License](https://github.com/audrey35/anaconda-guide/blob/master/images/Miniconda3License.png)

![Miniconda3UserSetting](https://github.com/audrey35/anaconda-guide/blob/master/images/Miniconda3UserSetting.png)

Anaconda recommends installing in C:\anaconda [Documentation](https://docs.anaconda.com/anaconda/faq#in-what-folder-should-i-install-anaconda-on-windows)

![Miniconda3InstallLocation](https://github.com/audrey35/anaconda-guide/blob/master/images/Miniconda3InstallLocation.png)

Recommend not checking Add Anaconda to my PATH environment, unless this is the only Python installed on your computer. 

Recommend not checking Register Anaconda as my default Python 3.6, unless this is the only Python installed on your computer.

[Add Anaconda to my PATH environment variable](https://docs.anaconda.com/anaconda/faq#should-i-add-anaconda-to-the-windows-path)

![Miniconda3PathSettings](https://github.com/audrey35/anaconda-guide/blob/master/images/Miniconda3PathSettings.png)

Below are some links with detailed instructions on installation.

[Simple Windows Installation Instructions - Official Documentation](https://conda.io/docs/user-guide/install/windows.html)

[Detailed Installation Instructions - Official Documentation](https://docs.anaconda.com/anaconda/install/)
