# ChatwithChatGPT

## Install
```
pip install openai
```
Create OPENAI_API_KEY.txt under the same directory as ChatwithChatGPT.py. 
Put your OpenAI key in it.

## Run 
```
python ChatwithChatGPT.py 
```

You can add any parameters you want to tune. Normally we only change temperature and top_p. But do not change them together.  
Use --stop and --max_tokens to control the length of the answer to prevent wasting too much quota.  

For example:
```
python ChatwithChatGPT.py  --temperature 0.1 --max_tokens 30 --debug True
```


## Open AI API docs
https://platform.openai.com/docs/api-reference/introduction  
https://platform.openai.com/docs/guides/chat