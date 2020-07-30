## unordered logic/brainstorm

* breed is selected and plant is created 
  // plant entry added to database with user_id and breed_id

* for every x minutes that passes from the plant's creation date, the water level drops y. 
  // when first logs in, app checks how much time has passed since last update, and calculates water level drop. while app runs, an internal clock runs in state. when x time passes, the water level in db is updated as well as in state.

* water level can be incremented by y by clicking button. 
  // when button is clicked, counter starts. for every second it is held down counter increases. when button is released, the total counter amount is used to update the water level in the rails db

* if the water level drops below 25% the plant has brown filter applied to it, maybe have 'withered' sprites.
  // need to ask ed about applying gradients to sprites.

* if the water level reaches 0, the plant dies and all features are disabled. the user is prompted to start again.
  // when water level (in state) reaches 0, the plant's alive boolean in db is updated to false as well as in state. if alive boolean is false in state, disable features. make 'try again' div visible.

* for every z minutes that the plant's water level is above 70%, the plant grows one stage.
  // ??

* when the plant reaches full size, the features are disabled and the user is allowed to start a second plant. // if growth attribute reaches maximum for that breed, water level stops dropping, features become disabled.

## ordered logic

front-end application starts

### app, home, about views

1. render view content

### sign up view

1. render form

**when user completes form and clicks submit.**

1. queries database to see if user exists with this username
2. queries database to see if password and other fields are valid
3. if all is valid, post new user to db database and render login page
4. if invalid, show errors in view on same view

### log in view

1. render form

**when user completes form and click 'log in'**

1. queries database to see if user exists with this username
2. queries database to see if password is valid
3. if all is valid, db responds with jwt token. render plants view.

### plants view

**when user successfully logs in.**

1. queries database for all plants belonging to user as well as for user's information including 'max plants allowed'
2. first checks alive boolean of plants.
3. check if any plants have finished growing, disable water level drop and features of those who have.
4. for plants that are alive and still growing, calculate current water level and start water level drop.
5. for plants that are alive, calculate how long water level was above 70% since last growth.
6. apply growth if necessary.
7. if any plant has reached max, increment user's 'allowed plants' by one. create 'plant finished' alert.
8. for plants that are still alive and growing, if plants are below 25%, apply brown filter or withering, create 'needs water' alert.
9. calculate correct status emojis and apply.
10. render plants in plants view, render any alerts. if user is allowed another plant, render 'create plant' button.

**when user clicks individual plant.**

1. check that plant is alive and/or finished (from props?) to check if features are enabled or not.
2. if plant is dead, render prompt to delete plant and start again.
3.  render features, water level, etc.

**when user clicks 'create new plant'.**

1. render 'create' view.

### plant view

**if user clicks watering can.**

	1. when button is clicked, counter starts. for every second it is held down counter increases. 
 	2. when button is released, the total counter amount is used to update the water level in the rails db as well as in state.

### create plant view

1. render form.
2. render carousal for choosing breed (?)

**when user fills out form and clicks create.**

1. post plant info to db.
2. if plant info invalid, display errors.
3. if valid, rails creates new plant entry.
4. render plants view.


Level System

Oauth
unlock
