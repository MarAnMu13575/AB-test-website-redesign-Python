# AB-Test-Website-redesign-Python

## Introduction

Working for an early-stage startup, the team has been working on a redesign of the landing page. 
The team believes a new design will increase the number of people who click through and join your site, increasing the current conversion rate. 
Using and A/B test on a subset of user database we will determine if the old design is better than the new ones.

## Description of the dataframe

Column description
- "treatment" - "yes" if the user saw the new version of the landing page, no otherwise.
- "new_images" - "yes" if the page used a new set of images, no otherwise.
- "converted" - 1 if the user joined the site, 0 otherwise.
- "n_count" - count of values in dataframe for each design type
- "percent_rate" - percent of values in dataframe for each design type
- "group" - group of each desing type

The control group is those users with "no" in both columns: the old version with the old set of images. Treatment = 0, New images = 0.
