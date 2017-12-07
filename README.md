# wmdd_4999_final_assignment
# Final Assignment Twilio
This function send a text message every time you upload a object in your specified S3 bucket. To test you need to replace your S3 bucket name which already exist in serverless.yml file.

Also add your Twilio Account SID, Auth Token and Phone Number in serverless.yml and handler.js files. In handler.js replace add the phone number to which you want to send message in place of (to: "Your Number").
You need to install modules twilio and serverless-plugin-existing-s3.
