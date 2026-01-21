---
title: "Accessing Statistics Canada’s Socioeconomic Time Series Data (formerly CANSIM)"
layout: "home"
description: ""
permalink: "/"  #! Remove this if not the homepage
---

# Accessing Statistics Canada’s Socioeconomic Time Series Data (formerly CANSIM)

This guide is primarily designed to help users unfamiliar with the CANSIM database find and download data.

Note: This guide outlines how to search for CANSIM data on the Statistics Canada website. University of Toronto faculty, staff, and students may also [download CANSIM series for free via CHASS](http://mdl.library.utoronto.ca/technology/tutorials/accessing-cansim-data-though-chass). You will need to be using a UofT IP address to access CHASS.

**1\. Getting Started**

***a.***This tutorial covers how to search and retrieve data from Statistics Canada’s main socioeconomic time series database. The site contains most of the aggregate data collected by Statistics Canada on a regular basis such as data from the Consumer Price Index Survey, the Labour Force Survey, or the National Income and Expenditure accounts.

**NOTE:** The data on this site was previously referred to as **CANSIM** data.

***b. How to access the data:***

Access the data by going to the [Statistics Canada Website](https://www.statcan.gc.ca/eng/start), and selecting *Access our Data*.

<img src='{{ '/assets/images/AccessStatsCanNew1.jpg' | relative_url }}' alt='"Click on 'Access our Data' after opening Statistics Canada's home page"' title='' width='1109' height='1176' />

**2\. Searching for Data**

***a. Classification***

Data are classified by tables and series. A table is the largest unit and contains many series. For instance, there are over 300 tables from the Labour Force Survey. One of these is called *Unemployment rate, participation rate and employment rate by educational attainment, annual*” (Table 14\-10\-0020\-01\) and contains over 26 000 series. A series is, for instance, the full\-time employment of male teachers and professors in Canada from 1987\-2015 (series v2369249\).

***b. Searching by survey, table, or series number***

If you have the name or number of a survey, table, or series, you can easily retrieve the series by typing the information in the search menu.

***c. Searching by subject or keywords***

Statistics Canada’s interface allow the user to search for series by subject or keywords. However, unless you know the exact name of the series you are looking for, it is usually better to search by subject in the first stage because the concept we have in mind may not be in the title of the right table or series. For instance, to find the CPI\-based inflation rate, it is natural to type “inflation” as a keyword. However, this does not return the desired result, because the inflation rate is not by itself a series, but can easily be constructed from the consumer price index.

Suppose we want to find the quarterly Canadian CPI\-based inflation rate for the period 2017\-2022\.

I. From the page that you are currently on, we can see a list by subject down the left side.

II. From the list, choose *Prices and price indexes* (there are 461 tables on prices and price indexes). The link redirects us to a more precise list of topics. You will notice that, along the top of the results list, you can view all results, data tables, community and/or regional profiles, maps, microdata, and various data visualizations.

<img src='{{ '/assets/images/AccessStatsCanNew2.jpg' | relative_url }}' alt='' title='' width='986' height='1169' />

III. Since we are interested in the tables for the Consumer Price Index (CPI) statistics, select*Consumer price indexes,*then select the Tables tab.

<img src='{{ '/assets/images/AccessStatsCanNew3.jpg' | relative_url }}' alt='' title='' width='1094' height='806' />

IV. Then, scroll down to the bottom of the page, navigate to Page 3, and the third item down the tables list is the one that we are after, so we simply select that one to open the CPI table. This table is called *'Consumer Price Index (CPI) statistics, alternative measures, unadjusted and seasonally adjusted, Bank of Canada'*

NOTE: to those familiar with Statistics Canada's old CANSIM tables, notice that, where applicable, the website refers to a CANSIM number for the table. In the case of this particular CPI statistics table, the old CANSIM number was*176\-0003\.*

<img src='{{ '/assets/images/AccessStatsCanNew4.jpg' | relative_url }}' alt='' title='' width='936' height='1274' />

**3\. Playing with Data**

We have opened the table for “Consumer Price Index (CPI) statistics, alternative measures, unadjusted and seasonally adjusted, Bank of Canada.” The table will cover numerous years, and covers both the index itself and an inverse percentage value on a month\-to\-month basis, with the most recent few months displayed. We are are interested in finding the quarterly inflation rate for Canada from 2017 to 2022\.

By default, all the active series in the table are selected. So, to choose which series to download, select*Add/Remove data*.

1. Select *Geography*. The series are only available for all Canada. We have nothing to do.
2. Select *Alternative measures*. Different measures of the CPI are available and some series are not collected anymore (indicated by **(Terminated)**). Since we are interested in the simple inflation rate, select the series *Consumer Price Index (CPI) excluding food, energy and the effect of indirect taxes, seasonally adjusted*. Deselect any others and hit *Apply.*
3. Input the time frame by clicking on *Reference period*, selecting from January 2017 to January 2022, then hit *Apply*. Immediately, we are seeing the resulting CPI data, ranging from Jan. 2017 through Jan. 2022\.

<img src='{{ '/assets/images/AccessStatsCanNew5.jpg' | relative_url }}' alt='' title='' width='1163' height='775' />

 

<img src='{{ '/assets/images/AccessStatsCanNew6.jpg' | relative_url }}' alt='' title='' width='1075' height='715' />

 

<img src='{{ '/assets/images/AccessStatsCanNew7.jpg' | relative_url }}' alt='' title='' width='957' height='617' />

 

**4\. Downloading Data**

After confirming that the data you want to retrieve has been added to the display, click on *Download options* to save it as a CSV file.

<img src='{{ '/assets/images/AccessStatsCanNew10.jpg' | relative_url }}' alt='' title='' width='1289' height='1259' />

 

Then click on the first option: *CSV, download as displayed*. You can also choose other formats, but the first option is straightforward and downloads the selected data and any metadata into the same CSV file.

<img src='{{ '/assets/images/AccessStatsCanNew9.jpg' | relative_url }}' alt='' title='' width='1187' height='1261' />

That concludes this brief guide on downloading CANSIM data from Statistics Canada's website. If you have any questions regarding the guide, or would like some help with finding and downloading Statistics Canada data, please feel free to reach out to the Map and Data Library. Our contact form can be found [here](https://mdl.library.utoronto.ca/about/contact-form).

[https://mdl.library.utoronto.ca/about/contact\-form\&nbsp](https://mdl.library.utoronto.ca/about/contact-form&nbsp);

 

 

Technique: [Searching for maps and data](/technique/searching-maps-and-data)**Date Created:** 2017\-05\-05**Updated:** 2022\-04\-26
