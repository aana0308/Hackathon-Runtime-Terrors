# Hackathon-Runtime-Terrors
# Problem Statement 
Smart contracts are digital contracts stored on a blockchain that are automatically executed when predetermined terms and conditions are met.
Within a smart contract, there can be as many stipulations as needed to satisfy the participants that the task will be completed satisfactorily. To establish the terms, participants must determine how transactions and their data are represented on the blockchain, agree on the “if/when...then…” rules that govern those transactions, explore all possible exceptions, and define a framework for resolving disputes.

There are many people who want to access Polygon and utilise its benefits but do not have the appropriate coding knowledge and hence, our software aims to make things convenient for the general masses.

## Input

On the main website page, the user will be entering their login/registration details and then proceed to enter the contract details, like - the name of the contract, access specifier, conditions of the contract and other essential details required to make the contract.

## Output

Our website gets the user input details and using appropriate AI algorithms, it generates the corresponding Smart Contract code in Solidity language - which matches the needs as specified by the user.

## Software Used in AI Component

Using OpenAPI we can convert the user input into the corresponding smart contract code which is required by the user. Multilayer Perceptron Classifier is then used to check the validity and accuracy score of the code generated.

**OpenAPI :**
<br>
OpenAPI Specification (formerly Swagger Specification) is an API description format for REST APIs. An OpenAPI file allows you to describe your entire API, including:

1. Available endpoints (/users) and operations on each endpoint (GET /users, POST /users)
2. Operation parameters Input and output for each operation
3. Authentication methods
4. Contact information, license, terms of use and other information.
The ability of APIs to describe their own structure is the root of all awesomeness in OpenAPI. Once written, an OpenAPI specification and Swagger tools can drive your API development further in various ways:

Design-first users: use Swagger Codegen to generate a server stub for your API. The only thing left is to implement the server logic – and your API is ready to go live!
Use Swagger Codegen to generate client libraries for your API in over 40 languages.
Use Swagger UI to generate interactive API documentation that lets your users try out the API calls directly in the browser.
Use the spec to connect API-related tools to your API. For example, import the spec to SoapUI to create automated tests for your API.
And more! Check out the open-source and commercial tools that integrate with Swagger.
Link: https://beta.openai.com/playground/p/default-text-to-command

**Multilayer Perceptron Classifier :**
<br>
Multi layer perceptron (MLP) is a supplement of feed forward neural network. It consists of three types of layers—the input layer, output layer and hidden layer. The input layer receives the input signal to be processed. The required task such as prediction and classification is performed by the output layer. An arbitrary number of hidden layers that are placed in between the input and output layer are the true computational engine of the MLP. Similar to a feed forward network in a MLP the data flows in the forward direction from input to output layer. The neurons in the MLP are trained with the back propagation learning algorithm. MLPs are designed to approximate any continuous function and can solve problems which are not linearly separable. The major use cases of MLP are pattern classification, recognition, prediction and approximation.

## Future Work
Increase the accuracy score of both models, don't know how to do that as of now.
