# text_to_chart_LLM_integration

About the Project:
Imagine you are a data analyst or a data scientist of a marketing team at an e-commerce company. The company needs to understand customer purchasing behaviors over the last year to tailor their upcoming holiday campaigns. Traditionally, this would involve complex SQL queries, data wrangling in Python, and perhaps building visual dashboards to interpret the results including analyzing spreadsheets, creating charts, and maybe even some statistical analysis, tasks that require considerable time and expertise.

With the integration of Langchain and LLMs, you can simply ask, "Show me a visualization of monthly sales trends by product category," or "Generate a heatmap of customer activity by region." This project analyzes a dataset using IBM Watsonx.ai LLM integrated with LangChain. It enables natural language querying and visualization of student data, allowing exploration of correlations between demographics, grades, and lifestyle factors. The project demonstrates the power of combining AI-driven language models with structured data analysis.

## LLM Integration

The project integrates IBM Watsonx’s LLM to interact with the dataset in natural language. By connecting the LLM with LangChain’s Pandas DataFrame agent, users can ask questions about the dataset, filter records, and perform complex analysis without writing explicit code. The LLM generates both answers and the underlying Python commands, making the process transparent and educational.

## Data Analysis and Visualization

Users can generate visualizations such as bar charts, pie charts, box plots, and scatter plots through natural language prompts dynamically.  This not only speeds up the data analysis process but also allows team members who may not be tech-savvy to engage directly with the data and make informed decisions quickly. This approach fosters a more collaborative environment and ensures that strategic decisions are backed by real-time data insights, visually represented for easy comprehension. The LLM iteratively improves its generated code to provide accurate and clear visualizations.

## Key Features
- Natural language querying of data.
- Automatic visualization of demographics, academic performance, and lifestyle factors.
- Transparent generation of Python code used for data analysis.
- Facilitates exploratory data analysis and insights into student performance.

## Tech
ibm-watson-ai for using LLMs from IBM's watsonx.ai. LangChain, langchain-ibm, langchain-experimental for using its agent function to interact with data. matplotlib for additional plotting tools. seaborn for visualizing the data.
