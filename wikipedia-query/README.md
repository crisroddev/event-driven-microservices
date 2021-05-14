# Wikipedia-Query
## Init Lambda
1. `sam init`
2. `cd folder`
3. `add wikipedia in requirements.txt`

# Create VENV
1. `cd helloworld`
2. `python3 -m venv ~/.wiki`
3. `source wiki/bin/activate`
4. `pip install -r requirements.txt`

# Build Go to wikipedia-query dir
1. `sam build`
2. `sam local invoke`

# Error add Payload
1. `touch payload.json`
```{
    "entity": "google"
}```
2. `sam build`
3. `sam local invoke -e payload.json`

# Debugging
1. `ipython`
2. `import wikipedia`
3. `wikipedia.summary("twitter")

# Deploy to AWS
1. `sam deploy --guided`
2. `ecr repo create`
