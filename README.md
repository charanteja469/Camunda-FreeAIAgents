# Camunda-Free AI Agents (OpenRouter Connector)

This Connectors provides you models like
"Llama Maverick",
"Llama Scout",
"Llama 70B Instruct",
"Llama 3.2-3B Instruct",
"Llama 8B Instruct",
"OpenAI GPT-20B",
"Microsoft Mai DS",
"Google Gemini 2.0",
"Google Gemma E2B",
"Google Gemma E4B",
"Gemma 3-4B",
"Gemma 12B",
"Gemma 27B",
"Gemma 2.9B",
"DeepSeek Chat V3.1",
"DeepSeek R1-0528 QWEN3 8B",
"DeepSeek R1-0528",
"DeepSeek Distill LLama 70B",
"Mistral Small 3.2-24B",
"Mistral Dev Small 2505",
"Mistral Small 3.1-24B",
"Cognitive Dolphin 3.0",
"Cognitive Dolphin Venice",
"Mistral 24B 2501",
"Mistral 7B",
"Qwen Coder",
"Qwen 4B",
"Qwen 30B",
"Qwen 8B",
"Qwen 14B",
"Qwen 235B",
"Qwen VL-32B",
"Qwen-2.5 Coder 32B",
"Qwen 72B",
"Kimi K2",
"Kimi Dev 72B",
"DeepHermes 3-LLama3.8B",
"Hermes 3-Llama3.1 405B",
"Minimax M2",
"Alibaba DeepResearch 30B",
"Meituan LongCat",
"Nvidia Nemotron Nano 9B",
"Z-AI GLM 4.5",
"Shisa-V2 LLama3.3 70B",
"ARL QWQ 32B",
"Agentica DeepCoder 14B",
"Tencent Hunyuan 13B"

<img width="1021" height="516" alt="image" src="https://github.com/user-attachments/assets/55c490c1-dd40-4526-a784-e5be927a9f1d" />


You can use these models freely by generating api key in https://openrouter.ai/

## Steps To generate API Key

1.	Open https://openrouter.ai/ .
2.	Login with your gmail.
3.	Open settings-API Keys create API key.

  <img width="940" height="281" alt="image" src="https://github.com/user-attachments/assets/1c2ff47e-2c50-4d16-a6c4-7ff47e59cac9" />

 
4.	Save it in notepad.
   
Note: 1.openrouter gives you the unlimited credits. And it contains free ai models.
2. This Connector and openrouter is for POC and Practice purpose only.

## Test with SaaS and Self-Managed

### Setting Up in Saas/Self managed Environment:
1.	Navigate to Camunda SaaS.
2.	Upload the connector template from https://github.com/charanteja469/Camunda-FreeAIAgents/blob/main/FreeAiAgentsConnector.json or download it from marketplace.
3.	if your using Desktop modeler--> go to modeler folder-->resources-->element-templates-->Past the above downloaded Openrouter Connector Template


### STEP BY STEP Process to Configure and Use OpenRouter Connector
1.	Create a workflow with Start event, Task, End Event.
2.	select the task and click on element change type and search for Free AI Agents Connector.
   <img width="940" height="347" alt="image" src="https://github.com/user-attachments/assets/389ed9e7-2842-41ab-aa8d-90725ec038bc" />
   
3. configure the properties like API Key(which you created previously).
<img width="940" height="398" alt="image" src="https://github.com/user-attachments/assets/347777f6-7718-49bd-a9d6-6b01082fc88d" />

4. select the Model from list(you can use same API key for all models).

<img width="940" height="429" alt="image" src="https://github.com/user-attachments/assets/2d46fc92-a206-4ecb-a53a-d93dd5c68436" />

5. provide the prompt.

   <img width="940" height="402" alt="image" src="https://github.com/user-attachments/assets/94aad8c0-bdca-4cb0-8c62-938c59c4b711" />

6.	the response from the agent will be stored in agentResponse Variable.
  
7.	Deploy and Run the workflow. you can see the output in operate.
   <img width="940" height="433" alt="image" src="https://github.com/user-attachments/assets/5772727c-2f29-4cf3-8a7a-690a3ffb1170" />





