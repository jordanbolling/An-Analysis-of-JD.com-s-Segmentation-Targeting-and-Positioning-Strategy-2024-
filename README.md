<h1>A Cluster Analysis and Market Positioning Strategy for JD.com based on Survey Data (2024)</h1>

<h2>Description</h2>
This project involved conducting a **data-driven market segmentation and targeting analysis** for **JD.com**, China’s largest domestic e-commerce retailer. The objective was to identify high-value customer segments and develop a refined **market penetration strategy** in response to increasing competition from Alibaba and Amazon. Using **survey data and cluster analysis in R**, the study segmented customers based on demographic, behavioural, and preference variables, enabling JD.com to redesign its digital product retail marketing approach. The project was developed as part of a *Marketing Analytics coursework assignment* and demonstrates practical application of quantitative segmentation methods to strategic decision-making.
<br />

<h2>Dashboard Preview</h2>

[Project PDF](https://github.com/jordanbolling/An-Analysis-of-JD.com-s-Segmentation-Targeting-and-Positioning-Strategy-2024-/blob/main/MA%20Segmentation%20Analysis.pdf)

<h2>Languages and Utilities Used</h2>

- R (cluster analysis, scaling, dendrograms, eigenvalue analysis)
- Secondary research from Forbes, EcommerceDB, HubSpot, and industry reports
  

<h2>Program walk-through:</h2>

#### **Key Objectives**
- **Identify** distinct customer segments within JD.com’s digital retail market using behavioural and demographic data.
- **Determine** the optimal number of market segments through statistical validation.
- **Evaluate** segment attractiveness for JD.com, its strategic partners, and competitors.
- **Select** a primary target segment to support a market penetration strategy.
- **Develop** a clear positioning strategy aligned with JD.com’s technological and partnership strengths.

#### **Project Workflow**
A thousand customers from a select number of Ivy League Varsities completed a questionnaire at a 5% response rate. The following data file was implemented into the survey from which the questionnaire was constructed.

<p align="center">
Variables: <br/>
<img src="https://i.ibb.co/sJKD97SK/Screenshot-2025-12-17-at-16-53-10.png"/>
<br/>
<img src="https://i.ibb.co/sJKD97SK/Screenshot-2025-12-17-at-16-53-10.png"/>
</p>

The survey results were recorded, and a cluster analysis was done on R through the following steps.
• The mean and standard deviation for each column and all the variables were scaled. The results are analysed later.

<p align="center">
<img src="https://i.ibb.co/ymj6jZFF/Screenshot-2025-12-17-at-16-53-46.png"/>
</p>

• Finding the optimal number of clusters through Eigenvalues.

<p align="center">
<img src="https://i.ibb.co/hGBrfkD/Screenshot-2025-12-17-at-16-53-58.png"/>
</p>

It can be determined that the optimal number of clusters is 3 as no significant amount of information is lost.

• Determining cluster size

<p align="center">
<img src="https://i.ibb.co/HTmc0d43/Screenshot-2025-12-17-at-16-54-16.png"/>
</p>

As seen here, clusters 1,2 and 3 have the sizes 220, 321 and 459 respectively.

• Generating a cluster dendrogram by calculating Euclidean distance

<p align="center">
<img src="https://i.ibb.co/twyRHsqx/Screenshot-2025-12-17-at-16-54-31.png"/>
<br/>
Cluster Dendogram: <br/>
<img src="https://i.ibb.co/84RjYBPk/Screenshot-2025-12-17-at-16-54-59.png"/>
</p>

The highlighted boxes show how the 3 clusters are separated out of the 1000 respondents. 

<p align="center">
An output csv file is generated: <br/>
<img src="https://i.ibb.co/9mGrfNb4/Screenshot-2025-12-17-at-16-55-13.png"/>
</p>

This output shows the means of individual of cluster, which is analysed below.

Following the cluster analysis, the characteristics of cluster can now be understood.

<p align="center">
<img src="https://i.ibb.co/m5hfjTb5/Screenshot-2025-12-17-at-16-55-33.png"/>
</p>

Where an Asterix (*) is provided indicates that these numbers are significant in determining the nature of each cluster.

#### **Key Findings**
Three statistically distinct customer segments were identified using cluster analysis, with cluster sizes of 220, 321, and 459 respondents respectively.
- **Cluster 1** (“Loyal tech-savvy undergraduate students”) demonstrated the highest engagement, loyalty, and responsiveness to product attributes such as insurance, warranty policies, and replacement reminders.
- **Cluster 2** (“Busy everyday shoppers”) prioritised convenience and online shopping but showed weaker engagement with advanced product features.
- **Cluster 3** (“Independent, older customers”) exhibited lower loyalty and reduced sensitivity to product support features, despite higher average age and income.
- JD.com’s strongest growth potential lies in deepening engagement with **Cluster 1**, rather than attempting broad, generic market coverage.


#### **Outcome & Strategic Recommendations**
- **Target** the “Loyal tech-savvy undergraduate students” segment: This group shows the highest responsiveness to marketing initiatives and product enhancements, offering superior ROI.
- **Enhance** loyalty mechanisms: Introduce points-based rewards linked to purchases, reviews, and surveys to strengthen retention.
- **Emphasise** authenticity and product reliability: Marketing communications should highlight JD.com’s trusted supply chain, warranty policies, and insurance offerings.
- **Leverage** omnichannel engagement: Improve social media management and personalised digital communications to match evolving consumer expectations.
- **Strengthen** partner value propositions: Targeted segmentation increases the attractiveness of JD.com as a platform for premium and lifestyle brands, reinforcing competitive advantage over Alibaba.
