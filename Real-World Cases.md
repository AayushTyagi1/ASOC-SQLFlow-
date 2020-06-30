# Real World Cases

##  Medical Problem

Problem Statement
A lot has been said during the past several years about how precision medicine and, more concretely, how genetic testing is going to disrupt the way diseases like cancer are treated. But this is only partially happening due to the huge amount of manual work still required. Once sequenced, a cancer tumor can have thousands of genetic mutations. But the challenge is distinguishing the mutations that contribute to tumor growth (drivers) from the neutral mutations (passengers). Currently this interpretation of genetic mutations is being done manually. This is a very time-consuming task where a clinical pathologist has to manually review and classify every single genetic mutation based on evidence from text-based clinical literature. We need to develop a Machine Learning algorithm that, using this knowledge base as a baseline, automatically classifies genetic variations.This problem  was launched by Memorial Sloan Kettering Cancer Center (MSKCC), accepted by NIPS 2017 Competition Track, because we need your help to take personalized medicine to its full potential.

## Healthcare and Life Science
Problem Statement
Air pollution is a severe issue in today's industrial society because it is detrimental to the ecosystem, its species as well as personal health. It is therefore imperative for world governments and health organizations to take measures to reduce pollutants, but to do so, effective data and its analysis is required. This problem aims to analyze Air Quality of different states using Air Quality Dataset of any courntry.

## Business and Data Understanding

Business and Data Understanding
Teclov has two minor constraints for investments:
1. It wants to invest between 5 to 15 million USD per round of investment
2. It wants to invest only in English-speaking countries because of the ease of
communication with the companies it would invest in
! For your analysis, consider a country to be English speaking only if English is
one of the official languages in that country
! You may use this list: Click here for a list of countries where English is an
official language.

These conditions will give you sufficient information for your initial analysis. Before
getting to specific questions, let’s understand the problem and the data first.

1. What is the strategy?
Teclov wants to invest where most other investors are investing. This pattern is often observed among early stage startup investors.
 
2. Where did we get the data from?
We have taken real investment data from crunchbase.com, so the insights you get may be incredibly useful. For this group project, we have divided the data into the following files:

You have to use three main data tables for the entire analysis

3. What is Teclov’ business objective?
The business objectives and goals of data analysis are pretty straightforward.
1. Business objective: The objective is to identify the best sectors, countries, and a suitable investment type for making investments. The overall strategy is to invest where others are investing, implying that the 'best' sectors and
countries are the ones 'where most investors are investing'.
2. Goals of data analysis: Your goals are divided into three sub-goals:
- Investment type analysis: Comparing the typical investment amounts in the venture, seed, angel, private equity etc. so that Teclov can choose the type that is best suited for their strategy.
- Country analysis: Identifying the countries which have been the most heavily invested in the past. These will be Teclov’ favourites as well.
- Sector analysis: Understanding the distribution of investments across the eight main sectors. (Note that we are interested in the eight 'main sectors' provided in the mapping file. The two files — companies and rounds2 — have numerous sub-sector names; hence, you will need to map each sub-sector to its main sector.)
1. Company details
companies: A table with basic data of companies
3. Sector Classification:
mapping.csv: This file maps the numerous category names in the companies table
(such 3D printing, aerospace, agriculture, etc.) to eight broad sector names. The
purpose is to simplify the analysis into eight sector buckets, rather than trying to
analyse hundreds of them. 

## Load Analysis
You work for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
• If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
• If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company
The data given contains the information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.
In this case study, you will use EDA to understand how consumer attributes and loan attributes influence the tendency of default.
When a person applies for a loan, there are two types of decisions that could be taken by the company:
1. Loan accepted: If the company approves the loan, there are 3possible scenarios described below:
◦ Fully paid: Applicant has fully paid the loan (the principal and the interest rate)
◦ Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These
candidates are not labelled as 'defaulted'.
◦ Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan.
2. Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)


## Retail
A Chinese automobile company Tec_chinese aspires to enter the US market by setting up their manufacturing unit there and producing cars locally to give competition to their US and European counterparts.They have contracted an automobile consulting company to understand the factors on which the pricing of cars depends. Specifically, they want to understand the factors affecting the pricing of cars in the American market, since those may be very different from the Chinese market. Essentially, the
company wants to know:
• Which variables are significant in predicting the price of a car
• How well those variables describe the price of a car
Based on various market surveys, the consulting firm has gathered a large dataset of different types of cars across the American market.

## Document Similarity
Quora is a place to gain and share knowledge—about anything. It’s a platform to ask questions and connect with people who contribute unique insights and quality answers. This empowers people to learn from each other and to better understand the world.

Over 100 million people visit Quora every month, so it's no surprise that many people ask similarly worded questions. Multiple questions with the same intent can cause seekers to spend more time finding the best answer to their question, and make writers feel they need to answer multiple versions of the same question. Quora values canonical questions because they provide a better experience to active seekers and writers, and offer more value to both of these groups in the long term.
> Credits: Kaggle

__ Problem Statement __
Identify which questions asked on Quora are duplicates of questions that have already been asked. This could be useful to instantly provide answers to questions that have already been answered. We are tasked with predicting whether a pair of questions are duplicates or not.

## Tag Analysis
Stack Overflow is something which every programmer use one way or another. Each month, over 50 million developers come to Stack Overflow to learn, share their knowledge, and build their careers. It features questions and answers on a wide range of topics in computer programming. The website serves as a platform for users to ask and answer questions, and, through membership and active participation, to vote questions and answers up or down and edit questions and answers in a fashion similar to a wiki or Digg. As of April 2014 Stack Overflow has over 4,000,000 registered users, and it exceeded 10,000,000 questions in late August 2015. Based on the type of tags assigned to questions, the top eight most discussed topics on the site are: Java, JavaScript, C#, PHP, Android, jQuery, Python and HTML.

Problem Statemtent
Suggest the tags based on the content that was there in the question posted on Stackoverflow.
