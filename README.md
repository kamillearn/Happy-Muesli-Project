**BUSINESS CASE**  
A Muesli distribution company has approached you to help them understand their delivery process. They want to develop KPIs to help them keep track of the health of their business in order to improve the service they offer their customers.

The warehouse manager described the workflow as follows:
Order received (Day 1) - order processed in warehouse and made ready to ship (normally 2 days) - order leaves warehouse in truck following day - order delivered to customer (handled by logistics company).

The company has provided a list of their transactions over the course of the past years. They have full data on Order Date and the ‘On Truck Scan’ date but have limited visibility of what happens in between. They have on occasion sent some interns into the warehouse to record the ‘Ready to Ship’ date for as many orders as they could. The warehouse manager says they have not changed their processes much in the past year so they think it should be a good estimate. 

Customers can send orders every day but the warehouse only works Monday to Friday so any orders received on the weekends wait until Monday to be actioned.

Trucks Leave the warehouse on Mondays, Wednesdays and Fridays.
Orders leave on trucks the day after they are made ready for shipping (or two days later if there is no truck).
Customers can pay for Express Processing that means the orders leave on the truck the day the order is ready for shipping.

The logistics company has said they have on average 3 day delivery times to all locations. They transport goods on weekends but only deliver to customers from their local distribution centers on weekdays. The Muesli company has some data about exact delivery dates for a number of shipments that was gathered via marketing promotions they ran where customers scanned a QR code on the package in order to register for a prize. (We assume customers always scanned the code on the day of arrival).

**Deliverable:** 10-15 minutes presentation to the class / stakeholder describing how the business is performing based on the KPIs developed. Include why these specific KPIs are important, what they show about the description of the business given by the employees and how you developed them technically from the data given.

### Workflow:   
#### Understand Business Problem and Potential Solution
1. Map out the order process in a flow chart. 
2. Invent some KPIs that would be useful for tracking the performance processes overall and at each stage.
3. Label the flowchart with any logic that takes place that could affect how orders move through the stages. Include notes about assumptions the company and suppliers make about the processing time for each stage.  
#### Explore Data
4. Load the provided data into pandas and perform simple EDA to describe what data exists including descriptive statistics, identify missing values and any outliers.

Google sheets can be downloaded as excel files or csv files.
Pandas has a *`read_excel()`* method that can be used for reading excel files.
Alternatively there are packages that allow python to read directly from google sheets, feel free to explore these.  

5. Prepare your data for further analysis by combining and augmenting it in any way to generate the data needed to validate the assumptions and measure the KPIs. Use Pandas to create new columns to represent the processing times from the flow chart and that capture any logic needed to handle weekends or processing modes etc. Create new dataframes by joining tables as necessary.
#### Validate Solution
6. Make further exploratory data analysis to understand the time taken in each step in the order process and the range of values for each KPI. Identify problematic data or outliers in the KPIs. Show how long an average order takes as well as how much variation exists for each stage. 
7. Evaluate whether the data align with the explanations of the processes given by the company and identify any steps that have ‘concerning’ levels of reliability.
#### Visualise and Communicate
8. Use a Jupyter notebook to organise the text, code and visualisation that can be delivered to the customer.
9. Present your output as slides. Please create your slides in your [Google Drive EDA Project Folder](https://drive.google.com/drive/folders/1FC1K-fK0XDtzICEJdaJSIfas9vpgNHko). Talk about why you have done things, what your intentions were and how you technically developed the analysis by including screenshots of notebook code and output as necessary. Expectation is a 10-15 minutes presentation to the class. Think of it as a **stakeholder presentation** with technical elements.
