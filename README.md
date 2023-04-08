# Data Science Learning

The repository contains all the notes, exercises and sources that I used to learn Data Science, more specifically the manipulation, cleaning, and presentation of data

## Content Table

1. [Ipython](./01-ipython/README.md)
2. numpy
3. Data manipulation with Pandas

## Installation and Setup

To use and run the scripts and notebooks found in this project, we recommend using **miniconda** to manage and handle the python environments, After install minicoda execute the following commands

1. configure the channel where you going to fetch the packages in first instance

   ```shell
    (base) $ conda config --add channels conda-forge
    (base) $ conda config --set channel_priority strict
   ```

2. create a new enviroment

    ```shell
      (base) $ conda create -y -n pydata-book python=3.10
    ```

3. Activate the new environment

    ```shell
      (base) $ conda activate pydata-book
      (pydata-book) $
    ```

## Bibliography

- Python for Data Analysis 3rd Edition
