# EYBadges
EY Badge Recommendation System and Badge Impact Metrics

## Problem Statement

EY GDS teams offer its professionals a learning intervention called EY Badges which helps build competency across varying domains. Currently, there are over 100 badges on offer and the challenge is to pick the correct one. 

How do we recommend the right EY badge to an employee? How do we ascertain its impact, i.e. create a mechanism to correlate the effect of badges on an individual’s performance?

## Tasks Involved

1. Recommendation mechanism to the professionals on what badges they can pick up based on the below factors:
  
    Job family they belong to  
    Competency profile  
    Badges earned across Global Delivery Services (GDS)  
    Duration of badge (time taken to complete a badge)  
    Promotion requirements
  
2. Create a mechanism to monitor the impact of badge on individual performance in terms of new projects, increased efficiency, mentoring other team members, etc.

# EY-Recommendation-Engine

Recommendation system: [Link to Repo](https://github.com/neha-duggirala/EY-Recommendation-Engine)

The concept behind building the recommendation system is collaborative badge recommendations. This engine helps an individual to pick up a right badge eliminating the burden of scrolling through hundreds of badges present on the EY badge platform. The following scenarios that are taken into consideration:
1.	GDS SL - Domain Affinity: The degree to which service level tends to choose which domain.
2.	Domain – Sub Domain Similarity: Measure most employees who have chosen a domain tend to take which sub domain.
3.	Rank Name – Badge Type Similarity: The grade level and experience of an employee plays an important role in choosing badge difficulty. 
The key idea behind this is that similar individuals share the same interest and that similar badges are liked by an individual.
1. Level – based: The domain recommendation is given by which GDS SL and Rank they belong to. What are the most common domains picked up to the users belonging to that level?
2. Domain & Sub Domain based: The sub domain recommendation is given by comparison of a domain and most popular sub domain picked up the users of same GDS SL level and Rank.
Based on the above two points, two matrices have been extracted by performing a few operations and computation.  From the derived engine, when an individual finishes a badge, the engine inputs the badge details and gives the top matching recommendations. 

# Metrics-ui

EY badge metrics UI: [Link to Repo](https://github.com/neha-duggirala/EYBadge-Metrics-UI/tree/for-git-deployment)

EY badge metrics API: [Link to Repo](https://github.com/neha-duggirala/EYBadgeMetrics)

# UI Screenshots 
<img src="https://github.com/neha-duggirala/EYBadge-Metrics-UI/blob/master/Screenshots/Screenshot%20(230).png" />
<img src="https://github.com/neha-duggirala/EYBadge-Metrics-UI/blob/master/Screenshots/Screenshot%20(231).png" />
<img src="https://github.com/neha-duggirala/EYBadge-Metrics-UI/blob/master/Screenshots/Screenshot%20(232).png" />
<img src="https://github.com/neha-duggirala/EYBadge-Metrics-UI/blob/master/Screenshots/Screenshot%20(233).png" />
<img src="https://github.com/neha-duggirala/EYBadge-Metrics-UI/blob/master/Screenshots/Screenshot%20(234).png" />
<img src="https://github.com/neha-duggirala/EYBadge-Metrics-UI/blob/master/Screenshots/Screenshot%20(235).png" />
<img src="https://github.com/neha-duggirala/EYBadge-Metrics-UI/blob/master/Screenshots/Screenshot%20(236).png" />
<img src="https://github.com/neha-duggirala/EYBadge-Metrics-UI/blob/master/Screenshots/Screenshot%20(237).png" />

# Steps to Run UI
## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
