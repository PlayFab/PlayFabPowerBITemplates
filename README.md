# PlayFabPowerBITemplates
This repository contains Power BI templates that allow you to generate near-real time analytics and insights about your game. In less than 10 minutes, easily build your own Power BI dashboards by getting started with our templates. 

## Prerequisites
You must have a Fabric KQL or Azure Data Explorer (ADX) Database that contains your playstream events for you to use the template. If you have not setup a data connection yet, follow this guide to get started: [PlayFab Data Connections Quickstart](https://learn.microsoft.com/en-us/gaming/playfab/data-analytics/export-data/data-connection-quickstart)

## Instructions 
1. Download the template that you would like to use.
2. Open Power BI Desktop. If you don't have it installed, follow this tutorial: [Get started with Power BI Desktop - Power BI | Microsoft Learn](https://learn.microsoft.com/en-us/power-bi/fundamentals/desktop-getting-started#install-and-run-power-bi-desktop)
3. Select the **File** tab at the top of the screen.
4. Select **Browse this device** at the bottom left of the screen.
5. Look for the template file (.pbit) that you downloaded, **select** and **open** it.
6. Fill in the connection parameters on the template window.
    - In the **URI** field, enter the Query URI of your KQL Database or your ADX cluster connection URI.
    - In the **Database** field, enter the name of your KQL/ADX Database
    - In the **Table** field, enter the name of the table where your playstream events are located.
8. Select the **Load** button.
9. (Optional) Select the **Publish** button at the top of the page to publish your report to your MS Fabric workspace.

## Templates

**Overview Report**: This template allows you to evaluate daily performance accross multiple KPIs including daily active players, new players, and new player retention. Get further insights by breaking these metrics down based on Platform or Region.

## Contact Us

We love to hear from our developer community!
Do you have ideas on how we can make our products and services better?

Our Developer Success Team can assist with answering any questions as well as process any feedback you have about PlayFab services.

[Forums, Support and Knowledge Base](https://community.playfab.com/index.html)

## Contributing

We are more than happy to accept external contributions! If you want to propose a new template or change to a template, feel free to open a Pull Request directly.

## Copyright and Licensing Information

Apache License --
Version 2.0, January 2004
http://www.apache.org/licenses/

Full details available within the LICENSE file.
