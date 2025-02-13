<a href="https://www.linkedin.com/in/kshitija-chilbule-b98515309/" target="_blank">
  <img src="https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin" alt="LinkedIn Badge" style="height: 30px; width: auto;">
</a>

# 🕺🪩BrandPulse Event Performance Analysis

## 🔍Overview

**BrandPulse**, a leading consumer electronics company, has invested in multiple sponsorships across various high-profile events in India. These sponsorships aimed to drive product signups directly at the event venues. The goal is to analyze the performance of each event sponsorship in terms of signups achieved and compare this performance against the sponsorship amount spent.

# Access Google Sheet for the comprehensive overview of the project [Here](https://docs.google.com/spreadsheets/d/1cpxpfxfXb3zbnxA4jQMWp_IqS89icgGRG0Kjfoge_M0/edit?usp=sharing)

## 🔎Objectives

- **EventType Analysis:**  
  Assess how different types of events are performed in terms of signups and sponsorship amounts spent.
  
- **City-wise Analysis:**  
  Evaluate how different cities performed based on signups and sponsorship costs.

## 🔠Data Description

The dataset contains details of each sponsored event, including:

- **Event Type:** Type of event (e.g., Music Festival, Sports Event, Conference)
- **City:** Location of the event
- **Sponsorship Amount:** Amount spent on sponsorship (in Rs.)
- **Product Signups:** Number of signups achieved

## Event Sponsorship and Signups Data
| Event ID  | Event Name                          | Event Type       | City       | Sponsorship Amount (in Rs.) | Product Signups |
|-----------|------------------------------------|------------------|------------|-----------------------------|-----------------|
| SN-MU-A1  | Sonu Nigam Tour                   | Music Festival   | Mumbai     | 500,000                     | 2,000           |
| KL-SP-A2  | Kabbadi League                     | Sports Event     | Delhi      | 700,000                     | 3,500           |
| TC-CF-A3  | Tech Conference                    | Conference       | Bangalore  | 400,000                     | 1,200           |
| RW-MU-A4  | Retro Waves                        | Music Festival   | Bangalore  | 450,000                     | 1,400           |
| BW-SP-A5  | Badminton World Championship       | Sports Event     | Mumbai     | 600,000                     | 4,200           |
| DS-CF-A6  | Developer Summit                   | Conference       | Delhi      | 300,000                     | 1,000           |
| MF-MU-A7  | Metal Fest                         | Music Festival   | Hyderabad  | 350,000                     | 1,500           |
| PL-SP-A8  | Pro League Football                | Sports Event     | Pune       | 650,000                     | 3,700           |
| FS-MU-A9  | Folk Sound Festival                | Music Festival   | Pune       | 300,000                     | 1,300           |
| WT-CF-A10 | Web Tech Conference                | Conference       | Hyderabad  | 250,000                     | 900             |
| FF-MU-A11 | Fusion Fiesta                      | Music Festival   | Hyderabad  | 480,000                     | 2,200           |
| CW-SP-A12 | Cricket World Cup Final            | Sports Event     | Mumbai     | 900,000                     | 5,000           |
| IS-CF-A13 | Innovation Summit                  | Conference       | Pune       | 350,000                     | 1,400           |
| AG-SP-A14 | Athletics Grand Prix               | Sports Event     | Bangalore  | 500,000                     | 2,700           |
| CS-MU-A15 | Classical Strings                  | Music Festival   | Pune       | 250,000                     | 1,100           |
| HJ-CF-A16 | Health & Wellness Summit           | Conference       | Hyderabad  | 400,000                     | 1,250           |
| BB-SP-A17 | Basketball Finals                  | Sports Event     | Hyderabad  | 750,000                     | 4,000           |
| LE-CF-A18 | Leadership Excellence              | Conference       | Delhi      | 350,000                     | 1,500           |
| BB-MU-A19 | Bollywood Bash                     | Music Festival   | Mumbai     | 600,000                     | 3,200           |
| RW-SP-A20 | Hockey World Cup                   | Sports Event     | Pune       | 850,000                     | 4,500           |


## 📊Exploratory Data Analysis (EDA)

### Key Metrics

- **Total Sponsorship Amount Spent:** Rs. 9,930,000
- **Number of Events Sponsored:** 20
- **Total Signups:** 47,550
- **Average Sponsorship Amount per Event:** Rs. 496,500
- **Average Signups per Event:** 2,378
- **Cost per Signup (CPS):** Rs. 209

## 🔖Cost per Signup (CPS) Analysis

## Event Sponsorship, Signups, and Cost Per Signup (CPS)

