# Inspiration

I recently created a [project](https://github.com/kllarena07/safa-message-scheduler) that involved scheduling lambda functions and noticed a lack of abstractions that take care of this. So, I wanted to create my own SDK that will schedule a lambda function.

You will be able to code your lambda function locally and then read the code file in to be scheduled on AWS.

This project is written in Javascript as I am most comfortable with the language and the Node SDK for AWS. But, I am planning on rewriting the project in a different language later on.

## Technologies Used

- AWS Lambda
- AWS EventBridge Scheduler