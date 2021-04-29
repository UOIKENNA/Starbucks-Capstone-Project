# Starbucks-Capstone-Project

The data simulates how people make purchasing decisions and how those decisions are influenced by promotional offers.

Each person in the simulation has some hidden traits that influence their purchasing patterns and are associated with their observable traits.

People produce various events, including receiving offers, opening offers, and making purchases.

As a simplification, there are no explicit products to track. Only the amounts of each transaction or offer are recorded. There are three types of offers that can be sent: buy-one-get-one (BOGO), discount, and informational.

BOGO offer: a user needs to spend a certain amount to get a reward equal to that threshold amount.
Discount: a user gains a reward equal to a fraction of the amount spent.
Informational offer: there is no reward, but neither is there a requisite amount that the user is expected to spend.
Offers can be delivered via multiple channels: Email, Mobile, Social, Web

# Table of Contents

1. [Installation](https://github.com/UOIKENNA/Starbucks-Capstone-Projectt#Installation)
2. [Project Motivation](https://github.com/UOIKENNA/Starbucks-Capstone-Project#Project)
3. [File Descriptions](https://github.com/UOIKENNA/Starbucks-Capstone-Project#File)
4. [Results](https://github.com/UOIKENNA/Starbucks-Capstone-Project#results)
5. [Licensing, Authors and Acknowledgements](https://github.com/UOIKENNA/Starbucks-Capstone-Project#licensing)

# Installation
The code should run without issues using Python 3.*. All the necessary libraries were imported using the Anaconda distribution.

# Project Motivation

GOAL: To use the data to

a) Identify which groups of people are most responsive to each type of offer.

b) How best to present each type of offer?

c) How many people across different categories actually completed the transaction in the offer window?

d) Which individual attributes contributed the most during the offer window?

# File Descriptions

portfolio.json

id (string) - offer id offer_type (string) - type of offer ie BOGO, discount, informational difficulty (int) - minimum required spend to complete an offer reward (int) - reward given for completing an offer duration (int) - time for offer to be open, in days channels (list of strings)

profile.json

age (int) - age of the customer became_member_on (int) - date when customer created an app account gender (str) - gender of the customer (note some entries contain 'O' for other rather than M or F) id (str) - customer id income (float) - customer's income

transcript.json

event (str) - record description (ie transaction, offer received, offer viewed, etc.) person (str) - customer id time (int) - time in hours since start of test. The data begins at time t=0 value - (dict of strings) - either an offer id or transaction amount depending on the record

Starbucks Capstone Project.ipynb

contains all the code and analysis performed in the project

# Results
The results of this analysis are available on a medium post [here](https://uikenna97.medium.com/udacity-capstone-project-starbucks-66a4bb1a186f)

# Licensing, Authors and Acknowledgements

Credit to Udacity for the lessons and tools provided. I also credit https://github.com/MANOJPATRA1991 for providing me with guidance to perform this project. The code in this repository can be viewed and inputs will be welcome!.
