# Trading Analysis Setup Zipline-Reloaded

This project demonstrates the use of Zipline-Reloaded for algorithmic trading with Python. The provided code includes steps to install Zipline-reloded, Ta-Lib, and wheel.

## Installation Guide

### Set Up Your Python Project

1.  **Install Python**: Ensure Python 3.10 is installed on your system. You can download it from the [official Python website](https://www.python.org/downloads/).
    or install using Microsoft Store.
    We used python 3.10 because ta-lib wheel has support only for 3.10.
    You can install wheel from the [github for wheel](https://github.com/cgohlke/talib-build/releases)

2.  **Create a Virtual Environment**:

        python -m venv venv

3.  **Activate the Virtual Environment**:

    - For Windows

             venv\Scripts\activate

    - For macOS/Linux

            source venv/bin/activate

4.  **Downgrade or Make compatible with version**

    -Step 1: Uninstall numpy

        pip uninstall numpy

    -Step 2: Install numpy to prevent from version conflict

         pip install numpy==1.24

5.  **Download wheel**

    - Make sure to Download wheel file from the [github wheel](https://github.com/cgohlke/talib-build/releases) and file name should be like **_TA_Lib-0.4.29-cp310-cp310-win_amd64.whl_**
    - Now move the file inside root directory of project directory.

    - My_Treding_Project (Root of project) >>>> TA_Lib-0.4.29-cp310-cp310-win_amd64.whl

6.  **Install Wheel**

        pip install TA_Lib-0.4.29-cp310-cp310-win_amd64.whl

7.  **Install zipline-reloaded**

        pip install zipline-reloaded

    ***Make sure you have activated venv using 3rd step as mention above.***
