# Delivereat

Repeat of Delivereat project with database.

Weekend project for Constructor Labs


## Running from source

- Clone this repo.
- Run `npm install` to install dependencies.
- Create a `.env` file to store your database credentials.
- Create a local database using the supplied queries in [database.sql](database.sql).
- Run `npm start` to to run the Node server with Nodemon.
- Run `npm run dev` to create a development build with webpack.
S
- This app was built with mobile-use in mind, it is advised that browser dev tools are used to replicate this.


NOTE: Due to styling issues, the project displays correctly only on larger mobile screens. (iPhone 6/7/8 Plus, iPhone X etc.). I aim to correct this as soon as possible.

## Features:

* Burgers can be customised with additional toppings. This works via additonal "toppings" and "toppings_map" tables in the database, and nested promises within the post request.

*
## Issues

* As mentioned above, styling is not correct.

* UX is not complete. I.e once you click a burger item you HAVE to add it to order before returning to menu.

* No feedback when sides are added to order - Need to add a footer bar akin to when a burger is added to order.

* Removing items is buggy, cannot be done for toppings. This is a carry over from master branch which had a much simpler format. Can be addressed with more time.

* Some functions replicated in different components, can be corrected with more time.

* Some components are very similar - tried just having different classes, but wouuld cause styling to mess up

## Further Plans

* Some hang overs from master branch - most popular is now not entirely useful when burger options are simply bases for customisation. With more time I would have liked for it to display most popular topping combinations.
