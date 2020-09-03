# Reproducible-Research-Course-Project-1
The goal of this assignment is to analyze a set of data and document it so that it is reproducible by others. 
After all, if others can't replicate it, it is not science. The components of this repo are as follows:
- A R markdown file of the data analysis. (analysis_doc.rmd)
- The data itself. (steps_data.csv)
- A html file corresponding to the rmd file. (analysis_doc.html)
- Plots in the document.

# Introduction
There is a "quantified self" movement comprised of people who take measurements involving themselves methodically to improve personal health and find patterns in their behaviour. [I myself inadvertently fall into this category due to my many n = 1 experiements with intermittent fasting, cold exposure, extreme endurance, caloric restriction and various exercise and dietary regimens. I was doing data science without even knowing it. Over the years, through all the noise, I have found real gems that have revolutionized my well being.]

Tools such as Fitbit, Nike Fuelband, Jawbone Up has allowed for the collection of personal movement data. Using this data requires statistical methods and software to process and interpret the data. In this experiment, we will be studying data related to the number of steps taken per day averaged over five minute intervals over the course of two months (October + November of 2012).

Variables of the activity monitoring data are given by:

- steps: number of steps taken in a 5-minute interval (missing values are denoted NA)
- date: date on which the measurement was taken in yyyy-mm-dd format.
- interval: identifier for the five minute intervals.
- The data is stored in a comma separated CSV file with 17568 rows.
