{\rtf1\ansi\ansicpg1252\cocoartf2709
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs24 \cf0 # Machine Learning to Analyze Paycheck Protection Program (PPP) Data\
Michael Lewis, Ethan Wong, Peter Magee, Margaret Willis\
\
## Introduction\
Throughout the COVID-19 pandemic, an estimated $525 Billion USD was disbursed as part of the federal government\'92s Paycheck Protection Program (PPP) House (2022). These loans, while crucial for protecting American industry and the workforce, have been met with allegations of fraud and controversy. Additionally, from the program's onset machine learning (ML) was used to help automate the approval and disbursement of loans, mirroring a larger nation-wide trend of ML in the financial services industry. While the vast majority of loans have been forgiven, we wanted to understand how various ML methods perform using data the lenders themselves had access to. \
\
## Why? \
We focus our analysis on two variables: `Amount Forgiven` and `Business Type`. Understanding whether we can accurately predict `Amount Forgiven` is important as future lenders may use this data to predict whether businesses are solvent and could repay future loans. To examine this we use various regression methods. Second, we are interested in seeing whether this open-source data on a company's characteristics (e.g., number of employees, minority-owned, utilities, rent, etc.) can be used to classify businesses according to their legal business type (i.e., non-profit, for-profit, etc.). This is an important area of study given that business type often determines which loans a company may qualify for as well as determine things like a loan's interest rate. Additionally, this data could be used to make generalizations about whether certain types of businesses in certain sectors are more likely to repay their loans. Thus, understanding how well ML methods perform on this data more broadly is an important area of research.\
\
## Summary \
Our final research can be found in this GitHub repo. Our complete report containing our code and analysis, as well as our final dataset can be located in the `Final_Analysis` folder. Preliminary research, code, and EDA can be found in our `Research` folder. Our poster presentation can be found in `Presentation`. Finally, our division of labor breakdown is located in `Roles_Responsibilities`. }