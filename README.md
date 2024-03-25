# Stock-Price-Analysis-and-Visualization

![download](https://github.com/ANSHPG/Stock-Price-Analysis-and-Visualization/assets/132222062/96e88a1e-acc7-430a-9c7c-ec2524c34e3a)

The Stock Price Analysis and Visualization project is a comprehensive tool designed to facilitate the analysis and visualization of stock price data across various parameters such as 'open,' 'close,' 'highest,' and 'lowest.' The project stemmed from a need to gather accurate and reliable stock price data efficiently. Initially, faced with challenges in sourcing data, the project owner took the initiative to manually curate a CSV dataframe comprising 12 time frames with intervals of 5 minutes each.

Upon successfully creating the algorithm and testing it on the manually curated dataset, the project owner sought to enhance the project's capabilities by incorporating historical data from official sources such as the National Stock Exchange (NSE) and Bombay Stock Exchange (BSE). Subsequently, the project was tested and validated using historical data spanning 22 and 82 days obtained from NSE and BSE, respectively.

The core functionality of the project involves dividing the stock price data into two primary categories: gains and losses. Gains refer to instances where the opening price is less than the closing price, while losses denote scenarios where the closing price is less than the opening price. Subsequently, the data is further segmented to calculate the highest and lowest ticks for gains and losses individually.

For gains, the highest bar is determined by the difference between the highest price and the closing price, while the lowest bar is calculated using the difference between the opening price and the lowest price. Conversely, for losses, the highest bar is determined by the difference between the opening price and the highest price, and the lowest bar is calculated using the difference between the closing price and the lowest price.

To enhance the visual representation of the data, custom colors are assigned to the bars in the plot, providing clarity and differentiation between different parameters.

This repository, maintained by Anshuman Pattnaik, is made available for public use, enabling stakeholders to access and leverage the functionalities of the Stock Price Analysis and Visualization tool for informed decision-making in the financial domain.