| Event ID  | Event Name                          | Event Type       | City       | Sponsorship Amount (in Rs.) | Product Signups | CPS (in Rs.) |
|-----------|------------------------------------|------------------|------------|-----------------------------|-----------------|--------------|
| SN-MU-A1  | Sonu Nigam Tour                   | Music Festival   | Mumbai     | 500,000                     | 2,000           | 250          |
| KL-SP-A2  | Kabbadi League                     | Sports Event     | Delhi      | 700,000                     | 3,500           | 200          |
| TC-CF-A3  | Tech Conference                    | Conference       | Bangalore  | 400,000                     | 1,200           | 333          |
| RW-MU-A4  | Retro Waves                        | Music Festival   | Bangalore  | 450,000                     | 1,400           | 321          |
| BW-SP-A5  | Badminton World Championship       | Sports Event     | Mumbai     | 600,000                     | 4,200           | 143          |
| DS-CF-A6  | Developer Summit                   | Conference       | Delhi      | 300,000                     | 1,000           | 300          |
| MF-MU-A7  | Metal Fest                         | Music Festival   | Hyderabad  | 350,000                     | 1,500           | 233          |
| PL-SP-A8  | Pro League Football                | Sports Event     | Pune       | 650,000                     | 3,700           | 176          |
| FS-MU-A9  | Folk Sound Festival                | Music Festival   | Pune       | 300,000                     | 1,300           | 231          |
| WT-CF-A10 | Web Tech Conference                | Conference       | Hyderabad  | 250,000                     | 900             | 278          |
| FF-MU-A11 | Fusion Fiesta                      | Music Festival   | Hyderabad  | 480,000                     | 2,200           | 218          |
| CW-SP-A12 | Cricket World Cup Final            | Sports Event     | Mumbai     | 900,000                     | 5,000           | 180          |
| IS-CF-A13 | Innovation Summit                  | Conference       | Pune       | 350,000                     | 1,400           | 250          |
| AG-SP-A14 | Athletics Grand Prix               | Sports Event     | Bangalore  | 500,000                     | 2,700           | 185          |
| CS-MU-A15 | Classical Strings                  | Music Festival   | Pune       | 250,000                     | 1,100           | 227          |
| HJ-CF-A16 | Health & Wellness Summit           | Conference       | Hyderabad  | 400,000                     | 1,250           | 320          |
| BB-SP-A17 | Basketball Finals                  | Sports Event     | Hyderabad  | 750,000                     | 4,000           | 188          |
| LE-CF-A18 | Leadership Excellence              | Conference       | Delhi      | 350,000                     | 1,500           | 233          |
| BB-MU-A19 | Bollywood Bash                     | Music Festival   | Mumbai     | 600,000                     | 3,200           | 188          |
| RW-SP-A20 | Hockey World Cup                   | Sports Event     | Pune       | 850,000                     | 4,500           | 189          |


## 🔖Event Type Performance Analysis

| Event Type      | Number of Events | Sponsorship Amount (Rs.) | Total Signups | CPS (Rs.) |
|----------------|-----------------|--------------------------|---------------|-----------|
| Music Festival | 7                 | 2,930,000                 | 12,700         | 230.71     |
| Sports Event   | 7                 | 4,950,000                 | 27,600         | 179.35     |
| Conference     | 6                 | 2,050,000                 | 7,250          | 282.76     |

**Insights:**  
- Sports Events performed best with the lowest CPS of Rs. 179.35.
- Conferences had the highest CPS of Rs. 282.76.

## 🔖City-wise Performance Analysis

| City      | Number of Events | Sponsorship Amount (Rs.) | Total Signups | CPS (Rs.) |
|-----------|-----------------|--------------------------|---------------|-----------|
| Mumbai    | 4                 | 2,600,000                 | 14,400         | 180.56     |
| Delhi     | 3                 | 1,350,000                 | 6,000          | 225.00     |
| Bangalore | 3                 | 1,350,000                 | 5,300          | 254.72     |
| Hyderabad | 5                 | 2,230,000                 | 9,850          | 226.40     |
| Pune      | 5                 | 2,400,000                 | 12,000         | 200.00     |

**Insights:**  
- Mumbai performed the best with the lowest CPS of Rs. 180.56.
- Bangalore had the highest CPS of Rs. 254.72.

## 📊Dashboard
![image](https://github.com/user-attachments/assets/725cfdd5-7ca9-43d5-bbfc-c60f9851fe03)

## 📌Key Insights

![image](https://github.com/user-attachments/assets/06574e68-d383-46d8-a3f0-398e79f8a44e)

- Sports Events has worked best for us with CPS of Rs.179.35 which is the lowest for all event types
- Conference as events has not performed well for us. It has CPS of Rs. 282.76 which is the highest for all event types
- Events held in Mumbai have performed well, with the CPS of Rs. 180.56, the lowest for any city
- Events held in Bengaluru, have not performed well for us, with the CPS of Rs. 254.72, the highest for any city
  
## 🤙Future Recommendations

- **Increase investment in sports events** due to their lower CPS and higher signup efficiency.
- **Re-evaluate conference sponsorships** to improve cost-effectiveness.
- **Focus more on Mumbai and Pune** for future events, given their strong performance.
- **Analyze underperforming cities** like Bangalore to optimize sponsorship spending.

## Connect 🤝
- 📩 <b>Email:</b> kshitijachilbule5@gmail.com
- 👩‍💻 <b>Github:</b> https://github.com/itskshitija
- 📶 <b>LinkedIn:</b> https://www.linkedin.com/in/kshitija-chilbule-b98515309/
- 🌐 <b>Medium:</b> https://medium.com/@kshitijachilbule2

