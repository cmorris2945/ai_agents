# Artificial Intelligence Agents
This repo is used for the development of "Professional AI Agensts" component program to create a team of ai agents to perform research for you.


![image](https://github.com/user-attachments/assets/1e6dd0f9-5cee-4f71-950d-39b907dc304c)





#### How It Works Together  
#### #  Project ONE:  JOB INTERVIEW AGENTS....

1. The analyst **introduces themselves** and asks the **first question**.  
2. The AI **refines the questions** based on **previous answers** to **dig deeper** into the topic.  
3. The process continues until the analyst decides they have **sufficient insights** and ends the interview.

#### Example Use Case

**Topic:** The benefits of LangGraph as an agent framework.  
**Analyst Persona:** Startup Entrepreneur.  

**Generated Questions:**
1. "Hi, I’m Alex, an entrepreneur exploring AI tools for startups. Can you share examples where LangGraph improved workflow efficiency in startups?"  
2. "That’s interesting. Can you explain how LangGraph integrates with existing systems to minimize setup costs?"  
3. "Thank you so much for your help!"  

#### Summary

This code enables an AI analyst to **conduct structured interviews**, starting with an **introduction** and **focused questions**, refining insights along the way. It dynamically adjusts based on **persona, goals, and prior messages**, making it ideal for **deep-dive explorations** of complex topics.


### # Project TWO.... Agent with Long-Term Memory that will manage a "to-do" list for you....

#### Example Output

```
================================ Human Message =================================

For the task to schedule monthly meeting with the USA Sales Team, I need to get that done by end of month.
================================== Ai Message ==================================
Tool Calls:
  UpdateMemory (call_KPTq6T7WoGJtzVzwT1yU96GH)
 Call ID: call_KPTq6T7WoGJtzVzwT1yU96GH
  Args:
    update_type: todo
================================= Tool Message =================================

No updates for ToDo.
================================== Ai Message ==================================

I've noted that the task to schedule the monthly meeting with the USA Sales Team needs to be completed by the end of the month. If there's anything else you'd like to adjust or add, just let me know!

## Second Task....

================================ Human Message =================================

Prepare the content for the meetings with Gen AI Teams of USA, Europe, and India.
================================== Ai Message ==================================
Tool Calls:
  UpdateMemory (call_sDuVimTbek29UJyzczWuO34A)
 Call ID: call_sDuVimTbek29UJyzczWuO34A
  Args:
    update_type: todo
================================= Tool Message =================================

Updated ToDo: {'task': 'Prepare the content for the meetings with Gen AI Teams of USA, Europe, and India.', 'time_to_complete': 180, 'solutions': ['Research recent developments in AI relevant to each region.', 'Draft an agenda tailored to the interests and needs of each team.', 'Include discussion points on collaboration opportunities across regions.'], 'status': 'not started'}
================================== Ai Message ==================================

I've added "Prepare the content for the meetings with Gen AI Teams of USA, Europe, and India" to your ToDo list. If there's anything else you need, feel free to ask!

```

#### Summary

This code builds a **complete AI-powered research pipeline**. It conducts **parallel interviews**, compiles findings into **sections**, and generates a **professional report** with an **introduction, body, and conclusion**. It’s ideal for **automating research projects, market analysis, or whitepaper creation** with **dynamic adjustments and scalability**.
