---
layout: post
title: F1 Prediction Project
subtitle: Seeing who would win with machine learning
cover-img: /assets/img/FormulaOne.jpg
thumbnail-img: /assets/img/Ferarri.jpg
share-img: /assets/img/path.jpg
tags: [Data Science, Machine Learning, API Deployment, Project]
---
***My first solo project*** **Github Repo**

# Table of Contents
1. [Introduction](#introduction)
2. [Grabbing Data & Data Analysis](#grabbing-data-&-data-analysis)
4. [Machine Learning](#machine-learning)
5. [Final Thoughts](#final-thoughts)

## Introduction
I finally finished Lambda School, got my data science & machine learning certification and landed my very first internship! The only thing left is to start my first project to explore subjects that I either brushed across when studying or never had the chance to explore. So, I present to everyone, My F1 Race Predictor. 

This is a project that takes the current driver lineup and will predict who will win any given race based on their race history. Formula One is a data driven sport, since the 80s teams have been grabbing data from their cars to continuously chase even the smallest gains to get the edge over their opponents. I will be grabbing data from the Ergast F1 API (http://ergast.com/mrd/) ***Don’t forget to actually link this*** to train my machine learning model. This review of this project will be a summarized version and the full write up will be found ***here***. 

##Grabbing Data & Analytics 
This process was possibly the most time consuming part of the project. Grabbing the data wasn’t really an issue, but finding useful data was the issue. Thankfully the API was straightforward with the method of grabbing data. Using HTML requests in Python I could grab the data in JSON format to easily convert into a data frame to analyze and train the model on. I built the data extraction into 4 individual functions with their own purpose to keep the code as clean as possible. 

As I’m writing this, there’s more data that I want to grab but isn’t found anywhere inside the current database of the API. Data like the weather at the time of the race, engine supplier to the constructor and tires used throughout the race are examples. That kind of data isn’t really for the machine learning data (other than the tires) but great to find patterns to engineer useful data for the machine learning model instead. With the current data, I was only able to engineer 2 new features that didn’t cause any data leaks. (data leaks were a concurrent theme with this project) 

As for the analysis, 

##Machine Learning
This is the fun part (and honestly my favorite part). Since this project was predicting the finishing position of any given racer that user inputs, 



