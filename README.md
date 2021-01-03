# Telecom-Company 
## Give supervisors information on the least effective operators
### Description of the data:
The datasets contain data on the use of the virtual telephony service CallMeMaybe. Its clients are organizations that need to distribute large numbers of incoming calls among various operators, or make outgoing calls through their operators. Operators can also make internal calls to communicate with one another. These calls go through CallMeMaybe's network.

### Goal:
Give supervisors information on the least effective operators.

### Specify details:
Identify operators that have:
- A large number of missed incoming calls (internal and external).
- A long waiting time for incoming calls. 
- A small number of attempts to make a call.

### Propose hypotheses:
- There may be correlation between share of missed incoming calls and long waiting time for incoming calls.
- There may be correlation between share of missed incoming calls and share of outgoing calls.
- There may be a significant difference between the average incoming calls waiting time of effective and ineffective operators.
- There may be a significant difference between the proportions of missed incoming calls of effective and ineffective operators.
- There may be a significant difference between the means of each plan.

### Mandatory stages of analysis:

- <u> Data preprocessing: </u>
    - Study missing values
    - Study duplicate values
    - Check the correctness of column names
    - Rename the columns
    - Remove duplicates
    - Convert types
    - Replace missing values
- <u>  EDA: </u>
    - Check distribution of calls & duration.
    - Find outliers - remove or correct.
    - Check correlations between the columns.
- <u> Define effective & ineffective operators: </u>
    - Give a rank for each operator based on something like RFM analysis: 
        - Number of missed incoming calls
        - Waiting time for incoming calls
        - Number of outgoing calls
- <u> Test statistical hypotheses: </u>
    - Difference between the average incoming calls waiting time of effective and ineffective operators.
    - Difference between the proportions of missed incoming calls of effective and ineffective operators. 
    - Difference between the average number of outgoing calls of effective and ineffective operators. 
    
## Link to Presentation <a href="https://drive.google.com/file/d/1S6UsYyt30D7H4Lwqzy_HsxKT_BzJdir_/view?usp=sharing"> Here </a>
## Link to Tableau dashboard  <a href="https://public.tableau.com/profile/ron.sherwi#!/vizhome/OperatorsBehavior/Dashboard?publish=yes"> Here </a>
