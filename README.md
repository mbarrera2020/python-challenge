# python-challenge
Author: Maria Barrera
Date: 01/10/2021
Description:  Python scripts for analyzing financial & election records.

## Background
There are 2 python challenges, Pybank and PyPoll.

## PyBank
The PyBank Python script processes a csv file and produces a financial analysis text file.
 * uses calculations, average function & data formatting

Input: 
CSV file

Process:
The PyBank Python script analyzes the financial data and does the followwing calculations:
  * total number of months included in the dataset
  * net total amount of "Profit/Losses" over the entire period
  * changes in "Profit/Losses" over the entire period and get the average of those changes
  * greatest increase in profits (date and amount) over the entire period
  * greatest decrease in losses (date and amount) over the entire period
  * other:
    - display the results on the terminal
    - export a text file with the results and store in a specific folder


## PyPoll
The PyPoll Python script processes a csv file and produces an election analysis text file.
  * uses lists, tuples, dictionary, zip, sort function, data formatting

Input: 
CSV file

Process:
The PyPoll Python script analyzes the election (votes) data and does the followwing:
  * total number of votes cast
  * capture a complete list of candidates who received votes
  * calculate the percentage of votes each candidate won
  * calculate the total number of votes each candidate won
  * identify the winner of the election based on popular vote
  other:
    - display the results on the terminal
    - export a text file with the results and store in a specific folder
