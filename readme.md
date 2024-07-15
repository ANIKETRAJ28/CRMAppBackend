# CRM-Backend App
## Setup
- Clone the project
```
https://github.com/ANIKETRAJ28/CRMAppBackend.git
```
- Install the dependencies
```
npm i
```
- Create a file named `.env`
- In `.env` file paste the following snippet
```
JWT_SECRET_KEY=<your_jwt_key>
```
- If hosted the database on atlas then paste this
```
MONGODB_URI=mongodb+srv://<username>3:<password>@crm-database.p7cc7eo.mongodb.net/<database_name>?retryWrites=true&w=majority&appName=CRM-Database
```