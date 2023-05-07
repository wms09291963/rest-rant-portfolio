# Project REST-Rant

REST-Rant is an app where users can review restaurants.

Here are the routes defined

| Method | Path | Purpose|
| -------- | -------- | -------- |
| GET    | /  | Home Page  |
| GET    | /places  | Places index page |
| POST   | /places | Create new place
| GET    | /places/new | Form page for creating new place
| GET    | /places/:id | Details about a particular place
| PUT    | /places/:id | Update a particular place
| GET    | /places/:id/edit | Form page for editing an existing place
| DELETE | /places/:id | Delete a particular place
| POST   | /places/:id/rant | Create a rant (comment) about a particular place
| DELETE | /places/:id/rant/:rantid | Delete a rant (comment) about a particular place
| GET    | * | 404 page (matches any route not defined above)


Here's a list of places

| Name | City | State | Cuisines |
| -------- | -------- | -------- |
| Jack Stack BBQ |Kansas City   | MO | BBQ |
| Plaza III    | Kansas City | MO | Steakhouse |
| Manny's   | Kansas City | MO |Mexican |
| The Bristol   | Kansas City | MO | Seafood |

