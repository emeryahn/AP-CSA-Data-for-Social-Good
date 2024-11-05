# Unit 3 - Data for Social Good Project 

## Introduction 

Software engineers develop programs to work with data and provide information to a user. Each user has different needs based on the information they are looking for from data. Your goal is to create a data analysis program for your user that stores and analyzes data to provide the information they need. 

## Requirements 

Use your knowledge of object-oriented programming, one-dimensional (1D) arrays, and algorithms to create your data analysis program: 
- **Write a class** – Write a class to represent your user or business and store and analyze their data with no-argument and parameterized constructors. 
- **Create at least two 1D arrays** – Create at least two 1D arrays to store the data that your user needs information about. 
- **Write a method** – Write a method that finds or manipulates the elements in a 1D array to provide the information your user needs. 
- **Implement a toString() method** – Write a toString() method that returns general information about the data (for example, number of values in the dataset). 
- **Document your code** – Use comments to explain the purpose of the methods and code segments and note any preconditions and postconditions. 

## User Story 

Include your User Story you analyzed for your project here. Your User Story should have the following format: 

As a DJ,
I want to know what the most viral current songs are
so that I can play them at major events and get the crowd hyped and entertained.

## Dataset 

Dataset: https://docs.google.com/spreadsheets/d/1Bjbfyuz2D5UBWrMT2D_0bOst5gY9KHu1zc_ieWNELWU/edit?usp=sharing
 - Position (int) - rank of the song
 - Track Name (String) - name of the song
 - Artist (String) - person who released the song
 - Popularity (int) - average rating from 1-100


## UML Diagram 

[UML Diagram for my project](https://github.dev/emeryahn/AP-CSA-Data-for-Social-Good) 

## Description 

This music app was designed to inform users of the most popular songs and artists out there right now. Our app returned the name of the artist with the most viral hits on the top 50 Spotify charts. It then asks the user if they have an artist that they would like to see the number of times they appear on the chart. The user has to input a name and then the app will traverse through the 1D array and determine how many times the inputted user's name appears.