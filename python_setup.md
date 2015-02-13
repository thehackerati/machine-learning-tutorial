#Preparing python for machine learning

## If python is not installed
[Download and install](https://www.python.org/download/releases/2.7/) using the installer appropriate for your OS.

## Make sure you have pip
Follow the installation instructions on the [pip website](https://pip.pypa.io/en/latest/installing.html#install-or-upgrade-pip).

You will download a script called get-pip.py, and then run it as follows:

```bash
python get-pip.py
```

If you get a permissions error, then rerun as:
```bash
sudo python get-pip.py
```

## Generally a good idea for python development on Linux

```bash
sudo apt-get install python-dev
```

## Set up your virtual environment

Install virtualenv:

```bash
pip install virtualenv
```

Navigate to the python directory for this course, and enter:

```bash
virtualenv env
```

Now, install the requirements (which include python tools for data science and machine learning):

```bash
pip install -r requirements.txt
```