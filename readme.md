1. PULL DOCKER IMAGE
docker pull kashyapsoni3010/scanjd

2. RUN CONTAINER
    A. USE FREE MODEL - COHERE COMMAND R
        docker run -d -p 8004:8004 -e API_KEY="your API key here if you want to use cohere command R model" -e MODEL="cohere" --name scanjd_instance kashyapsoni3010/scanjd
    B. USE OPEN AI - PAID MODEL
        docker run -d -p 8004:8004 -e API_KEY="your API key here if you want to use OPEN AI models" -e MODEL="openai" --name scanjd_instance scanjd

3. LOAD EXTENSION IN CHROME
    A. Open Chrom, click on the three dots on top right corner
    B. Click extensions, select manage extensions