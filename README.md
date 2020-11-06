# Twic Frontend Coding Challenge

Welcome to the Twic frontend coding challenge! Please read the following instructions carefully.

**Your goal is to set up an application which enables the user to view and manage vendors.**

# Contents

- [Business need](#business-need)
- [Use cases](#use-cases)
- [Evaluation criteria](#evaluation-criteria)
  - [Technology requirements](#technology-requirements)
- [How to submit](#how-to-submit)
- [How to run API server](#how-to-run-api-server)
- [Time limit](#time-limit)

# Business need

The goal of this application is to allow the Twic team to view and manage vendors.

# Use cases

- The user should be able to:
  - Visit the root path and see a list of all the vendors
  - Sort the vendor list by name in ascending/descending order
  - View vendor information on a separate vendor details page
  - Update the vendor name (should persist when the page is reloaded)
  - You may design it however you wish (just make it look usable). Don't worry, we don't expect you to be a professional designer.

# Evaluation criteria

## Technology requirements

**React** and **JavaScript** are mandatory requirements. Apart from this, you can use any libraries.

# How to submit

- Clone this repository.
- A RESTful API for `vendors` is provided with the challenge. To run, follow: [How to run API server](#how-to-run-api-server)
- Complete your project as described above within your local repository.
- Ensure everything you want to commit is committed before you bundle.
- Create a git bundle: `git bundle create your_name.bundle --all`
- Email the bundle file to your point of contact.

**In order to be fair to all candidates, please refrain from sharing your solution on public repository hosting services such as GitHub and Bitbucket.**

# How to run API server

The boilerplate includes a small service for data fetching. The file `db.json` includes all the necessary data to achieve the goal. Please follow the steps below to start the server:

```
yarn or npm install .
yarn server or npm run server
```

Check [json-server](https://github.com/typicode/json-server) for more information.

# Time limit

There is no hard time limit for this coding challenge. However, we believe that 3-4 hours is sufficient for the must-have parts of the application. While we appreciate all the effort put into the challenge, we also do not want to take up too much of your time. Our advice is to focus on making sure that the application works properly before moving on to secondary objectives. Happy coding!

Good luck,
The Twic Team
