# ** Split Pay **

<p> Split Pay is an interactive web application which allows users to create groups, and split bills within each group. Within the payments model, it allows users to see and track all transactions, and settle expenses once paid. </p>

You can find the link to the Split Pay website [here](https://split-pay.netlify.app/). 

You can find the Mongoose DB backend repo [here](https://github.com/mdak2806/split-pay-express-backend).

## Project Overview
As part of the Software Engineering Immersive program, as General Assembly Project #3 was designed to challenge students to create a website using technologies of their own choice, from what they have learnt thus far. 

Due to our groups interest in finance, we decided to create a Split-wise clone, which allowed the tracking and settling of expenses. 

We decided to also utilise a new technology Mongoose DB as our backend server and create a React Hooks Front-End (previously used components based). 

![Split Pay Home Page Interface](/build/Split%20Pay%20App.jpg)

## Logins:

Users:

* Email: craig@gmail.com
* Password: chicken

* Email: wen@gmail.com
* Password: chicken

* Email: kris@gmail.com
* Password: chicken

* Email: luke@gmail.com
* Password: chicken

## Wireframe and page associations

Below is an image highlighting the high-level associations between the different pages on the Split Pay Website.

![Split Pay Associations](/build/Split-pay-wireframe.jpg)

1. Sign in/Sign out

2. Password Encryption

3. JSON data providing connection to React front end

4. Create User Profile for full site access

5. Create and name your new group

6. Create a group expense

7. Settle expenses in payments section

## Technologies Used ##

Mongoose DB main backend technology used, and React.js was the main front-end technology utilised. The following technologies where also used:

1. Mongoose DB
2. CSS 
3. HTML & ERB
4. MongoDB Cloud Atlas
5. Netlify
6. React
7. Cors
8. Bcrypt
9. JWT

## Project Status

The project is approximately 80% complete, all essential components are running, although our initial intentions was to create a check-out system connecting a user’s back details to their Split-pay account, and thus allowing direct debts and deposits directly on the same application. 

This would take the Split-wise ideal to the next level, and allow a more user friendly, and more useful product overall. 

Furthermore, payments section could be split into two separate pages (Payments and Expenses) to create a distinction between a payee (money owed) and payer (money owing) payments. 

### Project Future Improvements 

- [ ] *Split payments section into two pages, payee(money owed), and payer(money owing).*
- [ ] *Adjust CSS to allow the dynamic list of payments that do not overflow onto the footer.* 
- [ ] *Adding a dynamic currency system allowing users to select the currency of the payment.*
- [ ] *Allow users to only select group members based on contact details instead of the full list of Split-wise users.* 
- [ ] *Better utilise the categories to allow users to track overall expenses based on there activities. * 
