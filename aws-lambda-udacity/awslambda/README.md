# See storage usage
`df -h'
# Resize
chmod +x resize.sh

# Initialize New Lambda 
1. `sam init`
2. `cd HelloWorldLambda`
3. `sam build`
4. `sam local invoke`
5. `sam deploy --guided`
6. `create-new-ecr-repo`
7. `paste uri`

# Deploy and Testing two ways
1. `sam local invoke`
2. `sam local start-api`
