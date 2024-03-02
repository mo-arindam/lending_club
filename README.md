# LendingClub Case Study
> This is a case study to solve real world business problem using EDA. Apart from applying EDA techniques this case study will also help to develop basic understanding of of risk analysis in banking and financial domain and how data is used to minimise the risk of losing money while lending to customers.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A consumer finance company grants loans to urban customers, facing risks of both denying loans to good applicants and approving loans to defaulters.
- Given data on past applicants, the company aims to identify patterns predicting defaults for future decisions
- These decisions include approving loans with various outcomes (fully paid, ongoing, defaulted) or rejecting them entirely.
- Identifying these "risky" applicants beforehand can significantly reduce financial losses.
- Understanding these "driver variables" will help the company assess risk and manage its loan portfolio.
- The raw data is given as a CSV files which contains 39717 rows and 111 columns. It also accompany data dictionary in xlsx format


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Regarding the distribution of loan_status, which is key to understanding the likelihood of default:
    - 82.96% of loans have been fully paid off.
    - 14.17% of loans have been charged off, indicating a default.
    - 2.87% of loans are currently being paid off.
- Grade: As the grades progress from A to G, there is a noticeable trend where the default count increases
- Interest Rate: There is a positive correlation between interest rate and loan default
- Term: The charge-off rate for the short term appears to be lower than for the long term


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python  - version 3.10.9
- Pandas  - version 1.5.3
- Numpy   - version 1.23.5
- Seaborn - version 0.12.2
- Matplotlib -version 3.7.0
- conda - version 23.3.1 

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project is based on Lending Club Case Study by upGrad



## Contact
Created by [@mo-arindam] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->