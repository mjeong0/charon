Date    : May 24 2019
Author  : Q.R. Liu

Here is how to start running these scripts.
Just do 

```
./run.sh channel mass Nevent seed
```
--channel
channel is the annihilation channel you want to generate:
Now available ones are:
{'dd':1,'uu':2,'ss':3,'cc':4,'bb':5,'tt':6,'gg':7,'WW':8,'ZZ':9,'mumu':10,'tautau':11,'nuenue':12,'numunumu':13,'nutaunutau':14}
numbers correpond to the MC particle numbering scheme

--mass
DM mass in GeV.

--Nevent
number of events you want to generate.

--seed
seed for MC generation 