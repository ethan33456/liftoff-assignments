# Project Outline
For this assignment, you will submit a high-level outline of your project. This can, and likely will, change over time. In particular, your mentor will provide direction and feedback to help sharpen your ideas. So don't worry if you feel unsure about some aspects of the outline or if you have to change some things later.

## Assignment Description
[Project Outline Assignment](https://education.launchcode.org/liftoff/modules/assignments/project-outline)

## Submission Instructions

### Overview
I am going to create the MVP for an app that will allow business owners to keep track of there inventory
in one place while having there products listed on multiple eCommerce platforms. Each storefront will ping
back to the database that stores the inventory to check for changes, and will update the stock count if there
are changes in the inventory. This solves two problems, it allows business owners to automate keeping track of
their stock on multiple platforms. And solves the age old problem of a store saying something is in stock online,
but when you get to the store it's actually out of stock. I got this idea because I currently manage a website for
a local business and the online shopping catalog I created with WooCommerce is supposed to pull stock count from there
in store inventory which is set up with square, but it is really buggy and does not work consistently at all.
### Features
- User Login
users need to login to edit personal storefronts. You can shop without login.
- Add / remove storefronts
Users can open or close storefronts like they would a business.
- Add / Remove products to / from storefronts
Products can be added to storefronts so stimulate an online store. A single product can only be added to the same storefront once, but can be added to multiple storefronts.
- "Purchase" products from storefronts
A product should be able to be "purchased" while viewing a storefront, it should decrease the stock qty by the amount purchased.
- Update stock count manually and automatically
A logged in storefront owner can manually increase or decrease inventory at one storefront, and changes should take effect across all storefronts.
If a customer purchases a product the stock qty of that product should change across all storefronts.
? Display statistical sales info from each product ?
A storefront owner could view sales info, best selling, worst selling etc.
- Search products
search a certain storefront for a product.
### Technologies
- Java
- Spring
- MySql
- ThymeLeaf
- Bootstrap
- Gradle 
- Js / html / css
- Docker
- Google cloud platform
### What I'll Have to Learn
I need to figure out how I can get the store fronts to routinely ping the database and check the entire database for inventory changes.
### Project Tracker
https://trello.com/b/Vf6pnCz1/inventory-tracker
