# awsSMS
A lambda function to send sms with AWS SNS

For setup you'll need an aws account with SNS, lambda and api gateway services
You might also need to increase your sns spending limit to increase the number of text messages you can send (NO SPAM ALLOWED)
The following links provide documentation:
https://docs.aws.amazon.com/apigateway/latest/developerguide/api-gateway-create-api-as-simple-proxy-for-lambda.html
https://docs.aws.amazon.com/AWSJavaScriptSDK/latest/AWS/SNS.html#publish-property
https://aws.amazon.com/premiumsupport/knowledge-center/sns-sms-spending-limit-increase/
https://docs.aws.amazon.com/AWSJavaScriptSDK/latest/AWS/SNS.html#publish-property

After setup, you'll need to this lambda function with get variables subject, message and phone
example: https://wuieuiwey.execute-api.eu-west-1.amazonaws.com/send_sms?subject=HelloSMS&message=Hello from AWS SNS&phone=+23490XXXXXXXX

For any queries, please feel free to reach me on wogwugwu.zenith@gmail.com

Happy implementing!

# Update: 24/07/2020
I find it far less stress to use serverless.com and i'd recommend that going forward.
Thanks
