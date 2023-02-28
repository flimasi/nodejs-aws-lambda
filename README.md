# nodejs-aws-lambda
Nodejs Application Lambda

npm install -g serverless

zip -j deploy.zip ./dist/*

# Deploy AWS Command Line
aws lambda update-function-code --function-name=nodejs-aws-lambda --zip-file=fileb://deploy.zip --profile flimasi
