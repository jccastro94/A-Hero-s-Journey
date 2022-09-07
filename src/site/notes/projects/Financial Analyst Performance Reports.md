---
{"dg-publish":true,"permalink":"/projects/financial-analyst-performance-reports/","dgHomeLink":true,"dgPassFrontmatter":false}
---

Due to compliance and non-disclosure agreements, I will speak of this client as "[[entities/the bank|the bank]]". 

At [[entities/the bank|the bank]], it was necessary to know exactly how each of their research managing directors were doing. If I told you a stock had a price target of $50 in 3 months, and it turned out to be $45, I would still know nothing. It could have gone up from $30, down from $60, or down from $48. Each scenario says a different story for the analyst. 

Although stock performance was a piece, it was not the only piece. Each MD had to record billing hours, separated by caregories such as calls and meetings, as well as report how much resources they were taking out as VPs and other analysts under them and trip costs.

All in all, each performance report was a very detailed, 15 page+ report of a ton of data gathered on them. This was given directly to the Head of Global which in turn reported to the CEO.

## Details
The whole process was divided up in 6 parts, done in about 3 months time.

### 1) Data Gathering
Fortunately for me, most of the gathering was done by other teams. Everything was uploaded to their [[SAP Boxi|SAP]] systems, and I only had to create different queries to gather the data. 
As it happens with old systems in old institutions, the data was never clean, often duplicated elsewhere, without one single correct source. So a big part of the data gathering process was creating queries to get only what was relevant. 

### 2) Data Cleaning
Once the data was downloaded and ready, usually the cleaning was done in Excel. This meant editing and parsing data points, so that we could actually use it on our analysis. Mostly converting text to number, taking out unsupported characters, and making sure columns and rows were as needed.

### 3) Data Normalization
After making sure all the data could be read and processed in excel, we had to ensure it made sense. This means reducing redundancy, finding outliers, and more often then not, requerying the databases to ensure we have the correct values. Big jumps in meeting hours or calls could mean double counting while very low amount of them meant they were not logged. At times, it was necessary to remind the MD to log their hours or to get into the weeds and fidn what was double counted.

### 4) Statistical Analysis
This was my favorite part. We were always trying to figure out the best metrics to measure performance. We also had a set of metrics we always had to give. This step was just a couple of days of using formulas to summarize data and measure performance. The statistical analysis was done on each individual MD to then be able to compare them with their peers and get a perspective of the best and worse performing MDs.

### 5) Report Building
This was the easiest step of all. We had to get the data and put it in [[entities/PowerBI|PowerBI]] dashboards as well as create all sorts of Excel charts and tables. We would include certain notes and comments, and format everything to print. In the end, it was easily a 200 page report, used to give the MDs their performace report and the Head of Global the full picture of how [[entities/the bank|the bank]] was performing. 

### 6) Proof Reading / Review
About 2 weeks were spent ensuring that we had the correct information and that every detail was correct and perfect. The product had to be perfect, without flaw. This report was used to let go MDs at times of restructuring, so it had to be thoroughly vetted before any action was taken on it. 