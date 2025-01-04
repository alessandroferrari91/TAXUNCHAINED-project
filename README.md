# TAXUNCHAINED.AI-project

<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->


## Summary

Let's create a system that, given the transaction reports of different exchanges/platforms/crypto wallets, provides the poor Italian with the data to independently compile the tax report. The AI could be free, but also be requested a payment of 50 euros as it is currently necessary to pay accountants hundreds of euros. Milions Italians will buy it for sure.

## Background

Italy discourage the purchase of cryptocurrencies for less wealthy people, favoring the purchase of them only by those who have large capital to invest. This is because to be aligned with the new regulations, the average Italian would have to spend hundreds of euros every year to rely on dedicated professionals who carry out the accounts on the taxes to be paid for investments made in cryptocurrencies.

To give an example, a worker with a salary of 1500 euros per month who has invested 1000 euros and staked earning 100 euros in a year, will have to pay around 500 euros to an accountant to pay the state 26% of 100 euros (26 euros) , therefore becoming poorer than before and therefore unable to take advantage of the advantages that an investment in this sector can have. A politician with a salary of 30k euros a month, who invested 100k and earned 10k will have to pay the same amount of 500 euros to the accountant, becoming even richer. Under these conditions, the millions of Italians who have invested or who want to invest even a few hundred euros in cryptocurrencies are obliged to exit as soon as possible to avoid paying astronomical sums to accountants or switching to the illegal side by not declaring the crypto activities in the annual report for the payment of taxes (which the state seems to encourage in order to then be able to fine these people and collect more money from the economically weakest, rather than from the richest).

## How is it used?

It needs a user friendly interface because it will be used by ordinary people. Simple buttons for loading reports downloaded from various platforms, exchanges or the wallet's public address, so that the system has the necessary input data. An easy Download report button which must certainly contain the values ​​to be inserted in the relevant fields of the 730 and income tax return. An optional button for downloading the report showing how the calculations were carried out, separating the capital gains from sales, from those from staking, earn, aridrop etc..

## Data sources and AI methods

The input data comes from the user. The rules with which the AI ​​must formulate the report are written in laws and communicated by the revenue agency on public website and AI need to read it and understand mechanism for calculate tax due. If the AI ​​cannot "read" these documents, I can personally provide these rules which must then be implemented in the code.

## Challenges

The format of the input data is varied as each platform provides reports with different column headers. The AI ​​must understand the meaning and then assign the data to the correct categories. the FIFO method and not the LIFO method must then be used to determine capital gains. everything that is realized from staking, earn etc. must be interpreted as a capital gain of the entire amount with equivalent value in EUR at the time of receipt. The actual sale, if posthumous to that moment, can create a further capital gain or loss based on the value in euros at that moment. Yhe AI ​​must then calculate the average balance on the account by making weighted averages of the various positions by accessing their countervalues ​​at multiple points in time (data that it must automatically take from Coinbase or similar) of the calendar year to determine the IC tax.

If the AI could read laws and so on, it have to read them every year and adapt report of download based on changes made at laws.

## What next?

I need a programmer who can have an equal relationship with me in terms of future economic benefits. I have the project in my head, but I am a mechanical engineer and not a computer engineer. I therefore need someone who understands the potential audience of people who would benefit from this AI tool and is willing to invest their time for future gain.
