# Financial Analysis using APIs

Here we use two APIs ```Alternative.me API``` and ```Alpaca API```. This information is used to calculate the value of the crypto and stock/bond holdings, comparing it to a desired savings benchmark and lastly creating two MonteCarlo simulations to analyze the potential performance of our stock/bond portfolio over a range of ten and thirty years.

---

## Technologies

The following technologies were used to build and deploy this application:

* Python - Version 3.9.7
* Anaconda (Which includes Jupyter Lab and Pandas)
* os Library
* requests Library
* json Library
* dot_env Library
* matplotlib Library
* Alpaca Trade API
* MCForecastTools

---

## Installation and Usage Guide

### 1. Install Python 3.9.7

For installing Python 3.9.7 you can find the Installation Files for both Windows/Mac OS in the following link
 * [Anaconda Installation Files](https://www.anaconda.com/products/individual "Anaconda Installation Files")

If you require assistance installing it, you can follow the following videos for guidance
* [Youtube Video Python Installation Guide - Windows](https://www.youtube.com/watch?v=uSVl7gRXP80 "Python Installation Video - Windows") 
* [Youtube Video Python Installation Guide - Mac](https://www.youtube.com/watch?v=r6bBaj797t8 "Python Installation Video - Mac") 
 
### 2. Install Anaconda

For installing Python 3.9.7 you can find the Installation Files for both Windows/Mac OS in the following link
 * [Python Installation Guide](https://www.python.org/downloads/release/python-397/ "Python Installation Guide")

If you require assistance installing it, you can follow the following videos for guidance
* [Youtube Video Anaconda Installation Guide - Windows](https://www.youtube.com/watch?v=g6ln1dAt-RI "Anaconda Installation Video - Windows") 
* [Youtube Video Anaconda Installation Guide - Mac](https://www.youtube.com/watch?v=oWVTO_69U4c "Anaconda Installation Video - Mac")

### 3. Install necessary Libraries and Dependencies

For installing ```requests``` please follow the following link to receive guidance 
* [Requests Library Installation](https://docs.python-requests.org/en/latest/user/install/ "Requests Library Installation") 

For installing ```json``` please follow the following link to receive guidance 
* [JSON Library Installation](https://www.educba.com/json-in-python/ "JSON Library Installation") 

### 4. Creating and Saving API Keys

In this project we are using two APIs (Alternative.me and Alpaca), the first one does not require us to create API Keys, however the latter requires us to create API Keys and Secret Keys. This will allow us to access the Alpaca servers to access their data.

For getting an Alpaca API key and secret key, please follow the following guide
* [Alpaca API Guide](https://alpaca.markets/learn/connect-to-alpaca-api/ "Alpaca API Guide") 

In addition if you want an added level of security (that is protecting your keys when sharing your code) please follow the following guide
* [Creating Environment Files](https://able.bio/rhett/how-to-set-and-get-environment-variables-in-python--274rgt5 "Creating Environment Files") 


### 3. Downloading the Financial Analysis using APIs

Navigate to your desired location where you would like to save the documents for this application. You can do this by using the ```cd``` command followed by a space and the file path inside quotations ```" file path "```. In my example I have gone to Desktop.

![image](https://user-images.githubusercontent.com/94983278/149385012-181d1769-0af6-487e-8e04-823a28f2c3ed.png)

Clone this project's repository from GitHub using the following command 

```git clone https://github.com/epocaterrasus/Financial-Planning-using-APIs.git```

### 4. Opening the file on Jupyter Notebook

Being in the folder created when you downloaded the repository type ```jupyter lab```, this should open a window in your predetermined browser with Jupyter Lab. In the left corner you can see the files inside the repository, open the ```financial_planning_tools.ipynb``` which contains all steps and notes followed to analyze this dataset pair.

---

## Overview of the Project

We used the two apis above to gain acccess to data on stocks and cryptocurrencies and then use that data to evaluate performance.
---

## Contributors

Maxwell Snyder @mholts1020@gmail.com

---

## License

MIT License

Copyright (c) 2022 MAxwellSnyder

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.