# aws-cognito-login-federated-ids

Place **_application.properties_** file in resources folder. The following credentials are needed:
<br/><br/>
AWS_ACCOUNT_ID= AWS account ID <br/>
AWS_COGNITO_IDENTITY_POOL_ID= Cognito identity pool ID <br/>
ACCESS_KEY= AWS IAM user access key <br/>
SECRET_KEY= AWS IAM user secret key <br/><br/>

API calls:<br/>
URL : [address]/api
POST: { token : id_token, provider : provider_name}<br>
provider_name = 'google' or 'facebook'
 
