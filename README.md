# it4200_calculator_assignment

## Assignment: Building and Testing a Node.js Project with CircleCI

### Objective: 
The purpose of this assignment is to guide you through the process of setting up a CircleCI pipeline for building and testing a provided Node.js project. You will configure the pipeline to generate code coverage reports and store both the test results and coverage report artifacts. Additionally, you will learn how to retrieve these artifacts using the CircleCI API.

## Instructions:

### Part 1: 
Setting Up the CircleCI Pipeline 
1. Clone the provided sample Node.js project repository from the URL provided by your instructor. 
2. Configure the .circleci/config.yml file to define the following steps: 
    1. Set up a Node.js executor. 
    2. Checkout the repository code. 
    3. Install project dependencies using npm. 
    4. Run unit tests using a testing framework. 
    5. Generate a code coverage report using a code coverage tool. 
    6. Store the test results and coverage report as artifacts.

### Part 2: 
Retrieving Artifacts Using the CircleCI API 
1. Create a new CircleCI API token from your CircleCI account settings. 
2. Explore the CircleCI API documentation to understand how to use API endpoints to retrieve artifacts. 
3. Using a tool of your choice (e.g., curl, Postman, or a scripting language), write a script to authenticate with the CircleCI API using the API token. 
4. Utilize the appropriate CircleCI API endpoints to retrieve the stored test results and coverage report artifacts. 
5. Display or save the retrieved artifacts locally.

### **Part 3: 
Documentation Write documentation on your process with the assignment and the knowledge gained along with some of the pitfalls to avoid. Include the following points: 
* Documentation should be written in markdown. If you have never worked in markdown here is the markdown cheat sheet. The extension for a markdown file is .md 
* Describe the process of setting up the CircleCI pipeline for the provided Node.js project. 
* Explain how the retrieved artifacts could be valuable for the project’s development, debugging, and collaboration.

## Submission Guidelines: - Submit your CircleCI YAML files and documentation to GitHub Classroom

## Grading Criteria: 
* Successful setup of the CircleCI pipeline for building, testing, and artifact storage. 
* Accurate retrieval of artifacts using the CircleCI API. 
* Accurate documentation that would allow another student to reproduce your steps. - Adherence to submission guidelines and deadlines.

### Note: 
This assignment is designed to provide hands-on experience in configuring a CircleCI pipeline for building and testing a Node.js project, generating and storing artifacts, and retrieving these artifacts using the CircleCI API. Your documentation will demonstrate your understanding of the assignment’s concepts and their real-world applications.