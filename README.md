# :star:  Automation Exercise API Automated Testing

This project contains automated tests for the APIs of the Automation Exercise website. The tests were originally written using Postman, and the goal is to migrate them to Cypress for better maintainability and scalability.

## :pencil2: Description

The repository includes a Postman collection that tests various API endpoints for the Automation Exercise website. The tests focus on verifying the functionality of key features such as user authentication, product listing, and order creation. This automated testing helps ensure that the API responses are correct and consistent.

### API Testing Features
- :key: **User Authentication**: Test login functionality and verify token generation.
- :package: **Product Retrieval**: Test if product data is returned correctly from the API.
- :shopping_cart: **Order Creation**: Test the ability to place orders and check if orders are created properly.
- :warning: **Error Handling**: Test how the API handles errors such as invalid input or unauthorized access.

## :rocket: Project Setup

### 1. Clone the repository
To start using this repository, clone it to your local machine:
```bash

git clone https://github.com/GazJack/AutomationExerciseWebsiteAPIautomatedTestingPostman.git
cd AutomationExerciseWebsiteAPIautomatedTestingPostman
```

### :package: Install Postman

If you don't already have Postman, download and install it from [here](https://www.postman.com/downloads/).

### :inbox_tray: Import the Postman Collection

To use the provided Postman collection:

- :memo: Open Postman.
- :gear: Go to `File` > `Import`.
- :file_folder: Choose `Automation Exercise.com_API automatinis testavimas Agn.postman_collection.json` from your local directory and click `Import`.

### :bulb: Run the Tests

Once the collection is imported into Postman, you can run the tests manually or use the Collection Runner for batch execution. The results will be displayed in Postman’s console.

## :fire: Running the Tests

You can execute the tests from Postman by clicking on each request or running the entire collection. The results will be displayed in Postman’s console.

## :memo: Contributing

If you'd like to contribute, please fork the repository, create a new branch, and submit a pull request with your improvements. Make sure your tests pass before submitting.

### :arrow_right: Steps to contribute:

- 💻 Fork the repository.
- :wrench: Create a new branch: `git checkout -b feature/your-feature`.
- :pencil2: Commit your changes: `git commit -m 'Add feature'`.
- :rocket: Push your changes: `git push origin feature/your-feature`.
- 🪄 Open a pull request.

## :star: License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more detail
