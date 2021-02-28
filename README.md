# Mobile-Architect-Programming

## Requirements and goals
The requirements and goals of this inventory app was to design and develop a mobile inventory app to track user logins, items, quantities and notifications of low inventory.

## Screens and features
A login/register screen UI was needed along with two EditText, one for username and the other for password. One button is to register a new user with the username and password above the button. The other button Submit, is a poor choice of a name and will be changed in the future to Login. The next screen will be a grid with the first column for the item name and the second column for the quantity of items. To add an item there is a floating ‘+’ button which could bring up a dialog box with a text edit field to add a new item. Once an item is added it can also be deleted with a round trash can button. The item quantity can be changed either by pressing the increment or decrement buttons. The item quantity can also be adjusted by clicking on the EditText field which will be using the textEditNumber. The textEditNumber only allows the user to enter a number.

## UI Design
First UI design was not successful. The EditText fields and buttons had to be moved to the top of the screen to allow for a way to edit, save and create new inventory items. Below those items appears inventory items and quantities.

## Coding the app
The approach I took was to start with the first screen. Code and test the features of the first screen which was the login/register screen. Once the first screen was working properly development would start on the second screen and features. It's best to work on a single feature and test before starting to work on another feature.

## Testing
Code was tested using break points, logcat, and the Android emulator. Testing revealed errors that would not normally be found in code that was syntactically correct. Testing using the emulator helps reveal runtime errors.

## Innovate and overcome
I had to innovate and overcome a UI design and code issue mentioned above by moving and changing the way the inventory screen looked and functioned. Connecting SQLite, UI, and the controller to work together was rewarding experience.
