# Hearts and Hands Web Site

## Features

### User

* User should see the Splash page by going to "hearts&hands.com/"
* User should see a nav bar at the top of every page with:
  * Icon for Hearts and Hands and Name. When clicked, user should see Splash page
  * Link to "Smoothie Menu"
  * Link to "Drink Menu"
  * Link to "Breakfast Menu"
  * Link to "Lunch Menu"
* User should see a footer section with website license at the bottom of every page


#### Splash Page

* User should see from top to bottom:
  * Photo Carousel
    * Should be able to click through photos
  * Deals (2-3 Boxes Overlaying Photo Carousel)
    * User should be able to click on link to see menu for item(s) in the deal
  * Special Message Section (if admin has added one)
  * Mission Statement Section
  * Contact Information Section

![alt-text](https://github.com/LinaShadrach/HeartsAndHands/blob/master/splash-img.png)

#### Menu Page

* User should see from top to bottom:
  * Smoothie Menu
  * Drink Menu
  * Breakfast Menu
  * Snack Menu
* On each menu, user should see:
  * Menu Name
  * Menu Items in rows. For each menu item the user should see:
    * Item name
    * Item description
    * Item price
    * "New" flag on recently added items

### Admin

#### Login/Logoff

* When not signed in:
  * Admin should see a login form by going to "hearts&hands.com/admin"
* When signed in:
  * Admin should see Splash page from user perspective by going to "hearts&hands.com/admin"
  * Admin should see a logoff button in the nav bar
  * Admin should be able to use site from user perspective
  * Admin should see "Update" button on each page when viewing site from user perspective

_**Note**: All admin features described below are available only when the admin is signed in._

#### Update Splash Page

* Admin should be able to:
  * Update Title
  * Update Deals (2-3)
  * Add/Remove Special Message
  * Add/Remove photos in carousel (minimum 4, can add and delete)
  * Update Mission Statement
  * Update Contact Information: Location, Hours, Phone Number
  * Click a "Save Changes" button to save changes.
    * Should see Splash page from user perspective after clicking "Save Changes" button.
  * Click a "Cancel" button to cancel changes.
    * Should see Splash page from user perspective after clicking "Cancel" button.


#### Update Menus

* Admin should be able to:
  * View items grouped by menu.
  * Add, remove, and update menu items. Each menu item must have the following:
    * Name
    * Description
    * Price
  * Ability to add "New" flag to items
  * Update Deals
  * Click a "Save Changes" button to save changes.
    * Should see Menu page from user perspective after clicking "Save Changes" button.
  * Click a "Cancel" button to cancel changes.
    * Should see Menu page from user perspective after clicking "Cancel" button.
