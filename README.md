# Appliance Energy Consumption Website

## Project Overview

This project is a small interactive website created for COS30045 Data Visualisation. The website presents information about appliance energy consumption in the Australian market, with a focus on televisions.

The website contains three pages:

- Home
- Televisions
- About Us

The Televisions page presents a data story using visualisations created from the cleaned Australian television dataset processed in T01(b) and explored in T02.

## Technologies Used

- HTML
- CSS
- JavaScript
- GitHub
- GitHub Desktop
- Vercel
- Visual Studio Code
- KNIME
- Miro

## Website Features

- Three-page website with Home, Televisions and About Us pages
- JavaScript navigation between pages
- Power logo that links back to the Home page
- Mouse-over effects for navigation links
- Highlighting of the current page
- Responsive CSS layout
- Television energy tips
- Six television data visualisations
- Data story with findings from the visualisations
- Footer with project information and GenAI acknowledgement

## Data Story

### Audience

The main audience for this data story is Australian TV consumers.

The visualisations are designed to help consumers understand the types of televisions currently available in Australia and how factors such as screen technology, screen size, brand and power consumption vary between models.

### Purpose

The data story answers six questions about television products:

1. What type of TV screen technologies are currently available in Australia and which are the most frequent?
2. What screen sizes are currently available, and which are the most frequent?
3. Which brands have the greatest number of different models?
4. Which type of screen technology consumes the least amount of power?
5. What is the relationship between screen size and power use?
6. What is the relationship between star rating and screen size?

The visualisations were selected to make the differences, frequencies and relationships easier to understand.

## Miro Storyboard

The storyboard was created in Miro to plan the data story and decide how each question would be presented.

The storyboard shows the audience, six questions, the purpose of each visualisation, the selected chart type and the expected insight.

Miro storyboard:

https://miro.com/app/board/uXjVHj-p180=/?share_link_id=341651278908

## About the Data

The data comes from the Australian Government's Energy Rating Data for household appliances – Labelled Products dataset, focusing on televisions.

The dataset contains information about television products available in Australia, including brand, model number, screen size, screen technology, power consumption and star rating.

### Data Processing

The original dataset contained 5,028 records.

The data was processed using KNIME in T01(b). The processing included:

- Removing duplicate records
- Filtering the dataset to available television models
- Selecting the columns needed for the analysis
- Cleaning and standardising brand names
- Converting screen size from centimetres to inches
- Creating additional data needed for the analysis

After processing, the cleaned dataset contained 4,759 available television models.

### Data Accuracy and Limitations

The visualisations are based on the available records in the dataset after data cleaning and filtering.

Some variables contain missing or incomplete values, so the number of records used for individual visualisations may differ.

The results describe the television models included in the dataset and may not represent every television available in the Australian market.

Power consumption can also vary between individual television models, even when they have the same screen technology or screen size.

### Privacy

The dataset contains information about television products rather than personal information about individual consumers.

No personal consumer information was used in this project.

### Ethics

The data is used to explore television energy consumption and communicate findings to consumers.

The visualisations are presented to help users understand the data. The results should not be treated as a recommendation to purchase a particular brand or television model.

## Data Visualisations

The Televisions page contains six visualisations based on the cleaned dataset explored in T02.

1. Screen Technology Distribution
2. Screen Size Distribution
3. Number of TV Models by Brand
4. Median Power Consumption by Screen Technology
5. Screen Size vs Power Consumption
6. Screen Size vs Star Rating

### Key Findings

- LCD (LED) was the most frequently available screen technology, with 3,794 models.
- 65 inches was the most frequent screen size, with 777 models.
- KOGAN had the greatest number of different TV models, with 807 models.
- LCD had the lowest median power consumption at 71.3472 W.
- Larger televisions generally tended to use more power, although there was variation between models.
- There was no clear consistent relationship between screen size and star rating in the dataset.

## AI Declaration

ChatGPT and GitHub Copilot were used to assist with the development of this website.

ChatGPT was used to help with HTML, CSS and JavaScript code, explain programming concepts, improve website content, organise the website structure, and help with debugging.

GitHub Copilot was used in Visual Studio Code to explain parts of the existing code, suggest improvements, and provide coding suggestions. The suggestions were reviewed and tested before being used.

## Reflection on GenAI Use

Using GenAI helped me understand the development process and solve coding problems more easily. ChatGPT was useful for explaining code and helping me understand how the different HTML, CSS and JavaScript files work together.

GitHub Copilot was useful because it could provide suggestions directly in Visual Studio Code and explain parts of my code. I learned that the suggestions still need to be checked because the generated code may not always be suitable for the project.

Overall, GenAI helped me develop the website faster, but I still needed to understand the code and test the website to make sure everything worked correctly.

## Project Author

Bernice Liu

COS30045