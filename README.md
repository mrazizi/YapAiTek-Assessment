# YapAiTek Assessment

This is the assessment of [YapAiTek](http://www.yapaitek.com/) company as a part of the process of selecting candidates for their *Junior Data Scientist* Position.

This is a time-series forcasting problem. The goal is to predict air quality of Singapore (Pollutant Standards Index or PSI) using an existing dataset of PSI levels between year 2016 to 2019.

## Getting Started

You can copy the dataset to your Google Drive and open the jupyter notebook on Google Colab or alternatively, you can run the jupyter notebook locally. In each case, make sure to change the ``dataset_path`` variable to the correct path of dataset.

### Prerequisites

You need the ``python 3`` and the following packages to run the code.

```
tensorflow               2.2.0
numpy                    1.18.5
pandas                   1.0.5
matplotlib               3.2.2
```


## About the Task


### Dataset
![dataset](img/dataset.png?raw=true "Title")


### Model
We used 4 lags of data as the input to a LSTM model.



### Results
The following image is the plot of prediction vs true PSI levels for out test data:

![dataset](img/result.png?raw=true "Title")





## Contributing

Feel free to make issues or create pull requests :)


## Author

* **Mohammad-Reza Azizi** - [mrazizi](https://github.com/mrazizi)
