# financial_planning

## Install

* Open a new terminal window.

* All packages should be installed into the `alpacaenv` virtual environment.  To create the `alpacaenv` virtual environment, run the following command in your terminal, answering `y` when prompted:

  ```shell
  conda create -n alpacaenv python=3.7 anaconda
  ```

* After the `alpacaenv` environment installation is complete, activate it by typing the following command:

  ```shell
  conda activate alpacaenv
  ```

* Next, install the `python-dotenv` package by running the following command in your terminal:

  ```python
  pip install python-dotenv
  ```

* Now, initiate the `alpaca-trade-api` install by running the following command:

  ```shell
  pip install alpaca-trade-api
  ```

---

## Verify

* The `alpaca-trade-api` package will not run properly unless all needed dependencies and packages are properly installed.

* The above steps should have installed the following packages:

    * pandas

    * requests

    * python-dotenv

    * alpaca-trade-api

* Verify the installation of each package by running the command `conda list package_name` in your terminal, substi
