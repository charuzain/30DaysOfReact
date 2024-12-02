Day 1:


Inside the src folder, create a new file, Counter.js. This will house your counter logic.
Import useState from React—this will help you manage the count state.
Add a basic UI:
A heading to display the current count.
Three buttons: Increment, Decrement, and Reset.
Add basic functionality to make the buttons work:
Clicking Increment increases the count.
Clicking Decrement decreases the count.
Clicking Reset sets the count back to zero.
Step 3: Integrate the Counter
Import the Counter component into App.js and render it there.
Test that your buttons are working correctly.
Challenges
Disable the Decrement Button at Zero: Prevent the user from reducing the count below zero.

Hint: Use conditional rendering or the disabled attribute.
Add a Dynamic Color Change: Change the text color of the counter based on its value:

Positive numbers: Green
Zero: Black
Negative numbers: Red
Hint: Use inline styles or dynamic classes.
Limit the Counter Range: Set a maximum count (e.g., 10). Once the counter reaches this value, disable the Increment button.

Hint: Compare the count value before updating it.
Add Step Increments: Let the user input a step value (e.g., 2) and increment/decrement by that step instead of 1.

Hint: Use a controlled input field (<input />) and read its value.
Keep Count Persistent: Store the count value in localStorage so it stays the same even if you refresh the page.

Hint: Use the useEffect hook to read/write to localStorage.
Stretch Challenge
Add Animations: Use simple animations to make the count "pop" when it changes. Try using CSS transitions or explore a library like Framer Motion.
Learning Strategist: Remember, the goal isn’t just to complete the app but to reflect on what you’re learning. After finishing today’s project, ask yourself:

How does the useState hook work, and where might you use it in future apps?
Were there any challenges or bugs? How did you solve them?
How could this app be extended further?
When you're ready, share your progress, and we can discuss your solutions! 🚀