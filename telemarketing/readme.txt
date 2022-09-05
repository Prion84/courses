CONNECT SALES FILES WITH CONNECTION LOGS IN THE SYSTEM

Stack: python (pandas, os)

Task: prepare dataframe fitted the listed requirements:
1. Telemarketers do not always indicate the full id, if 'id' is not at the beginning of SUBS_ID, then add it
2. Fields in files can be located absolutely randomly, but field names are static
3. The sale is not counted if disconnection (END_DTTM) occurs less than 5 minutes after connection (START_DTTM)
4. If there is a line in the sales file without the specified SUBS_ID, it is skipped
5. Save the result to a delimited dataframe containing the correct connections.
6. To check the results, enter the SUBS_ID from the received dataset in ascending order, separated by commas with a space