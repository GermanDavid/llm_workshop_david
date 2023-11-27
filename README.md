# llm_workshop_david
**My first attempt:** 
Given your chatgpt_ask function's design, it returns a function (pandas_func) that is to be applied to a pandas DataFrame. To modify the code such that the response to a yes/no question is boolean (True or False), I add an additional step to process the output of chatgpt_ask.\\
Here's how I  do it:\\
- Apply the chatgpt_ask function: First, use the chatgpt_ask function to get 'yes'/'no' answers.
- Convert the Responses to Boolean: After getting the responses, convert them from 'yes'/'no' to boolean values.\\


**My second (and final) attempt:** 
I ensure that the chatgpt_ask function directly returns a boolean response based on a yes/no question, so I modify the chatgpt_ask function itself. This change will make the function more versatile and allow me to use it directly with df.apply without needing additional steps to convert the responses.
