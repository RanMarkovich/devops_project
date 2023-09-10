# AWS

## client-side < --- > cloud connection

### prerequisites:
* aws cli installed
### steps
1. extract user access keys 
2. set aws account
   1. for multi-account config use this guide: https://dev.to/hmintoh/how-to-use-multiple-aws-accounts-with-the-aws-cli-3lge
3. Note: if configurations are not the default type: `$env:AWS_PROFILE='<config_user_name>'` to switch account to the desired one.