# About

This is a set of notebooks with analysis of RNG event originating from Global Consciousness Project (Princenton Noosphere experiment). The article explaining this analysis is posted on [Medium](https://medium.com/@oleksandrsavsunenko/experimental-data-to-support-simulation-hypothesis-7b1148de7854)

## How to get raw data

wget -N -r -nH --cut-dirs=1 --limit-rate=125k https://global-mind.org/data/eggsummary/wget/wget2014.html

## Results

The data for chart presented in the article is in the file results_w1_2014.pickle and code to generate the chart is in the file 2-sliding window.

After getting a raw data, start with 0_form_data notebook to reproduce. 

STD for the egg should be calculated using experimental data, not mathematically derived (you can see both attempts in code) - this is due to XOR algorithm used in the RNGs - it tradesoff bias of 0.5 into bias of STD - read the discussion of GCP website.


## Warnings
1. This is quite RAM hungry. If you are OOMing - make sure there is enought swap and reduce number of parallel workers. Some parts of data analysis take hours. This is Python ;-)
2. Sorry for code quality, this is side project ;-)

## Reaching out
I would love to discuss this. Reach me out on twitter - @crazyleg11