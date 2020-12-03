<p align='left'>
    <img src='https://static.wixstatic.com/media/85087f_0d84cbeaeb824fca8f7ff18d7c9eaafd~mv2.png/v1/fill/w_160,h_30,al_c,q_85,usm_0.66_1.00_0.01/Logo_completo_Color_1PNG.webp' </img>
</p>

# Henry

# HenryTalent

## Introduction

This is a student group project done as a final big assigment, in wich join all the technologies learned at SoyHenry bootcamp, in addition the academy gathered the best developers of the *05 cohort* to make the first delivery of this app for a future deployment.

*Graduation project at soyHenry.com bootcamp.*

## About

this project consists in search, filtering and selection of candidates, for the creation of packages/folders to be sent to possible recruiters or employers.

## Developer Team

*Dev Leader*
- @MartinCura

*Dev Team*
- @diegotolaba09
- @FedericoCalderon
- @Lukasver
- @Kuinoso
- @SebaLevin
- @MatiasFunes94
- @BryanCPineda
- @cristianluca19


## Project Objetives

- Build a JavaScript App from scratch
- Afirm and conect all the learned concepts in the Carreer 
- Practice GIT workflow / team work, in a real working environment
- Use scrum agile methodology
- learn good programming practices
- implement testing  for feel confident about code

## Stack of Technologies

### Front End:
HTML, CSS, Javascript, React, Material-ui, Redux, Prettier.

### Back End:
TypeScript, Node.js, Express, Faker, Mailgun-js, Multer, Yml, Eslint, Mocha, Sequelize.

### Database:
PostgreSQL

## **Starting Instructions** 

## BoilerPlate

The boilerPlate has two folders: `api` and `client`.

Inside `api` you must have to create a file called: `.env` 
that has the following form: 

```
APP_ID=talent-api 
PORT= your_own_port
LOG_LEVEL=debug
REQUEST_LIMIT=100kb
SESSION_SECRET= secretword

OPENAPI_SPEC=/api/v1/spec

DB_USER=postgresuser
DB_PASSWORD=postgrespassword
DB_HOST=localhost
DB_PORT=postgresport
DB_NAME=data_base_name
DB_URL=back_end_url exp(http://localhost:3001)

CLIENT_URL=front_end_url exp(http://localhost:3000)

NODE_ENV=development
TALENT_URL_ROOT =front_end_url
MAILGUN_DOMAIN = mailgun_domain
MAILGUN_APIKEY = mailgun_apikey
MAILGUN_TALENT = mailgun_email

```
You have to replace `your_own_port`, `postgresuser`, `postgrespassword`, `postgresport`, and `MAILGUN*`  with your own credentials to connect to postgres database, and Mailgun services. This file will be ignored by github, as it contains sensitive information (the credentials).

The SESSION_SECRET is a random security keyword, you can change or keep it.  

Inside `client` you must have to create a file called: `.env` 
that has the following form: 

```

REACT_APP_BACKEND_URL= http://localhost:PORT/api/v1

```

PORT must be the same as api.

## Next 
### _Connect the data base_

 - Go to your postgres database manager and create a new   database. Replace `"data_base_name"` in `.env` file with the name of the new database.

 ### _Install the necesary package to run it_

- Open the project console
    + Inside `api` folder, run the command line, `npm install` / `yarn install` 
    + Inside `client` folder, run the command line, `npm install` / `yarn install`.

### _Test the project_

- Open the project console
    + Inside `api` folder, run the command line, `npm run test` / `yarn run test`.

### _Run the project_

- Open the project console
    + Inside `api` folder, run the command line, `npm run dev` / `yarn run dev`.

    + Inside `api` folder, run the command line, `npm run seed` / `yarn run seed` to fill the database, while the back is running.
        
    + Inside `client` folder, run the command line, `npm start` (go to http://localhost:3000/). 

# Project Screens 

- Home 
![home](https://user-images.githubusercontent.com/66705822/100810450-4f0bd600-3417-11eb-9f30-374d0d31a9f6.png)

- Filter Candidates
![filter-candidates](https://user-images.githubusercontent.com/66705822/100810468-59c66b00-3417-11eb-816b-27b6f219d99e.png)

- Filter Skill Technologies 
![filter-skill-technologies](https://user-images.githubusercontent.com/66705822/100810484-5fbc4c00-3417-11eb-8394-19bc30fcf6a1.png)

- Folder Preview 
![folder-preview](https://user-images.githubusercontent.com/66705822/100810502-664ac380-3417-11eb-8517-0d7c594da2c6.png)

- Add Recruiter
![add-recruiter](https://user-images.githubusercontent.com/66705822/100810516-6c40a480-3417-11eb-89d9-b426680fb8e5.png)

- Cadidates CRUD 
![crud-candidates](https://user-images.githubusercontent.com/66705822/100810521-6fd42b80-3417-11eb-8ea1-91d6a04129b6.png)

- Folders CRUD
![crud-folders](https://user-images.githubusercontent.com/66705822/100810526-72368580-3417-11eb-92bf-d1d4b4d87e2f.png)

- Skills CRUD
![crud-skills](https://user-images.githubusercontent.com/66705822/100810533-75317600-3417-11eb-8aea-b4a4f30e623c.png)


![visitors](https://visitor-badge.glitch.me/badge?page_id=BryanCPineda.HenryTalent)