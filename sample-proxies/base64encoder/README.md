# Base64Encoder
This sample shows you how to use third-party libraries as includes for
JavaScript policies.

This sample uses the CryptoJS module to perform base64 encoding on 
the username and password presented in the request. An AssignMessage
policy is used to echo the base64 encoded value back to the client
as an HTTP header.
# Set up
To use the sample, you need:

* The email address and password that you use to login to enterprise.apigee.com.
* The name of the organization in which you have an account. Login to 
  enterprise.apigee.com and check account settings.

# Configure 
Update `/setup/setenv.sh` with your credentials

# Import and deploy sample project
To deploy, run `$ sh deploy.sh`

To test, run `$ sh invoke.sh`

# Get help
For assistance, please use [StackOverflow](http://stackoverflow.com/tags/apigee) and add the tag "apigee".

Copyright © 2014 Apigee Corporation

Licensed under the Apache License, Version 2.0 (the "License"); you may not use
this file except in compliance with the License. You may obtain a copy
of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.


