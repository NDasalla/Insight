# Project Title

  Insight is a Full-Stack app that utilizes the PERN stack and was developed to help prospective and current CUNY students connect with others through forums. Specifically, users may converse with others to provide and receive help and advice. 
  Upon opening the app, you will land on the main homepage where you may search for CUNY colleges and choose to go to their own College Homepage. At this moment, there are only four Colleges available, but you may add more manually in your own database if you so desire. Each College Homepage will display the majors for that College, which are also links to the majors' dedicated forums. For example, clicking on the Computer Science button will link you to the Computer Science forum page. 
  This app features fully-functioning CRUD operations for Authentication, forum posts, and comments, though at the moment users are unable to edit and delete their own accounts.
  
## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system. The first step would be to git clone this repository.

### Prerequisites

What things you need to install the software and how to install them:

- Visual Studio Code (Code editor)
- PostgreSQL (Database)
- Optional: Postman (API testing)
- Gitbash (For Windows users, Gitbash will provide some commands that may be needed)

## Installing

A step by step series of examples that tell you how to get a development env running

In the root directory, run the following command in your console to install all required dependencies:

```
npm install
```
Afterwards, `cd ` into the `client` directory:
```
cd client
```
Then, run `npm install` again. All of the required dependencies are now installed.
Now, you may start the Vite localhost by running 
```
npm run dev
```
in the `client` directory, which you should already be on. However, you will likely encounter errors, which will
likely be due to not having an actual database set up yet. So, in order to full use the app please create a new 
Postgres database and use Sequelize as the ORM. After successfully doing so, you may then open up a new terminal in
VSCode and cd into the root directory of the project. Then, you may run:
```
npm start
```
This will start the app's server. In your other terminal make sure you are in your `client` directory and if the Vite server
is not currently running, you may run the following command again:
```
npm run dev
```
Go to the Vite link and you should be able to see the functioning app.

## Deployment

This app is deployed on AWS through the AWS Learner Lab.

## Built With

* [PostgreSQL](https://www.postgresql.org/) - Database
* [Express.js](https://expressjs.com/) - Backend framework
* [React](https://react.dev/) - Javascript library for building component-based projects
* [Node.js](https://nodejs.org/en) - Runtime environment
* [Sequelize](https://sequelize.org/) - PostgreSQL ORM
* [React Router](https://reactrouter.com/en/main) - Client-side code routing
* [tailwindcss](https://tailwindcss.com/) - App styling

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

## Acknowledgments

* Big thank you to my Tech Talent Pipeline Capstone Group members.
