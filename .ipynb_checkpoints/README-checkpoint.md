# guiding-llm
repo testing out different frameworks for guiding llm outputs


# Some helpful functions on the day

## Get notebook access token:
jupyter server list

## Startup lmql server
lmql serve-model codellama/CodeLlama-7b-Instruct-hf --cuda --host 0.0.0.0 --port 9999 --trust_remote_code True

--token access_token

lmql serve-model meta-llama/Llama-2-7b-chat-hf --cuda --host 0.0.0.0 --port 9999 --token HUGGINGFACETOKEN --trust_remote_code True