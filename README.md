# <center> Code Comment Generation <center> 

Automatic code comment generation with ChatGPT and AIPRM.

**You can find the prompt [here](https://app.aiprm.com/prompts/1802303337228656640 )** 

**Note :** You need the `AIPRM for ChatGPT` extension on your browser.
  
## How it works: 
Copy-paste the code you want to comment on. You receive as output the commented code in markdown code format. ChatGPT tells you what the code does, which can be useful for writing documentation, but can also waste your time. I'm trying to find a way to only output the commented code.

  
## Description 
  
  - Prompt Template : "Discard previous instructions. Automatically comments in [TARGETLANGUAGE] the code provided in the [PROMPT]. Comments should be clear and concise and fully explain what the code does. Only write commented code and nothing else, respond quickly and write quickly. Your answers are written in markdown format for the code. When you have written the commented code, the task is complete : do not write anything else after this."
  - Teaser : "Put any code to be commented in the language of your choice."
  - Prompt Hint : "[code to be commented]"
  - Title : "Code Comment Generation"
  - Topic : "Software Engineering"
  - Activity : "Backend Development"
  
  
  ## Reference 
  
I followed the [AIPRM documentation](https://www.aiprm.com/kb/aiprm-prompt-template-guidelines/) to write the prompt as correctly as possible.
