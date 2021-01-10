This page contains content that is a prerequisite for this course. These include the following:
* [Installing Python](#installing-python)
* [Installing pip](#installing-pip)
* [Installing Anaconda](#installing-anaconda)
* [Installing Jupyter](#installing-jupyter)

# Installing Python
To start this course, you need first to install Python on your operating system. You can easily download and install this programming language through its [official website](https://www.python.org/). Installing this language for your operating system is very easy, but you can also use the following guides:
* [Using Python on Windows](https://docs.python.org/3/using/windows.html)
* [Using Python on a Macintosh](https://docs.python.org/3/using/mac.html)
* [Using Python on Unix platforms](https://docs.python.org/3/using/unix.html)
* [How To Install Python 3 On Windows 10](https://phoenixnap.com/kb/how-to-install-python-3-windows)
* [How To Install Python (Persian version)](https://blog.faradars.org/%D9%86%D8%B5%D8%A8-%D9%BE%D8%A7%DB%8C%D8%AA%D9%88%D9%86-%D8%AF%D8%B1-%D9%88%DB%8C%D9%86%D8%AF%D9%88%D8%B2/)

After installing Python, you can get the various valuable packages through Pip or Anaconda.

# Installing Pip
pip is already installed if you are using Python 3 downloaded from python.org. You can use the following command to check if pip is installed on your system or not?
* **Windows:** `pip help`

If you see a message like the one below, pip is installed on your Windows; otherwise, you can follow the steps below to install pip.

![2021-01-08_16-25-36](https://user-images.githubusercontent.com/8090866/104019939-a7ca4d80-51d1-11eb-9005-f79b4d331798.png)


1. Download [get-pip.py](https://bootstrap.pypa.io/get-pip.py).
2. Open a Command Prompt and navigate to the folder containing the get-pip.py.
3. Run `python get-pip.py`
4. You can upgrade pip with `python -m pip install --upgrade pip`


* **Unix/macOS:** You can install pip on Unix / macOS via this [link](https://ahmadawais.com/install-pip-macos-os-x-python/).


# Installing Anaconda
Anaconda is one of the easiest ways to access packages developed for the R and Python programming languages. Anaconda can be easily downloaded through its [official website](https://www.anaconda.com/products/individual). Once Anaconda is installed on your system, it is easily accessible via Anaconda Prompt on Windows or Terminal on Linux and macOS.

You can also install Miniconda instead of Anaconda. According to its [official website](https://docs.conda.io/en/latest/miniconda.html) Miniconda is a free minimal installer for conda. It is a small, bootstrap version of Anaconda that includes only conda, Python, the packages they depend on, and a small number of other useful packages, including pip, zlib and a few others. Use the `conda install command` to install 720+ additional conda packages from the Anaconda repository.

# Installing Jupyter
[Jupyter ](https://jupyter.org/)is a free, open-source, collaborative online tool regarded as a computing notebook for data scientists. You can integrate your codes, outputs, and multimedia resources in a single document. You can read this useful article about [Why Jupyter is data scientists’ computational notebook of choice](https://www.nature.com/articles/d41586-018-07196-1). 

Jupyter developed a web-based interactive environment for data analysis that has been called [JupyterLab](https://youtu.be/A5YyoCKxEOU). JupyterLab can support a wide variety of workflows in scientific computing and machine learning.  In JupyterLab, you can open and edit multiple notebooks simultaneously. And use the packages.
You can install JupyterLab using the following methods:
* Using pip: `pip install jupyterlab`
* Using Anaconda and Miniconda: `conda install -c conda-forge jupyterlab`

After installing JupyterLab, you can run it using the `jupyter lab` command. JupyterLab will open automatically in your browser.
 
