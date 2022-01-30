# apdev-usecase

Notes
--

1. I know I can do this straight through anypoint. But I was under the impression it would be one repository per Mule Project. And obviously here I have 6, so I wanted to keep them together.
2. There is a config.yaml absent from the projects because since everything here has been running locally on my machine, I was able to hardcode the connection values. In real examples I am aware this is bad practice, I apologize for that.
3. Error handling may seem light, but when importing an API Spec from exchange, the error handling it creates in the scaffolding covered a lot of my cases for me.
5. The oauth API is an example API I got from the internet and am able to host on cloudhub to ensure oauth verification. 
4. I'm sure I did a lot of 'newbie' things in my design, these are just what I viewed off the top of my head.


FIXES AS OF 1/29/2022
--

1. Added a Config.yaml to all of the APIs and abstracted all the values
2. Added the orders and order-items API to the same project
3. Enables API discovery for all the API deployments
4. added bulk insert and bulk update to the order-items api 
5. Integerated batch processing 
