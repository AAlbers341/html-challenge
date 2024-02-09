# HTML Challenge - Mars News HTML Scrape & Mars Temperature Analysis

This project involves two main tasks: scraping Mars news articles from a webpage and analyzing Mars temperature data. Below are the details of each task.

## Mars News HTML Scrape

Utilizing Splinter, the project scrapes [this webpage](https://static.bc-edx.com/data/web/mars_news/index.html) to extract article titles and previews into a dictionary.

### Sources
All code utilized in this section was referenced through course material, such as examples and exercises.

## Mars Temperature Analysis

Utilizing Splinter, this part of the project scrapes the 'Mars Temperature Data' table to conduct exploratory data analysis (EDA) with Pandas.

### Preliminary EDA

1. **Number of Months on Mars**: 12
2. **Martian Days of Data**: 1867
3. **Coldest and Warmest Months on Mars (Curiosity Location)**:
   - Coldest Month: March, with an average minimum daily temperature of approximately -83.31°C.
   - Warmest Month: August, with an average minimum daily temperature of approximately -68.38°C.

   ![Coldest and Warmest Months Bar Chart](https://github.com/AAlbers341/html-challenge/assets/149892097/0c98328f-b89a-407d-8a25-8360c3809b31)

4. **Months with Lowest and Highest Atmospheric Pressure on Mars**:
   - Lowest Atmospheric Pressure: June, with an average daily atmospheric pressure of approximately 745.05 Pa.
   - Highest Atmospheric Pressure: September, with an average daily atmospheric pressure of approximately 913.31 Pa.

   ![Atmospheric Pressure Bar Chart](https://github.com/AAlbers341/html-challenge/assets/149892097/76f4b18c-8821-4e58-89ef-6d0b6bc97e9b)

5. **Martian Year Duration in Terrestrial Days**: Estimated visually by plotting the daily minimum temperature, showing the period Mars circles the Sun once.

   ![Martian Year Duration Plot](https://github.com/AAlbers341/html-challenge/assets/149892097/ebdc2e40-504f-4a1c-9bab-9b03d31c11c7)
