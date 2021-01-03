# Telecom-Company 
The datasets contain data on the use of the virtual telephony service CallMeMaybe. Its clients are organizations that need to distribute large numbers of incoming calls among various operators, or make outgoing calls through their operators. Operators can also make internal calls to communicate with one another. These calls go through CallMeMaybe's network.

### Goal:
Give supervisors information on the least effective operators.

### Specify details:
Identify operators that have:
- A large number of missed incoming calls (internal and external).
- A long waiting time for incoming calls. 
- A small number of attempts to make a call.

### Mandatory stages of analysis:

- <u> Data preprocessing </u>
- <u>  EDA </u>
- <u> Define effective & ineffective operators </u>
- <u> Test statistical hypotheses </u>

### Datasets:
The dataset `telecom_dataset_us.csv` contains the following columns:

- `user_id` — client account ID
- `date` — date the statistics were retrieved
- `direction` — call direction (`out` for outgoing, `in` for incoming)
- `internal` — whether the call was internal (between a client's operators)
- `operator_id` — operator identifier
- `is_missed_call` — whether the call was missed
- `calls_count` — number of calls
- `call_duration` — call duration (excluding waiting time)
- `total_call_duration` — call duration (including waiting time)


The dataset `telecom_clients_us.csv` has the following columns:

- `user_id`
- `tariff_plan` — client's current plan
- `date_start` — client's registration date

## Link to Presentation <a href="https://drive.google.com/file/d/1S6UsYyt30D7H4Lwqzy_HsxKT_BzJdir_/view?usp=sharing"> Here </a>
## Link to Tableau dashboard  <a href="https://public.tableau.com/profile/ron.sherwi#!/vizhome/OperatorsBehavior/Dashboard?publish=yes"> Here </a>
