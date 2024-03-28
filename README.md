Features
Displays menu items for Starters, Main Courses, and Desserts.
Allows users to click on items to add them to the order.
Calculates and updates the total order price.
How to Use
Menu Data: The menu is defined in a JavaScript object named menu. You can edit this object to update the menu items.

Displaying Menu: The displayMenuItems function renders the menu on the webpage. It creates elements for each category and item, and adds event listeners for adding items to the order.

Adding to Order: Clicking on a menu item adds it to the order list and updates the total price.

Initialization: Call initMenuSystem(menu) to start the menu system.

Challenges
Event Handling: Implementing click event listeners for each menu item.
Dynamic DOM Manipulation: Creating and updating DOM elements based on user interactions.
Learning Experience
DOM Manipulation: Learned how to dynamically create, append, and update DOM elements using JavaScript.
Event Delegation: Used event delegation to handle events more efficiently.
Code Organization: Improved code organization by separating concerns into functions.
Improvements
Accessibility: Enhance accessibility with ARIA attributes and keyboard navigation.
Animations: Add animations for a better user experience.
Responsive Design: Ensure the menu system works well on different devices.
