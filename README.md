# RetireSmart - RoboAdvisor
### Powered by the Amazons AWS Cloud Services
### For Retirement Plans

![Robot](Images/module-15-challenge.png)


### Background

Welcome to the RetireSmart Robo Advisor application! This cutting-edge platform is designed to assist retirement plan providers in expanding their client portfolios, with a particular focus on engaging young individuals. Leveraging the power of machine learning and natural language processing (NLP), our robo advisor offers personalized investment portfolio recommendations for retirement planning, transforming the customer experience.


### Packages Used:

* Amazon Lex [Amazon Lex Bot](https://aws.amazon.com/lex/)
* Lambda [Amazon Lambda](https://aws.amazon.com/lambda/)

### Files

* [lambda_function.py](Starter_Files/lambda_function.py)
* [correct_dialog.txt](Test_Cases/correct_dialog.txt)
* [age_error.txt](Test_Cases/age_error.txt)
* [incorrect_amount_error.txt](Test_Cases/incorrect_amount_error.txt)
* [negative_age_error.txt](Test_Cases/negative_age_error.txt)

---

### Application Description:

In this project, I have developed a powerful Robo Advisor that recommends an investment portfolio for retirement plans. This application combines the capabilities of AWS services and Python programming to provide a seamless and efficient user experience.

The Robo Advisor performs the following tasks:

1. Initial Robo Advisor Configuration:
   - Establishes an Amazon Lex bot with a single intent to initiate a conversation about the user's requirements for retirement investment portfolio suggestions.

2. Build and Test the Robo Advisor:
   - Ensures that the bot functions correctly and provides accurate responses during conversations with the user.
   - The user can interact with the bot through the chatbot window, simulating real-life conversations.

3. Enhance the Robo Advisor with an Amazon Lambda Function:
   - Implements an Amazon Lambda function called `recommend_portfolio()` to validate user input and generate investment portfolio recommendations.
   - The Lambda function performs data validation, such as checking the age and investment amount provided by the user.
   - Based on the selected risk level, the function returns an appropriate investment portfolio recommendation.

The application showcases the seamless integration of AWS services and demonstrates the power of combining machine learning, natural language processing, and cloud computing in the finance domain. It provides users with personalized investment recommendations for their retirement plans, empowering them to make informed financial decisions.

To see the application in action, you can refer to the demo videos or animated GIFs provided, which demonstrate the smooth user interactions and the accurate recommendation generation by the Robo Advisor.

Files to be Uploaded:
To complete the submission, please upload the following files to your repository:

1. Python script containing the final version of the Lambda function.
2. Two short videos or animated GIFs showcasing the Robo Advisor in action, specifically highlighting the interaction with the bot in the "Test bot" pane.

With this application, users can gain valuable insights and recommendations for their retirement investment portfolios, empowering them to make informed financial decisions and plan for a secure future.


###

