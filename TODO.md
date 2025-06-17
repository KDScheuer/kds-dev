# Project Setup & Deployment

## 1. Initial Setup
- []Create GitHub repo (e.g., kds-dev) and push initial structure
- [] Register Domain / Hosted Zone (kds-dev.com)
- [] Add License file to repo
- []Add basic README.md with project overview

## 2. Frontend (site/)
- [] Create index.html
- [] Style Site with CSS (mobile-first)
- [] Contact form
    - [] JS for submit to api gateway
    - [] Secure connection (CORS, etc)
    - [] Indicate form is sending
    - [] Indicate form sent successfully
    - [] Error handling for failures  

## 3. Lambda Function (lambda/)
- [] API Gateway to handle incomeing requests
    - [] CORS Enabeld 
- [] Write contact form Lambda handler 
    - [] Open Phone Layer
    - [] Pre Flight CORS check
    - [] Sanitize / Verify Input
- [] Env Vars
- [] Create tests

## 4. Terraform Infra (infra/)
- [] Deploy Amplify App
    - [] Redirect Config
- [] Deploy API Gateway
- [] Deploy Lambda
    - [] Triggered by API POST Request    
