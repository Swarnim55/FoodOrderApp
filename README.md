# [FoodOrderApp] (https://swarnim-reactmeals.netlify.app/)

A simple Food Order App with ReactJs

1. Created React App using create-react-app.
2. Created multiple components and assets sections.
3. Added a Header Component with background Image in Layout.
4. Created, Added and styled the "Cart" Button Component in Layout and Header Component.
5. Added Meals Components with dummy meals data and summarys.
6. Added Individual Meal Items, created Card and meal components.
7. Added Form, Input Component to MealItems
8. Worked along Cart component and styling.
9. Created a Overlay Modal for Cart Component via ReactPortal and passed to index.html via CreateReactPortal
10. Implemented Cart with some dummy data and states, used props for reusability and scalability.
11. Created Context for the Cart using ContextAPI and Provided it to all the components which needs the cart-context data.
12. Used to Context in Header Cart Button, and assigned the total added items to the badge using Reducer() method.
13. Added a Reducer function to the Cart Provider to update the items and amount in the context when added.
14. Added forwardRef to input component to enable useRef for mealsForm, updated amount in cart consuming the addItems function from the context.
