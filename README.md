# Machine-Learning-from-Scratch
A multimodal traditional process machine learning project originally made for Snowflake. I decided to run it through Google Collab with updates to the structure.

## Original Project Links
To build the original demo project first access the [Quickstart Guide](https://www.snowflake.com/en/developers/guides/first-machine-learning-project/) and download the notebooks [HERE](https://github.com/Snowflake-Labs/snowflake-demo-notebooks/tree/main/First_Machine_Learning_Project) and fork the repository that has the bear dataset [HERE](https://github.com/dataprofessor/bear-dataset/).

Follow the links in the Quickstart Guide to set up your 30 day free trial Snowflake account. And follow the rest of the demo instructions. 

## How I Built Mine
1. Swapped modin with pandas
2. Created a sliding rate limiter to keep within the free tier
3. Implemented Google Collab Secrets for API keys
4. Pulled dataset directly from the github repo
