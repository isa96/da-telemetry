# Deloitte Technology

## Data Analysis
> Build a dashboard to explore the client's telemetry data.

## Background Information
Daikibo's tech team has converted all telemetry data collected from the 4 factories of the company:

* Daikibo Factory Meiyo (Tokyo, Japan)
* Daikibo Factory Seiko (Osaka, Japan)
* Daikibo Berlin (Berlin, Germany)
* Daikibo Shenzhen (Shenzhen, China)

Each location has 9 types of machines, sending a message every 10 min. Daikibo has been collecting this data for 1 month (May 2021) and 
they've just shared this data in the form of a single JSON file.

The reason this client wanted to collect telemetry was to answer 2 questions:

* In which location did machines break the most?
* What are the machines that broke most often in that location?

## Task Brief
My task is to analyze the telemetry data collected by Daikibo (and unified with your algorithm) in a software called Tableau. 
Here are the steps that I need to take:

1. Download the 1 year free trial of Tableau. (Link in the Resources, Gmail account works)
2. Install Tableau on my computer and register an account with the same email I used to download the software.
3. Download the daikibo-telemetry-data.json.zip file -> unzip -> and import it in Tableau.
4. Create a calculated measure field "Unhealthy" with the value of 10 for every unhealthy status (representing 10min of potential down time since the previous message).
5. Create a bar-chart: Down Time per Factory.
6. Create new sheet with a new bar-chart: Down Time per Device Type.
7. Create a Dashboard with the 2 previous sheets and set the first chart to be used as a filter (selecting factory in the first chart, shows only the down time of the machines in this factory there in the second chart).
8. Select the factory with the most down time (click on its bar), make a screenshot of the dashboard and upload it as a submission for this task.


