
# Crypto Clustering 
![10-5-challenge-image.png](https://github.com/ahcano/cypto_clustering/assets/141194281/608ed161-4905-40c6-88b9-226956aa83b6)

# This Fintech project proposes a cryptocurrency investment strategy through the use of clustering methods and statistics.

## The following dataframe was created to store 41 cryptocurrency prices read from crypto_market_data csv file.

## The StandardScaler() module from scikit-learn was applied to normalize the data.

<img width="738" alt="" src="Screenshot 2023-10-29 224323.png">

## A summary of price change statistics through various time periods  
<img width="717" alt="Screenshot 2023-10-29 224419" src="Screenshot 2023-10-29 224419.png">

## Visual of the crypto coin variations based on the statistical data above
<img width="407" alt="Screenshot 2023-10-29 224430" src="Screenshot 2023-10-29 224430.png">

## Elbow method applied to find the optimal number of k clusters, which is 4 
<img width="352" alt="Screenshot 2023-10-29 224451" src="Screenshot 2023-10-29 224451.png">

## Scatter plot of predictions 
<img width="362" alt="Screenshot 2023-10-29 224503" src="Screenshot 2023-10-29 224503.png">

## Using PCA Data, the optimal value of k was predicted, matching as 4 again like with the original data
<img width="363" alt="Screenshot 2023-10-29 233713" src="Screenshot 2023-10-29 233713.png">


## Usage
The code is in Jupyter notebook crypto_investments.ipynb

## Contributors
Ana Cano - Author ana.cano@utoronto.ca

## License
Copyright (c) 2011-2017 GitHub Inc. Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions: The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software. THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
