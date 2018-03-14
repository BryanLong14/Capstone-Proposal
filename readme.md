# Capstone Project Proposal: _Can I Eat That?_   

## Project Description
* _Can I Eat That?_ is a mobile app that allows users to quickly create a custom list of food items and then easily avoid purchasing those items when shopping. Users can choose to avoid foods based on dietary restrictions such as paleo, vegan, vegetarian, and autoimmune diet. Alternatively, users can customize a list of foods to avoid based on specific allergies or food sensitivities.
* Users are then able to scan barcodes at the grocery store to see if the product contains any of ingredients on their list. Item nutrition information is also displayed so users can monitor and track their health goals.    

## What Problem Does Your Project Solve?
* With continually emerging science in agriculture and health, people are realizing the extent to which food allergies and food sensitivities affect them. In the United States alone, researchers estimate that up to 15 million Americans have food allergies<sup>1</sup>.
* Currently, these people do not have access to a tool that can easily tell them if allergens are contained in food.

## How Will This Project Solve The Problem?
* _Can I Eat That?_ categorizes and references food items according to common dietary restrictions, food allergies, and food intolerances. The app allows users to quickly create their own list and then reference that list when shopping. It utilizes the [Barcode API](https://www.programmableweb.com/api/can-i-eat-it-barcode) which includes a database of commercially available food items, their ingredients, and their barcodes.     

## Map of the User Experience
* User opens app and selects "New Profile" or “Existing Profile”.
* User selects foods to avoid from prepopulated list (Vegetarian, Paleo, Vegan, AIP). Alternatively, users choose custom foods to avoid based on allergies or intolerances.  
* User is then prompted to search for a food item or scan a barcode:
  * Search: User types in name of food item see if item’s ingredients contain allergens from their selected list
  * Scan: User scans barcode of item to be able to tell if item contains allergens
* Product health information is displayed for the selected product.

## What Technologies do you Plan to Use?
* HTML, CSS, JavaScript
* Knex.js, Psql, PostgreSQL
* Node.js
* React Native
* React Native Barcode Scanner (stretch goal)
* [Barcode API](https://www.programmableweb.com/api/can-i-eat-it-barcode)

## Prioritized Feature list
* Seeded database of commonly restricted food from diets, allergies, and intolerances.
* Seeded database of users
  * Profile {Name:, id:, allergens/intolerances:}
  * CRUD functionality
* Frontend allows user to create profile
* Frontend allows user to add foods to avoid
* Queries allow users to type a food name into the search bar and the Barcode API matches food name to ingredient list, checks for matches   


## Resources
<sup>1</sup> National Institute of Allergy and Infectious Diseases, National Institutes of Health. Report of the NIH Expert Panel on Food Allergy Research. 2006.
