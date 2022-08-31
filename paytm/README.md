## New things
1. customized font size inside the tailwind.config inside the script
2. Height max covers until the last element
3. border-red-600
4. border is required for the navbar texts only, otherwise you could use the justify-between for the parent div
## Common Errors
1. flex-col and not flex-cols
    1. The text is laid out in a line
    2. That is it is one single line
2. justify-center not working in section recharge "Recharge Prepaid Mobile
    1. Reason 1: The words do occupy the space available
    2. Reason 2: It couldn't go to the top due to less space
    2. Solution: To move with position
3. You need more detailed approach for 
4. Problems with grid
    1. Too hard for responsiveness
    2. Instead flex wrap
5. Image size should be different for different break point range
6. Show to a developer finished product
- Solution: double check
7. justify-content:space-between
- applied to the ul and not to the div parent of the ul
8. Hamburger menu hover not coming from the top
- You could give absolute to the div with items to make it absolute with the window
9. Hamburger
- This is the maximum possible with click on it and display the options
- For better responsiveness you need to have custom css involved
- Tailwind CSS is more time taking than custom CSS
- Custom is way to move forward
10. overflow-x-hidden not working inside the body
- Solution: you could add it inside the html tag

