# aws-account-initial-setting
monstar lab recommended AWS Initial Setting

## About
You can perform the following settings with this CloudFormation.

- **IAM password policy setting**
- **Enable CloudTrail**
- **Enable Config**
- **Enable GuardDuty**

After creating the AWS account, We recommend that you do this first.

## Parameter
This is the default setting.  
Please change as necessary.

![parameter.png](https://github.com/monstar-lab/aws-account-initial-setting/blob/master/images/parameter.png)

## Usage
### Management Console
1. Login to **Management Console**. I do not mind being root or IAM account.
2. Select an arbitrary **region**.
3. Select **Services** to **CloudFormation**
4. create stack
![181003-0001.png](https://github.com/monstar-lab/aws-account-initial-setting/blob/master/images/181003-0001.png)
5. Select a template and upload it to **S3**
![181003-0002.png](https://github.com/monstar-lab/aws-account-initial-setting/blob/master/images/181003-0002.png)
6. Please fill in the stack freely. I wrote aws-account-initial-setting-stack.
![181003-0003.png](https://github.com/monstar-lab/aws-account-initial-setting/blob/master/images/181003-0003.png)
This is the default setting.  
Please change as necessary.
7. It is completed when the status becomes **CREATE_ COMPLETE**.
![181003-0004.png](https://github.com/monstar-lab/aws-account-initial-setting/blob/master/images/181003-0004.png)
![181003-0005.png](https://github.com/monstar-lab/aws-account-initial-setting/blob/master/images/181003-0005.png)

### aws cli
To be written:sweat_smile:

## Authors
Takayuki Niinuma  
GitHub : [monstar-taka](https://github.com/monstar-taka)
