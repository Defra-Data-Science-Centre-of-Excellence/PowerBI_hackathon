# Power BI in the Data Analytics & Science Hub (DASH) platform

- Authors: Margarita Tsakiridou, Fluke Kasemsubphaisarn, Kate Hutchinson; DASH
- Date: 10/02/2025


## Summary

This repo was initially created for the PowerBI hackathon that we run the week 15-19th April as part of the DASH launch week. The materials and instructions provided are a great example to practise PowerBI on DASH. Follow the instructions provided below. 

## How to use

The instructions below provide a step-by-step guide for using either a 'penguins' or the 'Leeds Service requests' datasets. You can also use another dataset of your choice. 

### Accessing Power BI & DASH data

- To open Power BI, you will need to sign to the [Azure Virtual Desktop (AVD)](https://client.wvd.microsoft.com/arm/webclient/index.html). Please read through the[relevant Playbook chapter](https://dap-prd2-connect.azure.defra.cloud/DASH-Playbook/avd.html) for more information on logging on and using the AVD.
- The [PowerBI chapter](https://dap-prd2-connect.azure.defra.cloud/DASH-Playbook/avd.html](https://dap-prd2-connect.azure.defra.cloud/DASH-Playbook/powerbi.html#connecting-to-data) provides a detailed walkthrough for importing DASH data to Power BI, however, this and other routes for importing data are described further in the next section.

### Power BI data importing

There's a variety of ways to import data but most of the time, you will only need to import data from the Sharepoint, OneDrive or Data Lake (the DASH platfrom!). The flow chart below guides you through the steps to take to import data from those areas. We have also provided detailed [guidance with screenshots](https://github.com/Defra-Data-Science-Centre-of-Excellence/PowerBI_hackathon/blob/main/screenshot_guidance.png) for each of the processes described in our flowchart.

<img src="https://github.com/Defra-Data-Science-Centre-of-Excellence/PowerBI_hackathon/blob/main/Power%20BI%20Data%20Process%20(1).png" alt="Importing data workflow" width="800" height="800">

<br>

### Creating your report

#### Penguins (Basic)

Here is the [PDF copy](https://github.com/Defra-Data-Science-Centre-of-Excellence/PowerBI_hackathon/blob/main/sample_penguins_MT_V1.pdf) of the Power BI report. It uses the 'penguins' dataset (hint: it's the same dataset described in [Chapter 8.3](https://dap-prd2-connect.azure.defra.cloud/DASH-Playbook/avd.html) of our Playbook!). This report will be more suitable to people with limited or no previous experience on Power BI. It focuses mainly on showcasing the 'power' and versatility of Power BI, without focussing too much on the most complex parts of working with Power BI, such as Data Analysis Expressions (DAX) and PowerQuery.

#### Leeds environmental service requests (Advanced)

Here is the PDF copy of the Power BI report that uses the 'Leeds service requests' data. This report will be more suitable for you if you already feel somewhat comfortable with Power BI. It brings together all the features of Power BI, including importing data to DASH, advanced data cleaning in Power Query, creating measures using DAX and geospatial analysis.

This report uses a dataset on Environment Service Requests received by Leeds City Council, which is available [here](https://datamillnorth.org/dataset/e61k0/environmental-service-requests). You  will need to download the data and upload it to your data lake workspace yourself. Instructions are available [here](https://dap-prd2-connect.azure.defra.cloud/DASH-Playbook/databricks.html#uploading-data-to-the-dbfs).


#### Using your own data

Using the information we have supplied above, you should be able to either upload your own data to the data lake or navigate to and select one or more of the existing datasets already living in the DASH Data Lake. Any questions, let us know, we'll do our best to help you. It might be a good idea to wireframe your end product and think of your user needs before starting creating your visuals.


### Saving your report

Through the AVD you should have access to your documents in OneDrive. Please save as soon as possible your report to a folder of your choosing and ensure you remember to hit the 'save' button at regular intervals.

### Sharing your report

There are quite few options for sharing your dashboard. The one you chose will depend on your audience, functionality, and format you need.

- PDF: You can extract your report as a PDF file, which you can then share as widely as you want. However, there is limited interactivity preserved on PDFs.
- .pbix: You can share your shave .pbix file with colleagues who also have Power BI desktop to open and view your file. This option is not recommended as it runs the risk of creating a separate version of your file. This means that edits will live locally on each developer's laptop and will not update for the users.
- Power BI service: You can publish your report to the Power BI Service. This is the cloud version of Power BI desktop, which allows you to host, update and share your Power BI reports with your users. For today's session, we recommend that you chose 'My workspace'. For your future Power BI projects, you might need to create or request access to your team's or project's Power BI workspace.

### Useful links

#### DASH
- [Playbook](https://dap-prd2-connect.azure.defra.cloud/DASH-Playbook/)
- [DASH SharePoint](https://defra.sharepoint.com/sites/Community448/SitePages/Welcome-to-the-Data-Science-Centre-of-Excellence.aspx)
- Sign up to our [Data Science Sessions](https://defra.sharepoint.com/sites/Community448/SitePages/Discussion-Sessions-(Coffee-and-Coding).aspx)

#### Power BI
- [Microsoft Learn](https://learn.microsoft.com/en-us/training/powerplatform/power-bi)
- Datacamp ([premium sign up](https://www.datacamp.com/business/partners/Defra-and-datacamp-partnership), [Power BI courses](https://app.datacamp.com/search?q=Power+BI))
- [Logging on, using, and importing the penguin data on PowerBI on the AVD](https://dap-prd2-connect.azure.defra.cloud/DASH-Playbook/avd.html)
- [PowerBI Data Process Flowchart](https://github.com/Defra-Data-Science-Centre-of-Excellence/PowerBI_hackathon/blob/main/Power%20BI%20Data%20Process%20(1).png) and [Flowchart Guidance with Screenshots](https://github.com/Defra-Data-Science-Centre-of-Excellence/PowerBI_hackathon/blob/main/Power%20BI%20Data%20Process%20(2).png)
- Penguins Report ([PDF](https://github.com/Defra-Data-Science-Centre-of-Excellence/PowerBI_hackathon/blob/main/sample_penguins_MT_V1.pdf), [.pbix](https://github.com/Defra-Data-Science-Centre-of-Excellence/PowerBI_hackathon/blob/main/sample_penguins_V1_MT.pbix), you might need to download this and open it with PowerBI desktop to view it)
- [Leeds Environmental Service Requests](https://datamillnorth.org/dataset/e61k0/environmental-service-requests)
- Leeds Environmental Service Requests Report [PDF](https://github.com/Defra-Data-Science-Centre-of-Excellence/PowerBI_hackathon/blob/main/Leeds%20Service%20Requests%20Report.pdf), [Report](https://app.powerbi.com/links/xsZXkk1whR?ctid=770a2450-0227-4c62-90c7-4e38537f1102&pbi_source=linkShare)


#### Training

- Defra Power BI Community on [Sharepoint](https://defra.sharepoint.com/sites/Community909/SitePages/Power-BI-Home.aspx)
- [Microsoft Learn](https://learn.microsoft.com/en-us/training/powerplatform/power-bi)
- [DataCamp](https://app.datacamp.com/search?q=Power+BI) - here's a [link](https://www.datacamp.com/business/partners/Defra-and-datacamp-partnership) to sign up for a free premium DataCamp acount, on us!


## Next Steps

- Improve the data handling information (UC vs not, as UC rolls out and Playbook content is updated)
- Add a folder in the unrestricted part of the lake with data
- Let us know any thoughts/suggestions how to improve this repo.



## Troubleshooting

Please get in touch with [datascience@defra.gov.uk](mailto:datascience@defra.gov.uk) if you have any questions or suggestions.

