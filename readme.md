1. USE FREE MODEL - COHERE COMMAND R
docker run -d -p 8004:8004 -e API_KEY="your API key here if you want to use cohere command R model" -e MODEL="cohere" --name scanjd_instance scanjd

2. USE OPEN AI - PAID MODEL
docker run -d -p 8004:8004 -e API_KEY="your API key here if you want to use OPEN AI models" -e MODEL="openai" --name scanjd_instance scanjd