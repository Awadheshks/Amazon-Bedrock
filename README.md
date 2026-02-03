# Amazon-Bedrock - Foundation Models hands on workshop
**Amazon Bedrock** is a fully managed service that provide access to the Foundational Models from industry- leading providers and leaders via API Concepts. The advantage with Amazon Bedrock you can choose a variety of models to integrate or compare the models according to the customized use cases. It helps the customers to achieve the goals in GenAI applications across business efficiently.

If you’re new to Amazon Bedrock or AI concepts, I’d love to walk you through a workshop designed for beginners. I’ll break everything down into simple, practical steps so it’s easy to follow. This workshop focuses on core Amazon Bedrock concepts and how to work with different foundation models in a hands-on way.

![img]()

**Providers in the Foundational Models**- Amazon Bedrock Marketplace is a new capability in Amazon Bedrock that enables developers to discover, test, and use over 100 popular, emerging, and specialized foundation models (FMs) - https://aws.amazon.com/bedrock/marketplace/

Lets' follow the steps to start the Workshop.

Step 1 — Once it is done, Click on the “SageMaker AI” service on the AWS Console Dashboard
* The next step is to create a Domain and click on “Domains” below in the Admin Configuration.

![img]()

* Step 2 — Choose “Set up for the Single User” (Quick Step)

![img]()

Step 3 — Create a User Profile in the “Domain” Section & Choose a name for the User Profile. Once it is created ,follow the user profiles to verify that it has been registered in the list below.

![img]()

Step 4 — The “Execution role” in the user profile allows “to access all the models” — the essential part is {status must be “in service”}

![img]()

Step 5 — Launch the Studio in the User Profile “above ” — if any doubt, jump to see the Step 3

![img]()

Step 6 — Choose the “Jupyterlab” Notebook to access further and Create a “JupyterSpace”

![img]()

Step 7 — Choose the “Jupyterlab” Notebook to access further and Create a “JupyterSpace” , Jupyterlab->Create New JupyterLab space

![img]()

Step 8 — Create a “workspace”-> JupyterLab space and choose the name “my-workshop-space” accordingly

![img]()

Step 9 — Choose the Instance type “ml.t3.medium” and Image “SageMaker Distribution 3.7.0”

![img]()

Step 10 — Open the Workspace, the next step is to choose the python on the left corner Python3.
“To execute this workshop, you need Python3 installed.”

![img]()

Step 11 — Click on the right corner of the menu and choose to “clone a repository”

![img]()

git clone https://github.com/aws-samples/amazon-bedrock-workshop


