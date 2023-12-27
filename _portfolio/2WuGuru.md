---
title: "WuGuru"
excerpt: "Database of Duke Food Items where users can review and learn about new ones!<br/><img src='/images/WuGuru.png'> (SQL, Flask, HTML, Python)"
collection: portfolio
---

Demo Video: https://www.youtube.com/watch?v=Glc2zEvpeCE

Github Repo: https://github.com/Nsilswal/WuGuru

===

WuGuru is a website where Duke students can look at all foods available for purchase at Duke! The website runs on a Flask backend, with a PostgreSQL database supporting all operations. This was a semester long project where me and a team of four others colloborated on one repository to build various features and functionality for users.

Below is a list of all the functionality we offer:
Users ● Users can update all information except the id. Ensure that email is unique among all users. ● Create administrator accounts that allow for owners of restaurants to adjust the menus of their restaurants as well as the attributes of their restaurants. Restaurants ● Created a unique homepage for each restaurant that includes extra information: restaurant description, pictures, a notification for whether the restaurant is currently open, a full menu, and all user reviews Food Items ● Guests/users can search food items by restaurant name. ● Users (restaurant admin) can create new food items for sale and change the menu item information (via add and delete options). Reviews ● Summary ratings for reviews; after any query, the review page displays the resulting number of reviews and the average rating. ● Guests/users can search reviews by keyword. ● A logged in user can update/delete reviews that they wrote (they cannot do so for reviews other users have written). The link to this interface is in the user account view. ● Ability to leave reviews anonymously. Anonymous reviews will hide the user’s name when displayed. Recommendations ● Guests/users can view advanced information about a specific recommendation: associated foods and nutritional summaries. ● Guests/users can see information about trending food items based on # of total mentions and total popularity (w/ SQL views) ● Users can update an existing owned recommendation, inputting new fields or attaching additional photos, food items, tags, etc. ● Users can delete an existing owned recommendation. Cross Comparisons ● Guests/users can see a table of the top 5 most frequently compared food items, table also maintains reciprocity (food1 vs food2 should have the same frequency as food2 vs food1), table also updates with each comparison. ● Guests/users can generate scatter plots to visualize the relationship between two categories.

Team Members: Alec Liu, Mia Malden, Celina Ma, Nirvan Silswal, Jeffery Tan, Allison Taub
