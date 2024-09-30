# MF915__exam_system_biology_course

## Task 1: Reviewing the data 
### Question 1.1: how many predictions are there in the raw data file? 
#### Answer:- There are <35231> predictions in the miRAW_target_data
### Question 1.2: How many unique genes are there in the list? 
#### Answer:- Number of unique genes: 40
### Question 1.3: How many unique miRNAs are there in the list?
#### Answer:- Number of unique miRNA: 1627

## Task 2: Filtering the data 
### Question 2: How many predictions are left after filtering?
#### Answer:- Number of predictions left after filtering is 0 because there are no predictions that have prediction probability thats is greater than 0.999 and also energy that is greater than 10

## Task 3: Targeting types 
### Question 3.1: What percentage of the reported targets are non-canonical? 
#### Answer:- Percentage of ' noncanonical' is 50.00%
### Question 3.2: Is this consistent with what is reported in the literature? 
#### Answer:- 

## Task 4: 3’UTR Lengths 
### Question 4.1: What are the lengths of all the 3’UTRs? 
#### Answer:- 

## Task 5: miRNA binding along the 3’UTR 
### Question 5.1: Plot the distribution of locations of the start positions for all 3’UTRs.
#### Answer:![Distribution of Start Positions for 3' UTRs](https://github.com/user-attachments/assets/bef93c8d-cb88-4181-ab01-6e76b3e624b7)



### Question 5.2: Are there any biases in the location of where the miRNAs bind on the 3’UTR? 
#### Answer:- From the histogram above, the 3' UTR start positions we can observe that there is a clear bias in where miRNAs bind to the 3' UTR. we can say that because there is Higher frequency near the start which means, There is a significant concentration of miRNA binding events near the beginning of the 3' UTR region. And As you move farther from the start of the 3' UTR, the number of miRNA binding events gradually decreases.This suggests that miRNA binding sites tend to concentrate toward the beginning of the 3' UTR in our dataset
### Question 5.3: Are there any differences between where the canonical and non-canonical targeting events bind? 
#### Answer:- yes there is a  difference. In Canonical targeting event the seed region of the miRNA binds directly and perfectly to a complementary sequence in the mRNA (typically in the 3' UTR). But in Non-Canonical the interaction between the miRNA and mRNA may occur outside of the seed region or involve a more flexible, less stable interaction.

### Question 5.4: Display these two types of binding on the plot?,
#### Answer:- 

## Task 6: multiple miRNA binding events 
### Question 6.1: Generate another histogram to show how many times one miRNA binds to the same 3’UTR for all miRNA and all 3’UTRs.  
#### Answer:- ![Distribution of miRNA Binding Events to 3' UTRs](https://github.com/user-attachments/assets/7179277a-1eae-4b81-b833-aab6b4a76476)

## Task 7: generate a miRNA--3’UTR targeting network 
### Question 7.1: Similar to the plot above, generate a Connectivity Plot. 
#### Answer:-
### Question 7.2: Which miRNAs target the most 3’UTRs? 
#### Answer:-
### Question 7.3: What is the highest number of 3’UTRs targeted by a single miRNA?
#### Answer:-
### Question 7.4: What are the roles in disease of the three miRNAs that have the most 3’UTR targets?
#### Answer:-



