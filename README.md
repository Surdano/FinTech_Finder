# FinTech_Finder
![ScreenShot of ethereum](https://static.seekingalpha.com/cdn/s3/uploads/getty_images/1329407939/medium_image_1329407939.jpg)

A Streamlit application that allows the user to choose a FinTech professional that they are interested in hiring, choose the number of hours they want the hired professional to work and then send Ethereum as payment. The applcation provides a validated transaction hash to verify that the amount of Ethereum was sent successfully.

---
## Technologies:

This application was written in Python 3.7 and utilizes the following:

* [streamlit](https://streamlit.io/)

* [web3](https://web3py.readthedocs.io/en/stable/)

* [os](https://docs.python.org/3/library/os.html)

* [dataclasses](https://docs.python.org/3/library/dataclasses.html)

* [typing](https://docs.python.org/3/library/typing.html)

* [request](https://pypi.org/project/requests/)

* [dotenv](https://pypi.org/project/python-dotenv/)

* [bip44](https://pypi.org/project/bip44/)
---
## Installation Guide:

To run this web application the user must install Streamlit using the following code in the terminal:

```pip install streamlit```

The user will also need to utilize Ganache. Follow the instructions on the [Ganache](https://trufflesuite.com/ganache/) webpage to download and install this tool on your local machine.

---
## Usage:

To utilize this web application, clone this repository to your local computer. Launch the Ganache program and create a `.env` file which holds your MNEMONIC phrase that is provided. Once you are ready to launch the program, make sure that the RPC Server in Ganache matches the same HTTP Provider in the `fintech_finder.py` code. Finally, navigate to the working folder in your terminal and run the following command:
 
```streamlit run fintech_finder.py```

---
## Visualizations
![Screenshot of app](https://user-images.githubusercontent.com/89755088/153807662-5160430d-2c6e-4120-be4c-9f3f9f5e61dc.png)

![Screenshot of app](https://user-images.githubusercontent.com/89755088/153808019-f1c92a6d-f86e-40e7-b207-6caff6a7bb86.png)

---
## Contributors:

Thomas Leahy, thomasleahy6@gmail.com

In conjunction with Trilogy Education Services, a 2U, Inc. brand.

---
## Licence:

MIT

© 2022 Thomas Leahy
