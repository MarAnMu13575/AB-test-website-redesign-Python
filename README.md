# AB Test: Website Redesign with Python

## Introduction

As part of the ongoing efforts to improve the startup's landing page, the team has been working on a redesign with the belief that it will increase the number of people who click through and join the site, ultimately improving the current conversion rate. To evaluate the effectiveness of the new design, an A/B test will be conducted on a subset of the user database. The test will compare the performance of the old design with the new design to determine which version yields better results in terms of user conversion.

## Description of the DataFrame

The dataset used for the A/B test contains the following columns (DataCamp dataset):

- **"treatment"**: Indicates whether the user saw the new version of the landing page. It is labeled as "yes" if the user saw the new design and "no" otherwise.

- **"new_images"**: Indicates whether the page used a new set of images. It is labeled as "yes" if the new design used a different set of images and "no" if the old images were used.

- **"converted"**: Represents whether the user joined the site. It is labeled as 1 if the user successfully joined and 0 otherwise.

- **"n_count"**: The count of values in the DataFrame for each design type. It provides the total number of users for each design variation.

- **"percent_rate"**: The percentage of values in the DataFrame for each design type. It helps to understand the distribution of users among different design variations.

- **"group"**: Indicates the group to which each design type belongs. The control group comprises users with "no" in both "treatment" and "new_images" columns, representing the old version with the old set of images (Treatment = 0, New images = 0).

## Analysis Steps

1. **Data Preprocessing**: Prepare and clean the data, handling any missing values or inconsistencies.

2. **Exploratory Data Analysis**: Explore the dataset to gain insights into the distribution of users among different design variations and analyze conversion rates.

3. **A/B Test**: Conduct hypothesis testing to compare the performance of the old design with the new design. Evaluate the significance of any differences observed.

4. **Visualization**: Visualize the results of the A/B test to provide clear and compelling insights.

5. **Conclusion**: Summarize the findings and provide recommendations based on the A/B test results.

## Contributing

Contributions to this project are welcome. If you have any suggestions, improvements, or bug fixes, please feel free to open an issue or submit a pull request.

---

By conducting the A/B test on the website redesign, we aim to make data-driven decisions that will enhance the user experience and increase the conversion rate, ultimately contributing to the success of the startup. Thank you for being a part of this effort! 🚀💻📈
