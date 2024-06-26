# API Testing with Postman

Automated API tests of an e-commerce application built using **Postman**.

## Prerequisites

Install the following prerequisites:

1. [Oracle JDK](https://www.oracle.com/java/technologies/downloads/) or [OpenJDK](https://openjdk.org/)
2. [Node.js](https://nodejs.org/en/)
3. [PostgreSQL](https://www.postgresql.org/download/)
4. [Visual Studio Code](https://code.visualstudio.com/download)
5. [Postman](https://www.postman.com/downloads/)

## System Under Test (SUT)

The system under test (SUT) is this [e-commerce application](https://github.com/mgrybel/ecommerce-website) built using **Spring Boot 3** and **React 18**.

To run tests in this project, you must first install and run the SUT. Follow [these steps](https://github.com/mgrybel/ecommerce-website/blob/master/README.md).

## Download the project

Download the ZIP file and unzip the project.

Inside the ZIP file, you will find the
**EcommerceWebsiteAPITests.postman_collection.json** file, which is a Postman collection containing a group of saved requests.

## Import a JSON collection into Postman

1. Open Postman and click the **Import** button in the top left.
2. In the import modal, click **Select Files**, choose the JSON collection that you have just downloaded, and click **Open**.
3. Click the **Import** button to load the collection.
4. The collection will now be available in Postman under **Collections** on the left sidebar. All folders and requests will be imported.

![plot](https://github.com/mgrybel/api-testing-postman/blob/master/images/step1.png?raw=true)

## Run tests

The **Collection Runner** enables you to run the requests in a Postman collection in a specified order to test the functionality of the API of the SUT.

1. Select **Collections** in the sidebar and select the imported Postman collection.
2. Click three dots on the right and select **Run collection**.
3. Select the **Run manually** option and click **Run EcommerceWebsiteAPITests**.

![plot](https://github.com/mgrybel/api-testing-postman/blob/master/images/step2.png?raw=true)

![plot](https://github.com/mgrybel/api-testing-postman/blob/master/images/step3.png?raw=true)
