# guiding-llm
repo testing out different frameworks for guiding llm outputs

# Some helpful functions on the day

## Get notebook access token:
jupyter server list

## Startup lmql server
lmql serve-model codellama/CodeLlama-7b-Instruct-hf --cuda --host 0.0.0.0 --port 9999 --trust_remote_code True

### If the huggingface model requires an access token:
lmql serve-model meta-llama/Llama-2-7b-chat-hf --cuda --host 0.0.0.0 --port 9999 --token HUGGINGFACETOKEN --trust_remote_code True

# Compute environment

Docker image with jupyter, pytorch and cuda:
https://hub.docker.com/r/runpod/pytorch

(used this on the day: runpod/pytorch:2.0.1-py3.10-cuda11.8.0-devel)

This should come with Python 3.10.6 (main, May 29 2023, 11:10:38) [GCC 11.3.0] on linux.
