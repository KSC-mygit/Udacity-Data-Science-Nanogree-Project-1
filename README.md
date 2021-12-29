# Udacity Data Scientist Nanodegree - Project 1

This project is completed as part of the curriculum for the Udacity Data Scientist Nanodegree Program. In this project I will answer three questions using data on a population of mutual funds in the United States.

## Libraries used
* Numpy
* Pandas
* Matplotlib
* Seaborn
* Sklearn
* re 

## Files Used
I used the `MutualFunds.csv` which can be downloaded from Kaggle at the following link: https://www.kaggle.com/stefanoleone992/mutual-funds-and-etfs?select=MutualFunds.csv

I downloaded the data source from Kaggle that had been last updated on December 12, 2021. A copy of this file is included with this project. The file was too large to be uploaded on GitHub without being compressed hence the file is provided in zipped format. Please unzip the file first before running the code.

Please note that downloading the data directly from Kaggle using the link provided above may generate a more recent version of the dataset which may not be fully consistent with the results obtained at the time of this project. To ensure consistency with the results in this analysis please use the accompanying copy of the `MutualFunds.csv` file. 

## Questions addressed
1. Is the fund expense ratio an important factor for selecting funds that will generate the best performance? The results showed that when considering the population as a whole the fund expense ratio may not be a significant factor; however, when considered at the fund category level the relationship was stronger, suggesting that this may be a useful factor when selecting a category to focus on.
2. What are the most popular top holdings of the best performing mutual funds? The final result was a list of the following as the top 10 holdings across the population of mutual funds. Taiwan Semiconductor Manufacturing Co Ltd stood out for me personally as a surprise appearance on this list.
      * Microsoft Corp                               164
      * Amazon.com Inc                               129
      * Apple Inc                                    119
      * Alphabet Inc Class C                          94
      * Facebook Inc A                                67
      * Taiwan Semiconductor Manufacturing Co Ltd     54
      * Alphabet Inc A                                54
      * JPMorgan Chase & Co                           52
      * Tencent Holdings Ltd                          52
      * Visa Inc Class A                              52
3. Can the (i) Morningstar return rating, (ii) 5 year average fund performance, (iii) investment style and (iv) size type, be used to predict current performance? The model generated an r-squared score of 0.28 on test data which indicated the factors identified had some value in explaining the variation in current performance, however, it was not considered high enough to deem the model very useful for use in prediction. In was concluded that further work would need to be done to improve the model

## Further Reference
For more information on my analysis please read the accompanying blogpost on Medium which can be found at the following link: https://medium.com/@kennedychinyam2/three-insights-about-investing-in-mutual-funds-in-the-united-states-cf5c92b74fa0 

## Acknowledgements
Special thanks to Stefao Leone for making this dataset available on Kaggle. The original data was scrapped from Yahoo Finance (https://finance.yahoo.com/). 

## License
<a href="https://creativecommons.org/publicdomain/zero/1.0/">CC0: Public Domain</a>
