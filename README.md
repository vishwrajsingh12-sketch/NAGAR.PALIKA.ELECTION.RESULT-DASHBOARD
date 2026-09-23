# 🗳️ Nagar Palika Election Analytics Dashboard

# Project Overview

The Nagar Palika Election Analytics Dashboard is an interactive data analytics project developed using Microsoft Power BI to analyze voter data and election results of Badi Sadri Nagar Palika, Chittorgarh, Rajasthan.

The project transforms structured voter and election-result data into an interactive and visually appealing dashboard. It provides ward-wise analysis of voters, gender distribution, reservation categories,  candidates, parties, votes, and election results.

The dashboard is designed to make election-related data easier to understand through interactive charts, cards, tables, filters, and visual summaries.

#  Objectives

- Analyze voter data across all wards.
- Compare male and female voter distribution.
- Analyze ward-wise voter counts.
- Display ward reservation information.
- Analyze candidate-wise and party-wise votes.
- Identify ward-wise winning candidates.
- Analyze party-wise election results.
- Provide interactive filtering using wards and result status.
- Present election data in a clean and professional dashboard.

#  Dashboard Features

#  Voter Analysis
- Total number of wards
- Total voters
- Male voters
- Female voters
- Ward-wise voter distribution
- Gender-wise voter distribution
- Ward reservation analysis
- Detailed voter information table

#  Election Result Analysis
- Total votes
- Candidate-wise votes
- Party-wise total votes
- Party-wise winners
- Ward-wise winning votes
- Ward-wise winners
- Complete election result table
- Won/Loss filtering
- Ward-wise party vote analysis

# Technologies Used

- **Microsoft Power BI**
- **Microsoft Excel**
- **Power Query**
- **DAX**
- Data Visualization
- Data Cleaning & Transformation

# Data Used

The project uses structured Excel datasets containing:

# Voter Data
- Ward
- Male Voters
- Female Voters
- Reservation
- Total Voters

# Election Result Data
- Candidate Name
- Party
- Result
- Votes
- Ward

# Data Model

The dashboard uses a relationship between the voter and election-result datasets through the common **Ward** field.

//text

Voter_Data
    │
    │ Ward
    ▼
Result_Data
