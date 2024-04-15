# Power BI in the Data Analytics & Science Hub (DASH) platform

### Date: 19/04/2024
### Authors: Margarita Tsakiridou, Fluke Kasemsubphaisarn, Kate Hutchinson

---


	
[![Launch week logo](https://github.com/Defra-Data-Science-Centre-of-Excellence/PowerBI_hackathon/blob/main/launch%20banner%20intranet%201.png)](https://defra.sharepoint.com/sites/Community448/SitePages/DASH-Launch-Week.aspx)

# 1. Introduction

Thank you for signing up to our Power BI Hackathon! Here is some important information for the day:

- We assume that you are already onboarded to the platform. If true, you should be able to access our [Playbook](https://dap-prd2-connect.azure.defra.cloud/DASH-Playbook/#content).
- The point of this hackathon is to help you create a finished product on the DASH platform. We have prepared this tutorial/walkthrough using sample datasets, but you are very welcome to use other datasets of the DASH platform or your own data to create your product.
- If you chose to replicate the reports we have prepared for today, you will find within this repository their PDFs. .pbix are also available, but we'd advise you to not use these from the beginning.
  
<br>

# 2. Setting the scene

## 2.1 Resources and Training

If you are not already a Power BI evangelist, fear not. Power BI is an extremely versatile and user friendly tool. We have provided below a list of resources to help you get started. Remember, it's always a good idea to google or we can try to answer any questions you might have. 

- [Microsoft Learn](https://learn.microsoft.com/en-us/training/powerplatform/power-bi)
- [DataCamp](https://app.datacamp.com/search?q=Power+BI) - here's a [link](https://www.datacamp.com/business/partners/Defra-and-datacamp-partnership) to sign up for a free premium DataCamp acount, on us! 

## 2.2 Accessing Power BI & DASH data

- To open Power BI, you will need to sign to the [Azure Virtual Desktop (AVD)](https://client.wvd.microsoft.com/arm/webclient/index.html). Please read through [Chapter 8.1](https://dap-prd2-connect.azure.defra.cloud/DASH-Playbook/avd.html)  in our Playbook for more information on logging on and using the AVD.
- [Chapter 8.3](https://dap-prd2-connect.azure.defra.cloud/DASH-Playbook/avd.html) provides a detailed walkthrough for importing DASH data to Power BI, however, this and other routes for importing data are described further in the next section.

## 2.3 Power BI data workflows

There's a variety of ways to import data but most of the time, you will only need to import data from the Sharepoint, OneDrive or Data Lake (the DASH platfrom!). The flow chart below guides you through the steps to take to import data from those areas. We have also provided detailed [guidance with screenshots](https://github.com/Defra-Data-Science-Centre-of-Excellence/PowerBI_hackathon/belob/main/Power%20BI%20Data%20Process%20(2).png) for each of the processes described in our flowchart.

<img src="https://github.com/Defra-Data-Science-Centre-of-Excellence/PowerBI_hackathon/blob/main/Power%20BI%20Data%20Process%20(1).png" alt="Importing data workflow" width="800" height="800">

<br>

# 3. Developing a product

## 3.1 Penguins (Basic)

Here is the [PDF copy](https://github.com/Defra-Data-Science-Centre-of-Excellence/PowerBI_hackathon/blob/main/sample_penguins_MT_V1.pdf) of the Power BI report. It uses the 'penguins' dataset (hint: it's the same dataset described in [Chapter 8.3](https://dap-prd2-connect.azure.defra.cloud/DASH-Playbook/avd.html) of our Playbook!). This report will be more suitable to people with limited or no previous experience on Power BI. It focuses mainly on showcasing the 'power' and versatility of Power BI, without focussing too much on the most complex parts of working with Power BI, such as Data Analysis Expressions (DAX) and PowerQuery.

## 3.2 Leeds environmental service requests (Advanced)

Here is the PDF copy of the Power BI report that uses the 'Leeds service requests' data. This report will be more suitable for you if you already feel somewhat comfortable with Power BI. It brings together all the features of Power BI, including importing data to DASH, advanced data cleaning in Power Query, creating measures using DAX and geospatial analysis.

This report uses a dataset on Environment Service Requests received by Leeds City Council, which is available [here](https://datamillnorth.org/dataset/e61k0/environmental-service-requests). The data is available in Fluke's data lake workspace (location path is shown below; please let us know if the path looks greek to you, we'll walk you through it). However, we'd recommend you try to download the data and upload it to your data lake workspace yourself. Here's our [Data Handling Guide](https://adb-7393756451346106.6.azuredatabricks.net/?o=7393756451346106#notebook/486749531468438/command/486749531468443).

- Data Lake location **/dbfs/mnt/lab/unrestricted/fluke.kasemsubphaisarn@defra.gov.uk/Accelerator/Pilot/Leeds_Service_Requests_2007_2011.csv**


## 3.3 Using your own data

Using the information we have supplied above, you should be able to either upload your own data to the data lake or navigate to and select one or more of the existing datasets already living in the DASH Data Lake. Any questions, let us know, we'll do our best to help you. It might be a good idea to wireframe your end product and think of your user needs before starting creating your visuals.


<br>

# 4. Your report

# 4.1. Saving

Through the AVD you should have access to your documents in OneDrive. Please save as soon as possible your report to a folder of your choosing and ensure you remember to hit the 'save' button at regular intervals.

# 4.2 Sharing

There are quite few options for sharing your dashboard. The one you chose will depend on your audience, functionality, and format you need.

- PDF: You can extract your report as a PDF file, which you can then share as widely as you want. However, there is limited interactivity preserved on PDFs.
- .pbix: You can share your shave .pbix file with colleagues who also have Power BI desktop to open and view your file. This option is not recommended as it runs the risk of creating a separate version of your file. This means that edits will live locally on each developer's laptop and will not update for the users.
- Power BI service: You can publish your report to the Power BI Service. This is the cloud version of Power BI desktop, which allows you to host, update and share your Power BI reports with your users. For today's session, we recommend that you chose 'My workspace'. For your future Power BI projects, you might need to create or request access to your team's or project's Power BI workspace.

# 4.3 Advertising

We hope you enjoyed spending the day on the DASH platform and we hope to see you again soon. We would be very keen to invite you to our next Data Science Session (17th May; please sign up [here](https://defra.sharepoint.com/sites/Community448/SitePages/Discussion-Sessions-(Coffee-and-Coding).aspx) to receive invites) to share your experience and work with more colleagues that are currently being onboarded to the DASH platform. 

<br>

# 5. Useful links

- [Playbook](https://dap-prd2-connect.azure.defra.cloud/DASH-Playbook/)
- [DASH SharePoint](https://defra.sharepoint.com/sites/Community448/SitePages/Welcome-to-the-Data-Science-Centre-of-Excellence.aspx)
- [PowerBI Data Process Flowchart](https://github.com/Defra-Data-Science-Centre-of-Excellence/PowerBI_hackathon/blob/main/Power%20BI%20Data%20Process%20(1).png) and [Flowchart Guidance with Screenshots](https://github.com/Defra-Data-Science-Centre-of-Excellence/PowerBI_hackathon/blob/main/Power%20BI%20Data%20Process%20(2).png)
- Penguins report ([PDF](https://github.com/Defra-Data-Science-Centre-of-Excellence/PowerBI_hackathon/blob/main/sample_penguins_MT_V1.pdf), [.pbix](https://github.com/Defra-Data-Science-Centre-of-Excellence/PowerBI_hackathon/blob/main/sample_penguins_V1_MT.pbix), you might need to download this and open it with PowerBI desktop to view it)
- [Leeds Environmental Service Requests](https://datamillnorth.org/dataset/e61k0/environmental-service-requests)
- Sign up to our [Data Science Sessions](https://defra.sharepoint.com/sites/Community448/SitePages/Discussion-Sessions-(Coffee-and-Coding).aspx)
