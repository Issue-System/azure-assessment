# Azure assessment
The goal of this assessment is to assess your Azure knowledge and skills. Remember, you already passed the initial screening and the first interview; this is the beginning and preparation for a mutual technical conversation.

You are working on three fictional scenarios where you have to answer questions, fill in the blanks, design the solution, and deploy the resources. Create your personal repository, add the files from this repository, and you are ready to start!

You have to deploy the resources using automation, preferably as code. Add the code to the repository. Use the *ASSESSMENT.md* file for answering the questions and explaining your decisions and the configuration of the resources. When finished, commit, push and [share the link](mailto:robin.smorenburg@linkit.nl).
 
If there are any doubts or questions, feel free to reach out to [Robin Smorenburg](mailto:robin.smorenburg@linkit.nl).

Good luck, and don't forget to have some fun! :grin:

## Scenario 1: Virtual network
You receive a request for a virtual network. The goal is to create and deploy the solution. The virtual network is the first in the environment and needs to be scalable and cost-effective.

### Questions
- What are the use cases for a virtual network?
- What are the options for connecting multiple virtual networks?
- How do you secure a virtual network?

## Scenario 2: Storage account
You receive a request for a storage account from one of the .NET developers in the company. The goal is to create and deploy the solution. The data is classified as confidential. The developer mentions searching for an alternative to work with the storage account. Preferably from within the .NET application. The goal is to verify if the application is writing data correctly to the storage account.

### Questions
- What questions do you ask the developer?
- How do you secure the storage account?
- What is your advice for the developer for working with the storage account?

## Scenario 3: Application gateway
You receive a request for an application gateway. The goal is to create and deploy the solution. The application gateway is going to handle the traffic for a legacy web application. The web application consists of multiple virtual machines: one for the website, one for the images, and one for the videos.

### Web application
| Component | URL                        |
|-----------|----------------------------|
| Website   | http://contoso.com/        |
| Images    | http://contoso.com/images/ |
| Videos    | http://contoso.com/videos/ |

### Questions
- What are the use cases for an application gateway?
- What is the main difference between an application gateway and load balancer?