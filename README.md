# WDM-Ex.NO-2B-ASSOCIATION-RULES-FOR-BANKING-DATASET
### Aim:
To Find the Association Rules for Banking dataset.
### Description:
In data mining, association rule learning is a popular and well researched method for discovering interesting relations between variables in large databases. It can be described as analyzing and presenting strong rules discovered in databases using different measures of interestingness. In market basket analysis association rules are used and they are also employed in many application areas including Web usage mining, intrusion detection and bioinformatics.
## Creation of Banking Table:
### Procedure:
1)	Open Start  Programs  Accessories  Notepad
2)	Type the following training data set with the help of Notepad for Banking Table.

```
@relation bank
@attribute cust {male,female}
@attribute accno
{0101,0102,0103,0104,0105,0106,0107,0108,0109,0110,0111,0112,0113,0114,0115}
@attribute bankname {sbi,hdfc,sbh,ab,rbi}
@attribute location {hyd,jmd,antp,pdtr,kdp}
@attribute deposit {yes,no}
@data
male,0101,sbi,hyd,yes
female,0102,hdfc,jmd,no
male,0103,sbh,antp,yes
male,0104,ab,pdtr,yes
female,0105,sbi,jmd,no
male,0106,ab,hyd,yes
female,0107,rbi,jmd,yes
female,0108,hdfc,kdp,no
male,0109,sbh,kdp,yes
male,0110,ab,jmd,no
female,0111,rbi,kdp,yes
male,0112,sbi,jmd,yes
female,0113,rbi,antp,no
male,0114,hdfc,pdtr,yes
female,0115,sbh,pdtr,no
```

4)	After that the file is saved with .arff file format.
5)	Minimize the arff file and then open Start  Programs  weka-3-4.
6)	Click on weka-3-4, then Weka dialog box is displayed on the screen.
7)	In that dialog box there are four modes, click on explorer.
8)	Explorer shows many options. In that click on ‘open file’ and select the arff file
9)	Click on edit button which shows banking table on weka.
 
Training Data Set  Banking Table
<img width="730" height="784" alt="image" src="https://github.com/user-attachments/assets/b901d50b-211c-4a08-9cca-fa8d732e48b8" />


### Procedure for Association Rules:
1)	Open Start  Programs  Weka-3-4  Weka-3-4
2)	Open explorer.
3)	Click on open file and select bank.arff
4)	Select Associate option on the top of the Menu bar.
5)	Select Choose button and then click on Apriori Algorithm.
6)	Click on Start button and output will be displayed on the right side of the window.
 <img width="1086" height="899" alt="image" src="https://github.com/user-attachments/assets/6f6ad74e-bee1-4825-877c-9c413e30913a" />

 
### Output:
<img width="924" height="560" alt="image" src="https://github.com/user-attachments/assets/f02f6e67-2a79-4c79-b844-d3b5c75d0069" />

 
 

<img width="942" height="561" alt="image" src="https://github.com/user-attachments/assets/3d89ab29-5e6e-4505-9523-44284d7f4639" />































### Result:
Thus, this program has been successfully executed.
