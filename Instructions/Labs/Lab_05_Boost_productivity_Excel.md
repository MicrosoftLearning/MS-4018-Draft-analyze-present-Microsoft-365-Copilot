---
lab:
  title: 'Lab 5: Boost your productivity with data-driven decisions with Copilot in Excel'
  description: Microsoft Copilot – Use Copilot in Excel to explore data, analyze trends, and generate insights.
  level: Lab 100
  duration: '30'
  islab: true
  status: 'released'
  targetDate: 2026-12-31
  primarytopics:
    - Microsoft 365
    - Microsoft Copilot
---

# Lab 5 - Boost your productivity with data-driven decisions with Copilot in Excel

Imagine you're a sales manager at Contoso. Your primary responsibility is to analyze sales data and identify trends that can help improve the company's performance. In this hands-on lab, you'll use Copilot in Excel to explore and analyze various aspects of the sales data for Contoso's Chai products.

You'll start by getting an overview of the data and identifying key metrics. Next, you'll analyze sales trends, compare product sales, and calculate total sales. Then, you'll use Copilot in Excel with Python to forecast future Artisanal Chai sales and explore the data with the Analyst agent. Finally, you'll generate insights from your analysis and share key findings with your team.

> [!NOTE]
> To fully complete this lab, you must have a OneDrive account or access to SharePoint.

### Sample file

Throughout this lab, you craft prompts for Microsoft Copilot that reference this file. Download and save the following file to your OneDrive folder before you continue.

[Contoso Chai Tea market trends.xlsx](https://go.microsoft.com/fwlink/?linkid=2268822)

#### Exercise 1 - Explore the data

To get an idea of market trends, you must first understand the overall performance of Contoso's Chai products. Your first step is to get an overview of the data and identify key metrics that can guide your analysis.

1. Open the sample file (**Contoso Chai Tea market trends.xlsx**) you uploaded to your OneDrive.

1. Select the Copilot icon in the bottom-right corner of the Excel window.

1. Make sure **Allow editing** is selected.

1. Enter and submit the following prompt in the Copilot pane:

    +++Summarize the dataset and provide an overview of the key metrics.+++

    Copilot may create a new sheet with a detailed set of important takeaways, essentially an executive summary of the data. The response highlights patterns and interpretations of the data and may suggest potential next steps. From this response, you can prompt Copilot to:

    +++Create a new sheet with a table showing the key patterns in the data.+++

    Copilot creates a table that summarizes key patterns in the data.

1. Review the table that Copilot generated.

#### Exercise 2 - Identify sales trends

As a sales manager, you need to identify trends in the sales data to make informed decisions. Review the total chai sales over the year to identify patterns and trends that can inform your sales strategy.

1. Continue in the opened Copilot pane.

1. Enter and submit the following prompt:

    +++Create a new sheet with a line chart of Total Chai Sales (units) over the months.+++

1. Review the chart of Total Chai Sales (units) over the months.

#### Exercise 3 - Compare product sales

To optimize your product offerings, you need to compare the sales of different chai products. Copilot can help you compare the sales of Artisanal Chai and Premade Chai to determine which product category performed better overall.

1. Continue in the opened Copilot pane.

1. Enter and submit the following prompt:

    +++Create a new sheet with a bar chart comparing Artisanal Chai Sales (units) and Premade Chai Sales (units) for each month.+++

    Copilot creates a new sheet and inserts the chart in your Excel workbook.

1. Summer months often show wide variance in sales. Enter and submit the following prompt to compare product performance:

    +++Summarize the total sales (units) for Artisanal Chai and Premade Chai over the summer.+++

1. Copilot may ask for clarification to better define "summer." Enter your preference, then review the results. Keep the Copilot pane open for the next exercise.

#### Exercise 4 - Forecast with Python

Copilot in Excel with Python lets you run statistical forecasts without writing code. Use this capability to predict future Artisanal Chai sales based on the monthly trends in your data.

1. In the Copilot pane, enter and submit the following prompt:

    +++Predict next quarter's Artisanal and Premade Chai sales using the best forecasting method based on historical performance, and include model diagnostics.+++

    Copilot generates Python code, executes it on the grid, and returns a new forecast sheet with a supporting chart.

1. Review Copilot's response and the forecast results. Select **Done** to confirm the changes.

1. Confirm that your file is saved. You'll use the updated version in the next exercise.

#### Exercise 5 - Explore data with the Analyst agent

The Analyst agent lets you ask questions about your data in a chat interface. In this exercise, you attach the sample file and ask a cross-metric question to see how the agent surfaces patterns that connect to your in-Excel analysis.

1. Open a browser and navigate to +++https://m365.cloud.microsoft+++.

1. In the left navigation, select the **Analyst** agent.

1. Select the **+** icon and attach the **Contoso Chai Tea market trends.xlsx** file from your OneDrive.

1. Enter and submit the following prompt:

    +++Compare Artisanal Chai and Premade Chai sales performance across the year and identify which product showed stronger growth.+++

1. Review the response. Notice how the Analyst agent surfaces comparisons and patterns from the same dataset you analyzed in Excel. This chat-based approach is especially useful when you're working across multiple files before building your workbook.

#### Exercise 6 - Generate insights

Summarize the key insights from your analysis. These insights help you make data-driven decisions to drive sales growth at Contoso.

1. In the opened Copilot Analyst agent pane, enter and submit the following prompt:

    +++Provide a summary of the top 5 key insights from the analysis of the Contoso Chai Tea market trends data.+++

1. Review the summary. You can use this text to get your team up to speed more quickly.

You now have hands-on experience using Copilot in Excel to analyze market trends, identify patterns, and generate valuable insights from your data. Continue trying new prompts in your Excel files to gain more practice.

**End of Lab**