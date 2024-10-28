# 1. Title: 
Dating apps and what is its impact

# 2. Problem Description
In recent years, there has been a massive rise in the usage of dating apps to find love. Many of these apps use sophisticated data science techniques to recommend possible matches to users and to optimize the user experience. This project analize the data of one of these apps. 
## 2.1 What is the business or policy problem you are facing?
- How the dating apps use the data to macht the future lovers
## 2.2 Who or what is affected by this problem?
- The main affected persons are the users of these apps
## 2.3 How many of these people/organizations/places/etc. are affected by the problem, and how much are they affected
- Any people can be affected because the dataset doesn't have any type of identification than relate the information in the dataset with a person in the real world

# 3. Goals
- Check differentes machine learning models applied to this dataset to verify how to deploy it and what type of results they give us
## 3.1. What are your social, policy, or business goals, and what constraints do you have?
- The main constraint is we don't have a target feature of matching, we would need a trainin dataset with this feature, without this target we can not training our dataset to create a model that can be seek matching among the users in the app

# 4. Data
- **age:** continuous variable of age 
- **body_type:** categorical variable of body type
- **diet:** categorical variable of diet
- **drinks:**  categorical variable of what rutine of drinking have the user
- **drugs:** categorical variable of rutine of consume drugs have the user
- **education:** categorical variable of educational brackground
- **ethnicity:** categorical variable of ethnic 
- **height:** continuous variable of height 
- **income:** continuous variable of income 
- **job:** categorical variable of employment description
- **offspring:** categorical variable of children status
- **orientation:** categorical variable of sexual orientation
- **pets:** categorical variable of pet preferences
- **religion:** categorical variable of religious 
- **sex:** categorical variable of gender
- **sign:** categorical variable of astrological symbol
- **smokes:** categorical variable of the user smokes or not
- **speaks:** categorical variable of language spoken
- **status:** categorical variable of relationship status
- **last_online:** date variable of last login
- **location:** categorical variable of user city and state

# 5. Analysis
- Univariate analisys: analize al the features identifying the type variable (categorical or numerical)
- Transform the data
    - Merging some values
    - Creating new values
- Identifying the missing values and deciding the missing type (MCAR, MAR, MNAR)
    - Applying differents techinques to manage the missing values
- Select the best features to success in the model implementation
- Convert categorical variables in numerical ussing the dummies technique
- We apply two classification models: Deccision trees and k-neigbors
- Evaluate de models

# 6. Ethical Considerations
- This project has an educational porpuse and doesn't exist any ethical consideration to take into consideration

## 6.1 Privacy, Confidentiality, Transparency, Discrimination/Equity and Security
The dataset has been downloaded from CodeAcademy platform. 
