# BigData-Cubes

This is a descriptive guide on how to create data cubes with measures,calculations,KPI's and many different characteristics from scratch.

## Prerequisites
-	Visual Studio 2019 (works fine if you already have visual studio 2017)
-	SQL Server Management Studio
-	AdventureWorks 2019 (or 2017 according to the version you have downloaded for the previous 2)

## Description

The data cube is used to represent data (sometimes called facts) along some measure of interest. For example, in OLAP such measures could be the subsidiaries a company has, the products the company offers, and time; in this setup, a fact would be a sales event where a particular product has been sold in a particular subsidiary at a particular time. In satellite image timeseries measures would be Latitude and Longitude coordinates and time; a fact would be a pixel at a given space/time coordinate as taken by the satellite (following some processing that is not of concern here). Even though it is called a cube (and the examples provided above happen to be 3-dimensional for brevity), a data cube generally is a multi-dimensional concept which can be 1-dimensional, 2-dimensional, 3-dimensional, or higher-dimensional. In any case, every dimension represents a separate measure whereas the cells in the cube represent the facts of interest. Sometimes cubes hold only few values with the rest being empty, i.e.: undefined, sometimes most or all cube coordinates hold a cell value. In the first case such data are called sparse, in the second case they are called dense, although there is no hard delineation between both.

Here I preesnt you with the solution of a basic cube made with facts from the AdventureWorks database of Microsoft where 
I have created all the features described in the above textfiles.
Finally I composed a descriptive guide on how to setup all the needed tools and all the steps to create your cube and it's
features!

## Download 

```bash
~$ git clone https://github.com/AristiPap/BigData-Cubes-Tutorial

The links to download the previous prerequisities:

> Visual Studio
https://visualstudio.microsoft.com/

>SQL Server and SQL Server Management Studio 
https://www.microsoft.com/en-us/sql-server/sql-server-downloads 
https://docs.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver15 

> AdventureWorks
https://docs.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver15&tabs=ssms
```
