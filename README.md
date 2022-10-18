# My Personal Linkedin Data Analysis 📚🔎
![version](https://img.shields.io/badge/version-0.0.1-blue)
![python](https://img.shields.io/badge/python-3.8.7-brightgreen)

### Feature ###

This repository features the following:
> - A personal project developed with the intention of doing a more elaborate data analysis of my Linkedin network.

### Local installation ###

To execute the project, the following steps will be necessary:
> - Install [python 3](https://www.python.org/) and [git](https://git-scm.com/downloads);
> - On your local server, run a `git clone` command;
> - Create a virtual enviroment running  `C: actualdir\ $ python -m venv venv`, and acess it by `$ .\venv\Scripts\activate.bat`
> - Download the requirements.txt file with the project dependencies by typing `pip install -r requirements.txt`.
> - Log in daatpane with yout own personal account token. You can do it on terminal like: `$ datapane login --server=https://datapane.com/ --token=<yourtoken>`
> - To connect your notebook with the virtual enviroment you have just created and seted up, run finally `$ ipython kernel install --user --name=venv` and acess it through your notebook.

### How to get acess to your own linkedin dataset? 

The easiest and fastest way to obtain a copy of your LinkedIn data is to initiate a data download from your **Settings & Privacy** page:

1. Click the **Me** icon at the top of your LinkedIn homepage.
2. Select **Settings & Privacy** from the dropdown.
3. Click the **Data Privacy** on the left rail.
4. Under the How LinkedIn uses your data section, click **Get a copy of your data**.
5. Select the data that you’re looking for and **Request archive**.

You can select specific categories of data or a larger download! If you select a specific type of data, we’ll email you within minutes. If you select the larger download, you’ll receive an email within 24 hours. Use the link provided in the email to download the information you requested. The data will be available for download for 72 hours. For more details, acess the following [Link](https://www.linkedin.com/help/linkedin/answer/50191/downloading-your-account-data?lang=en)


### Project Technologies ###

* Pandas
* Pandas_profiling
* Datapane
* Plotly
* WordCloud
