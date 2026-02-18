# Data Sources for Trump 2016 Primary Analysis

## Primary Microdata Sources

### 1. ANES 2016 Time Series Study
- **URL**: https://electionstudies.org/data-center/2016-time-series-study/
- **N**: 4,271 (1,181 face-to-face + 3,090 internet)
- **Key variables**:
  - `V161021a`: Primary vote choice (5=Trump, 6=Cruz, 7=Rubio, 8=Kasich)
  - `V161021x`: Which party's primary R voted in
  - `V161004`: How often R votes (1=always to 4=seldom)
  - `V161005`: Whether R voted in 2012
  - `V161006`: 2012 vote choice (1=Obama, 2=Romney)
  - `V161215`: Trust in government (cynicism measure)
  - `V161216`: External efficacy (inefficacy measure)
- **Strengths**: Gold standard election survey, tracks prior voting, has alienation measures
- **Limitations**: Small N for primary-specific analysis; primary voters are a subset

### 2. CCES/CES 2016 (Cooperative Election Study)
- **URL**: https://cces.gov.harvard.edu/
- **N**: ~64,600
- **Key variables**:
  - `CC16_320`: Voted in presidential primary (yes/no)
  - `CC16_321`: Primary vote choice
  - `newsint`: Political interest/attention
  - `votereg`: Voter registration status
- **Strengths**: Massive sample allows subgroup analysis; political interest variable
- **Limitations**: Less rich on alienation measures than ANES

### 3. Democracy Fund VOTER Survey (Views of the Electorate Research)
- **URL**: https://www.voterstudygroup.org/
- **N**: 8,000 (longitudinal panel from 2011-2012-2016)
- **Key finding**: Identified five types of Trump voters, tracked partisan shifts
- **Strengths**: Longitudinal — can observe actual change in the same individuals over time
- **Critical paper**: Ekins (2017), "The Five Types of Trump Voters"

## Exit Poll Data

### 4. CNN/Edison Research Primary Exit Polls
- **URL**: https://www.cnn.com/election/2016/primaries/polls
- **Crosstab**: "First time voting in a Republican primary"
- **Key states with data**: NH, SC, FL, and most Super Tuesday+ states
- **NH finding**: 15% first-timers, 38% of whom backed Trump

## Key Academic Papers

### On Political Alienation and Trump
- Kal (2024). "Political Alienation and the Trump Vote in the 2016 and 2020 US Presidential Elections." *Public Opinion Quarterly*, 88(1), 1-28.
  - https://academic.oup.com/poq/article/88/1/1/7636367
  - Replication data: https://osf.io/4j398/

### On Conversion vs. Mobilization
- Grimmer et al. (2021). "How Voter Conversion and Turnout Change Contributed to the Republican Victories in 2016 and 2020." *Science Advances*.
  - Press: https://news.yale.edu/2021/04/21/swing-vote-trumped-turnout-2016-election

### On Pathways to Trump
- Reny, Collingwood & Valenzuela (2019). "Pathways to Trump: Republican Voters in 2016." *Electoral Studies*, 61.
  - https://www.sciencedirect.com/science/article/abs/pii/S0261379418303032

### On the White Working Class
- Carnes & Lupu (2021). "The White Working Class and the 2016 Election." *Perspectives on Politics*.
  - https://noamlupu.com/Carnes_Lupu_WWC.pdf
