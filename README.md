# Video Game Sales Market Analysis

## Objective

Identify factors associated with commercial performance and determine which platforms are strategically relevant for 2017 planning.

## Data

16,715 video games released between 1980 and 2016.  
Platform, genre, release year, regional sales (NA, EU, JP, Other), critic score, user score, and ESRB rating.

Global revenue per title computed as total_sales.

## Approach

- Standardize and clean raw data  
- Remove logical duplicates  
- Normalize categorical variables  
- Engineer global revenue feature  
- Analyze release trends over time  
- Estimate platform lifecycle  
- Evaluate revenue concentration by platform  
- Model recent sales trends using linear regression  
- Select commercially relevant platforms active in 2016  

## Results

- 88% of titles were released after 2000.  
- Six platforms account for approximately 63% of total historical revenue.  
- Average platform commercial lifespan is 7.7 years.  
- PS4 and XOne show positive recent sales trends.  
- Legacy high-revenue platforms exhibit declining trajectories.  
- PC shows long-term commercial stability.

## Conclusion

Historical dominance does not imply current relevance.

Platform selection for 2017 must prioritize:

- Recent growth trends  
- Active market presence  
- Lifecycle stage  
- Revenue stability  

PS4, XOne, and PC represent strategically relevant platforms under these criteria.

## Tools

Python, Pandas, NumPy, Matplotlib, Seaborn, SciPy