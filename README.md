## BACKEND STATE

The s3 bucket bucket name choice is very important. Apart from ensuring its uniqueness, you must choose a name depending on whether: 
    - it's to store the backend of a single applicationn env e.g enterprisename-backend-state
    - or the dev backend states of several applications e.g dev-applications-backend-state-yourusername

### Create a DynamoDB Table
This will ensure that the s3 bucket is locked after being eencrypted with the srver encryption resource.