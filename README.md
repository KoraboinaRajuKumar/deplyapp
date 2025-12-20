# deplyapp


# docker 
# docker ps      # containers
# docker ps -a   # running conatiners
# docker version

# docker build -t deplyapp:latest .                           # latest em avasarmled

# docker run -d -p 8080:8080 --name my-project deplyapp         to run the container
#                               <containe-name> <image-name>

# leftside port is systemport and right side port is container port


# To chec app is running or not 
# http://localhost:8080/    in browser  



# ECR RELATED:
==========

What you must do next

Add these GitHub repository secrets (Settings → Secrets and variables → Actions):
AWS_ACCESS_KEY_ID (from an IAM user, not root)
AWS_SECRET_ACCESS_KEY
AWS_ACCOUNT_ID (12-digit number)
ECR_REPO_NAME (e.g., deplyapp or fastapi-hello)
Optional: add AWS_REGION secret and change the workflow to use it if you don't use us-east-1.
