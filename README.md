# Risk-Analysis-Report-for-All-for-5-dollars-Store
# Executive Summary:

Upon request from company owner concerning the hacking of card reader machines similar to ATMs, I conducted a full risk analysis on the point-of-sale card readers for a 50-year-old business called All for $5 Stores LTD.

I brainstormed and asked questions concerning these inputs: What do I know at this point? What are the assets, threat communities, and loss events? What are the anticipated threat paths? How frequently would the threats occur? How vulnerable is the company to these threats? And What data do I have currently and is it objective for our purposes?
These questions pointed us in the right direction to conduct the risk analysis.

My approach was to use the risk analysis using the FAIR Basic Risk Assessment Methodology. This was broken down into two stages. 
Stage 1: Scoping the analysis, which included identifying the asset at risk, threat communities under investigation, and defining the loss event. 
stage 2: Encompassing evaluate Loss Event Frequency, Estimate Contact Frequency, Estimate Probability of Action, Estimate Threat Event Frequency, Estimate Threat Capability, Estimate Resistance Strength, Vulnerability and Loss Event Frequency.

The assessment results showed the estimated minimum and maximum total loss amounts over a year, which ranged from $60,000 to $19.6 million. This is what the company could experience based on the current risk exposure. 

A Loss Exceedance Curve visually shows that the more the loss exposure is or how much All for $5 Stores is vulnerable, the greater the possibility of loss is. 

The company currently has 97.08% vulnerability based on the data given. 

# Business Problem:
The company keeps costs down by allowing a contractor to maintain the store equipment but I saw, this also opens up the door for non-invested intentions. Notably, the video surveillance is not robust with the records only keeping for one month time and reused every 30 days and could miss a device retrieval. However, the company prides itself on being well trained in loss prevention and working with local police on these matters.

Upon request from the company owner concerning the hacking of store machines similar to ATMs, I have conducted a full risk analysis on the point-of-sale card readers since it appeared after looking at loss prevention, most of the occurrences happened by shoplifting and bad checks. These can be a steady drain of cash flow and consistently hurt the company revenues. The owner is concerned about the negative publicity that data breaches can have and since All for $5 Stores is heavily involved with the local chamber of commerce and community, they want to keep the company reputation strong. I looked specifically at ATM skimmers, which sit on top of the card readers undetected and absorb data for some time, only to be retrieved later and used or sold for exploitation. I pulled together data provided by All for $5 Stores and ran a FAIR risk analysis to provide an estimate of how often and how much the company may be exposed to this form of loss.

# Methodology:
Stage 1: Scoping the analysis
  o Identify the asset at risk
  o Identify the threat communities under investigation
  o Define the loss event

Stage 2: Evaluate Loss Event Frequency (LEF)
  o Estimate Contact Frequency (CF)
  o Estimate Probability of Action (PoA)
  o Estimate Threat Event Frequency (TEF)
  o Estimate Threat Capability (TCap)
  o Estimate Resistance Strength (RS)
  o From the above measures, we can find Vulnerability (Vuln) and Loss Event Frequency (LEF)

# Skills:
FAIR analysis tool

------------------------------------------

# Results and Recommendations:
The three algorithms utilized showed different results:

Apriori algorithm showed poor results with support being low around 37% through testing the three district areas to see if there were association rules but did show higher-end confidence, showing a leaning towards only specific data.

<img width="840" height="148" alt="image" src="https://github.com/user-attachments/assets/e6673fab-b7ce-4787-aaf9-b31dd7580642" />

Naïve-Bayes tests pulled the following performance results in predicting arrests. They were not as high as I would have hoped but considering the size and variety of the data, this is possible.

<img width="537" height="240" alt="Naive Bayes" src="https://github.com/user-attachments/assets/9e7e3029-675f-4d6d-a906-beb3f764add1" />

Decision tree model pulled better performance than the Naïve-Bayes. I look at the error rate being only 11% compared to the 33 and 34%. The false-positive rate is much lower showing the decision tree almost unwilling to make a positive arrest identifier.

<img width="313" height="240" alt="Decision tree" src="https://github.com/user-attachments/assets/7d3274e5-8570-4579-90cd-06a2dcb33644" />

# Next Steps:
1. 
2. 
3. 



