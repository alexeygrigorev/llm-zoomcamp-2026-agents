agent 

- has intructions
- has tools 
- has memory 


history

1. make a call to the LLM <-- we pay 
2. LLM decided to invoke search('params')
3. We invoke the search, we have the results
4. Send the results back to the LLM (another call) <-- we pay again
5. LLM processes the results
6. LLM gives the answer

2 requests sent to the LLM 


1. make a call to the LLM <-- we pay 
2. LLM decided to invoke search('params')
3. We invoke the search, we have the results
4. Send the results back to the LLM (another call) <-- we pay again
5. LLM processes the results
6. LLM decides to make another tool call
7. Send one more API request <-- 
8. Process and gives the answer

