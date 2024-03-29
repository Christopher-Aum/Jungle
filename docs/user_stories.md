# User Stories

## Users

### Sign Up

* As an unregistered and unauthorized user, I want to be able to sign up for the website via a sign-up form.
  * When I'm on the `/signup` page:
    * I would like to be able to enter my email, username, and preferred password on a clearly laid out form.
    * I would like the website to log me in upon successful completion of the sign-up form.
      * So that I can seamlessly access the site's functionality
  * When I enter invalid data on the sign-up form:
    * I would like the website to inform me of the validations I failed to pass, and repopulate the form with my valid entries (except my password).
    * So that I can try again without needing to refill forms I entered valid data into.

### Log in

* As a registered and unauthorized user, I want to be able to log in to the website via a log-in form.
  * When I'm on the `/login` page:
    * I would like to be able to enter my email and password on a clearly laid out form.
    * I would like the website to log me in upon successful completion of the log-in form.
      * So that I can seamlessly access the site's functionality
  * When I enter invalid data on the log-in form:
    * I would like the website to inform me of the validations I failed to pass, and repopulate the form with my valid entries (except my password).
      * So that I can try again without needing to refill forms I entered valid data into.

### Demo User

* As an unregistered and unauthorized user, I would like an easy to find and clear button on both the `/signup` and `/login` pages to allow me to visit the site as a guest without signing up or logging in.
  * When I'm on either the `/signup` or `/login` pages:
    * I can click on a Demo User button to log me in and allow me access as a normal user.
      * So that I can test the site's features and functionality without needing to stop and enter credentials.

### Log Out

* As a logged in user, I want to log out via an easy to find log out button on the navigation bar.
  * While on any page of the site:
    * I can log out of my account and be redirected to a page displaying recent songs.
      * So that I can easily log out to keep my information secure.

## Items

### Viewing Items

* As a logged in _or_ logged out user, I want to be able to view a selection of the items available, whether of the entire list, or individually

### Creating Items

* As a logged in user, I want to be able to post a new item
    * When I'm on the `/new-item` page:
        * I can post and specify the Name, Type of item, and Description
        * Able to upload: Image

### Updating Items

* As a logged in user, I want to be able to update my item(s)
    * When I'm on the `/:username/:itemname`:
        * I can click 'Edit' to make permanent, new changes to the item

### Deleting Items

* As a logged in user, I want to be able to delete my item(s)
    * When I'm on the `/:username/:itemname`:
        * I can click 'Delete' to permanently remove the item

## Comments

### Getting Comments

* As a logged in _or_ logged out user, I can see comments on any `/:username/:itemname` page if there are any

### Creating Comments

* As a logged in user, I want to be able to make a comment

### Updating Comments

* As a logged in user, I want to be able to edit a comment I have made

### Deleting Comments

* As a logged in user, I want to be able to delete a comment I have made
