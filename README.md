**What factors help predict whether or not a job posting is fraudulent?**
In this project, we analyze a data set of real and fake job postings to build a model to predict whether or not a posting is fake.

**With our data set, we answered the following questions:**
- How does missing data affect the fraudulence of a job?
- How does word count in the job and company descriptions affect the fraudulence of a job?
- How can we utilize these findings to build a predictive model?
**From our analysis and models, we conclude that:**
- Missing data in a job posting does not significantly contribute to whether or not it is fraudulent, unless there are 11+ missing columns
- Whether or not a job has a company logo was the single column with the highest correlation to whether or not a job was fraudulent
- The combination of columns that creates the best predictive model is the count of words in the description, the count of words in the company profile, whether the posting has a salary range, whether it shows employment type, and the department listed
