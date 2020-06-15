---
unique-page-id: 7504238
description: Custom RTP Dashboards in Google Universal Analytics - Marketo Docs - Product Documentation
title: Custom RTP Dashboards in Google Universal Analytics
---

# Custom RTP Dashboards in Google Universal Analytics {#custom-rtp-dashboards-in-google-universal-analytics}

Custom RTP Dashboards in Google Universal Analytics - Marketo Docs - Product Documentation

### What's in this article? {#what-s-in-this-article}

[Setting up a Custom Dashboard](#customrtpdashboardsingoogleuniversalanalytics-settingupacustomdashboard)  
[RTP B2B Dashboard](#customrtpdashboardsingoogleuniversalanalytics-rtpb2bdashboard)  
[RTP Engagement Dashboard](#customrtpdashboardsingoogleuniversalanalytics-rtpengagementdashboard)

>[!NOTE]
>
>**Prerequisites**
>
>[Integrate RTP with Google Universal Analytics](integrate-rtp-with-google-universal-analytics.md)

This post explains how to setup RTP dashboards in Google Universal Analytics (GUA).  The data sent from RTP to GUA can be set up as two separate custom dashboards called:

* RTP B2B
* RTP Engagement

#### Setting up a Custom Dashboard {#customrtpdashboardsingoogleuniversalanalytics-settingupacustomdashboard}

1. `Login to Google Analytics.` `Click on **Reporting **in the top menu.` `Click **Dashboards **and **+New Custom Dashboard.**`  
   ![](assets/image2015-3-22-16-3a41-3a29.png)

1. `Select **Blank Canvas**, add a **Dashboard Name**` `and c` `lick **Create Dashboard**.`

1. ` Click **Add Widget** to create a new widget.`  
   ` ![](assets/image2015-3-22-16-3a46-3a48.png)

   `

#### RTP B2B Dashboard {#customrtpdashboardsingoogleuniversalanalytics-rtpb2bdashboard}

This dashboard allows users to analyze their website performance from a B2B perspective.

It provides information like visit source and onsite behavior by industry, revenue, size, Account-Based lists, and target segments.

The dashboard consists of 3 columns

* Traffic source
* Segmentation
* Firmographic drill down

1. Create a new dashboard called **RTP B2B Dashboard **and define the following widgets:

![](assets/image2015-3-22-16-3a50-3a3.png)

<table class="confluenceTable"> 
 <thead> 
  <tr style="margin-left: 30.0px;"> 
   <th> 
    <div class="tablesorter-header-inner">
      Column 1 - Traffic Sources 
    </div></th> 
   <th> 
    <div class="tablesorter-header-inner"> <strong>Column 2 - Segmentation</strong> 
    </div></th> 
   <th> 
    <div class="tablesorter-header-inner"> <strong>Column 3 - Firmographic Drill down</strong> 
    </div></th> 
  </tr> 
 </thead> 
 <tbody style="margin-left: 30.0px;"> 
  <tr style="margin-left: 30.0px;"> 
   <td> 
    <ul style="margin-left: 0.0px;"> 
     <li>Name: Sessions by Segments and Channels</li> 
     <li><span style="color: rgb(0,0,0);">Widget type: Bar</span><span style="color: rgb(0,0,0);"><br></span></li> 
     <li><span style="color: rgb(0,0,0);">Create a bar chart showing: Session</span></li> 
     <li>Grouped by: Event label</li> 
     <li>Pivot by: Default Channel Grouping</li> 
     <li>Filter: <br>Only Show | Event Category (containing) RTP-Segments</li> 
    </ul><p><img class="confluence-embedded-image confluence-thumbnail" width="300" src="assets/image2015-3-23-11-3a32-3a13.png" data-linked-resource-id="7504247" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></td> 
   <td> 
    <ul style="margin-left: 0.0px;"> 
     <li>Name: # of RTP Segmented Users</li> 
     <li>Type: 2.1 Metric</li> 
     <li><span style="color: rgb(0,0,0);">Show the following metric: Users</span><span style="color: rgb(0,0,0);"><br></span></li> 
     <li>Filter: <br>Only Show | Event Category (containing) RTP-Segments</li> 
    </ul><p><img class="confluence-embedded-image" width="350" src="assets/image2015-3-23-11-3a33-3a6.png" data-linked-resource-id="7504249" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></td> 
   <td> 
    <ul style="margin-left: 0.0px;"> 
     <li>Name: Sessions by Industry</li> 
     <li>Type: Pie<span style="color: rgb(0,0,0);"><br></span></li> 
     <li><span style="color: rgb(0,0,0);">Create a pie chart showing: Sessions</span></li> 
     <li><span style="color: rgb(0,0,0);">Grouped by: RTP-Industry</span></li> 
    </ul><p><img class="confluence-embedded-image" width="350" src="assets/image2015-3-23-11-3a33-3a27.png" data-linked-resource-id="7504250" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></td> 
  </tr> 
  <tr style="margin-left: 30.0px;"> 
   <th> 
    <ul style="margin-left: 0.0px;"> 
     <li><strong>Name: Sessions by Industry and Channels</strong></li> 
     <li><strong><span style="color: rgb(0,0,0);">Widget type: Bar</span><span style="color: rgb(0,0,0);"><br></span></strong></li> 
     <li><strong><span style="color: rgb(0,0,0);">Create a bar chart showing: Session</span></strong></li> 
     <li><strong>Grouped by: RTP-Industry</strong></li> 
     <li><strong>Pivot by: Default Channel Grouping</strong><br><img class="confluence-embedded-image confluence-thumbnail" width="300" src="assets/image2015-3-23-11-3a33-3a52.png" data-linked-resource-id="7504252" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></li> 
    </ul></th> 
   <th> 
    <ul style="margin-left: 0.0px;"> 
     <li><strong>Name: Segmented Sessions by Country</strong></li> 
     <li><strong>Type: Geomap<span style="color: rgb(0,0,0);"><br></span></strong></li> 
     <li><strong><span style="color: rgb(0,0,0);">Plot selected metric: Country | Sessions</span></strong></li> 
     <li><strong><span style="color: rgb(0,0,0);">Select a region: The World</span></strong></li> 
     <li><strong>Filter: Only Show | Event Category (containing) RTP-Segments</strong></li> 
    </ul><p><img class="confluence-embedded-image" width="350" src="assets/image2015-3-23-11-3a34-3a18.png" data-linked-resource-id="7504253" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></th> 
   <th> 
    <ul style="margin-left: 0.0px;"> 
     <li><strong>Name: Sessions by RTP Category</strong></li> 
     <li><strong>Type: Pie<span style="color: rgb(0,0,0);"><br></span></strong></li> 
     <li><strong><span style="color: rgb(0,0,0);">Create a pie chart showing: Sessions</span></strong></li> 
     <li><strong><span style="color: rgb(0,0,0);">Grouped by: RTP-Category</span></strong></li> 
    </ul><p><img class="confluence-embedded-image" width="350" src="assets/image2015-3-23-11-3a35-3a1.png" data-linked-resource-id="7504254" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></th> 
  </tr> 
  <tr style="margin-left: 30.0px;"> 
   <th> </th> 
   <th> 
    <ul style="margin-left: 0.0px;"> 
     <li>Name: Top Target Segments</li> 
     <li>Type: Bar</li> 
     <li><span style="color: rgb(0,0,0);">Create a bar chart showing: Users</span></li> 
     <li><span style="color: rgb(0,0,0);">Grouped by: Event Action</span></li> 
     <li>Filter: Only Show | Event Category (containing) RTP-Segments</li> 
    </ul><p><img class="confluence-embedded-image" width="350" src="assets/add-a-widget.png" data-linked-resource-id="11382874" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></th> 
   <th> 
    <ul style="margin-left: 0.0px;"> 
     <li>Name: Sessions by RTP-Groups</li> 
     <li>Type: Bar<span style="color: rgb(0,0,0);"><br></span></li> 
     <li><span style="color: rgb(0,0,0);">Create a bar chart showing: Sessions</span></li> 
     <li><span style="color: rgb(0,0,0);">Grouped by: RTP-Group</span></li> 
    </ul><p><strong><img class="confluence-embedded-image" width="350" src="assets/image2015-3-23-11-3a35-3a54.png" data-linked-resource-id="7504256" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></strong></p></th> 
  </tr> 
  <tr style="margin-left: 30.0px;"> 
   <th> </th> 
   <th> 
    <ul style="margin-left: 0.0px;"> 
     <li>Name: Sessions &amp; Goals by Top Segments</li> 
     <li>Type: Table<span style="color: rgb(0,0,0);"><br></span></li> 
     <li><span style="color: rgb(0,0,0);">Display the following columns: </span><br><span style="color: rgb(0,0,0);">Event Label | Sessions | Goal Conversion Rate</span></li> 
     <li>Filter: <br>Only Show | Event Category (containing) RTP-Segments</li> 
    </ul><p><strong><img class="confluence-embedded-image" width="350" src="assets/image2015-3-23-11-3a36-3a15.png" data-linked-resource-id="7504257" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></strong></p></th> 
   <th> </th> 
  </tr> 
 </tbody> 
</table>

#### RTP Engagement Dashboard {#customrtpdashboardsingoogleuniversalanalytics-rtpengagementdashboard}

This dashboard allows users to analyze their RTP campaign performance and recommendation engine engagements. It provides comparison of avg. session duration and pages per session between:

*

    * Unengaged
    * Engaged (impressions and clicks on a personalized campaign)
    * Clicks on the Recommendation Engine and top recommended content

Create a new dashboard called **RTP Engagement Dashboard** and define the following widgets:

![](assets/image2015-3-22-17-3a7-3a19.png)

<table class="confluenceTable"> 
 <thead> 
  <tr> 
   <th> 
    <div class="tablesorter-header-inner"> <strong>Column 1 Campaigns Exposure</strong> 
    </div></th> 
   <th> 
    <div class="tablesorter-header-inner"> <strong>Column 2 Campaigns Clickthrough</strong> 
    </div></th> 
   <th> 
    <div class="tablesorter-header-inner"> <strong>Column 3 Recommendation Engine</strong> 
    </div></th> 
  </tr> 
 </thead> 
 <tbody> 
  <tr> 
   <td> 
    <ul style="margin-left: 0.0px;"> 
     <li>Name: <strong>Total CTA (Engagement)</strong></li> 
     <li>Type: <strong>2.1 Metric </strong></li> 
     <li><span style="color: rgb(0,0,0);">Show the following metric: <strong>Total Events</strong></span></li> 
     <li><span style="color: rgb(0,0,0);">Filters:</span><br><strong>[only show] Event Category (contains): RTP-Campaigns</strong><br><strong>[only show] Event Action (exactly matcing): Impression</strong><strong>[don't show] Event Label (containing): #</strong></li> 
    </ul><p><strong><img class="confluence-embedded-image" width="350" src="assets/image2015-3-23-11-3a37-3a55.png" data-linked-resource-id="7504259" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></strong></p></td> 
   <td> 
    <ul style="margin-left: 0.0px;"> 
     <li>Name: <strong>Total CTA (Clickthrough)</strong></li> 
     <li>Type: <strong>2.1 Metric </strong></li> 
     <li><span style="color: rgb(0,0,0);">Show the following metric: <strong>Total Events</strong></span></li> 
     <li><span style="color: rgb(0,0,0);">Filters:</span><br><strong>[only show] Event Category (contains): RTP-Campaigns</strong><br><strong>[only show] Event Action (exactly matching): Clicks</strong><strong>[don't show] Event Label (containing): #</strong></li> 
    </ul><p><strong><img class="confluence-embedded-image" width="350" src="assets/image2015-3-23-11-3a38-3a12.png" data-linked-resource-id="7504261" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></strong></p></td> 
   <td> 
    <ul style="margin-left: 0.0px;"> 
     <li>Name: <strong>CRE - Total Clicks</strong></li> 
     <li>Type: <strong>2.1 Metric</strong><span style="color: rgb(0,0,0);"><br></span></li> 
     <li><span style="color: rgb(0,0,0);">Show the following metric: <strong>Pageviews</strong></span></li> 
     <li><span>Filter: <strong><span style="color: rgb(0,0,0);">[only show] Page (containing): rcmd</span></strong></span></li> 
    </ul><p><img class="confluence-embedded-image" width="350" src="assets/image2015-3-23-11-3a38-3a30.png" data-linked-resource-id="7504262" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></td> 
  </tr> 
  <tr> 
   <td colspan="1"> 
    <ul> 
     <li>Name: <strong>Avg. Session Duration (Engagement)</strong></li> 
     <li>Type: <strong>2.1 Metric </strong></li> 
     <li><span style="color: rgb(0,0,0);">Show the following metric: <strong>Avg. Session Duration</strong></span></li> 
     <li><span style="color: rgb(0,0,0);">Filters:</span><br><strong>[only show] Event Category (exactly matching): RTP-Campaigns</strong><br><strong>[only show] Event Action (exactly matching): impression</strong><strong>[don't show] Event Label (containing): #</strong></li> 
    </ul><p><strong><img class="confluence-embedded-image" width="350" src="assets/image2015-3-23-11-3a41-3a21.png" data-linked-resource-id="7504264" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></strong></p></td> 
   <td colspan="1"> 
    <ul> 
     <li>Name: <strong>Avg. Session Duration (Clickthrough)</strong></li> 
     <li>Type: <strong>2.1 Metric </strong></li> 
     <li><span style="color: rgb(0,0,0);">Show the following metric: <strong>Avg. Session Duration</strong></span></li> 
     <li><span style="color: rgb(0,0,0);">Filters:</span><br><strong>[only show] Event Category (exactly matching): RTP-Campaigns</strong><br><strong>[only show] Event Action (exactly matching): clicks</strong><strong>[don't show] Event Label (containing): #</strong></li> 
    </ul><p><strong><img class="confluence-embedded-image" width="350" src="assets/image2015-3-23-11-3a41-3a37.png" data-linked-resource-id="7504265" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></strong></p></td> 
   <td colspan="1"> 
    <ul> 
     <li>Name: <strong>CRE - Top Recommended Content</strong></li> 
     <li>Type: <strong>Table</strong><span style="color: rgb(0,0,0);"><br></span></li> 
     <li><span style="color: rgb(0,0,0);">Display the following columns: </span><br><strong><span style="color: rgb(0,0,0);">Page Title | Pageviews</span></strong><span style="color: rgb(0,0,0);"><br></span></li> 
     <li><span style="color: rgb(0,0,0);">Filters:</span><br><span style="color: rgb(0,0,0);">Filter: </span><strong><span style="color: rgb(0,0,0);">[only show] Page (containing): rcmd</span></strong></li> 
    </ul><p><img class="confluence-embedded-image" width="350" src="assets/image2015-3-23-11-3a41-3a51.png" data-linked-resource-id="7504266" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></td> 
  </tr> 
  <tr> 
   <td> 
    <ul style="margin-left: 0.0px;"> 
     <li>Name: <strong>Pages / Session (Engagement)</strong></li> 
     <li>Type: <strong>2.1 Metric </strong></li> 
     <li><span style="color: rgb(0,0,0);">Show the following metric: <strong>Pages / Session</strong></span></li> 
     <li><span style="color: rgb(0,0,0);">Filters:</span><br><strong>[only show] Event Category (exactly matching): RTP-Campaigns</strong></li> 
     <li><strong>[only show] Event Action (exactly matching): impression</strong></li> 
     <li><strong>[don't show] Event Label (containing): #</strong></li> 
    </ul><p><img class="confluence-embedded-image" width="350" src="assets/image2015-3-23-11-3a42-3a10.png" data-linked-resource-id="7504267" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></td> 
   <td> 
    <ul style="margin-left: 0.0px;"> 
     <li>Name: <strong>Pages / Session (Clickthrough)</strong></li> 
     <li>Type: <strong>2.1 Metric </strong></li> 
     <li><span style="color: rgb(0,0,0);">Show the following metric: <strong>Pages / Session</strong></span></li> 
     <li><span style="color: rgb(0,0,0);">Filters:</span><br><strong>[only show] Event Category (exactly matching): RTP-Campaigns</strong></li> 
     <li><strong>[only show] Event Action (exactly matching): clicks</strong></li> 
     <li><strong>[don't show] Event Label (containing): #</strong></li> 
    </ul><p><strong><img class="confluence-embedded-image" width="350" src="assets/image2015-3-23-11-3a42-3a32.png" data-linked-resource-id="7504268" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></strong></p></td> 
   <td> </td> 
  </tr> 
  <tr> 
   <td> 
    <ul style="margin-left: 0.0px;"> 
     <li>Name: <strong>Impressions by CTA</strong></li> 
     <li>Type: <strong>Table</strong></li> 
     <li><span style="color: rgb(0,0,0);">Display the following columns: <strong>Event Label | Total Events | Users</strong></span></li> 
     <li><span style="color: rgb(0,0,0);">Filters:</span><br><strong>[only show] Event Category (exactly matching): RTP-Campaigns</strong><br><strong>[only show] Event Action (exactly matching): impression</strong><strong>[don't show] Event Label (containing): #</strong></li> 
    </ul><p><img class="confluence-embedded-image" width="350" src="assets/image2015-3-23-11-3a42-3a48.png" data-linked-resource-id="7504269" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></td> 
   <td> 
    <ul style="margin-left: 0.0px;"> 
     <li>Name: <strong>Clickthrough by CTA</strong></li> 
     <li>Type: <strong>Table</strong></li> 
     <li><span style="color: rgb(0,0,0);">Display the following columns: <strong>Event Label | Total Events | Users</strong></span></li> 
     <li><span style="color: rgb(0,0,0);">Filters:</span><br><strong>[only show] Event Category (exactly matching): RTP-Campaigns</strong><br><strong>[only show] Event Action (exactly matching): clicks</strong></li> 
    </ul><p><img class="confluence-embedded-image" width="350" src="assets/image2015-3-23-11-3a43-3a4.png" data-linked-resource-id="7504270" data-linked-resource-type="attachment" data-base-url="https://docs.marketo.com" data-linked-resource-container-id="7504238"></p></td> 
   <td> </td> 
  </tr> 
 </tbody> 
</table>

>[!NOTE]
>
>**Related Articles**
>
>[Integrate RTP with Google Universal Analytics](integrate-rtp-with-google-universal-analytics.md)
>
>[Custom RTP Reports in Google Universal Analytics](custom-rtp-reports-in-google-universal-analytics.md)
