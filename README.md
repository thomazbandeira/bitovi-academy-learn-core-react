# Academy of Bitovi - Core React (Review)


I was interested in taking this class to return to being full stack. My strong point is currently Backend or solution architecture.


## What is React?


React is a front-end JavaScript library designed for building scalable and dynamic web applications. It’s renowned for its ability to break down the view layer of applications into small, reusable components, which are rendered as plain HTML. These components make up the core of React’s architecture, allowing for efficient and manageable development.

React is versatile and isn’t limited to web apps. It can also be used for creating mobile and desktop apps through platforms like React Native for mobile development and Electron for desktop applications. While this course focuses on web development, the concepts apply across these different environments.

## First step (First day)


[setting-up-your-environment](https://www.bitovi.com/academy/learn-react/setting-up-your-environment.html)

Branch: [01-setting-up-your-environment](https://github.com/thomazbandeira/bitovi-academy-learn-core-react/tree/01-setting-up-your-environment)


## Second step (First day)


[Introduction to JSX](https://www.bitovi.com/academy/learn-react/intro-to-jsx.html)

Branch: [02-introduction-to-jsx](https://github.com/thomazbandeira/bitovi-academy-learn-core-react/tree/02-introduction-to-jsx)

#### Exercise 01


copy broken test and implement html to JSX

#### Exercise 02


01 - Update the existing JSX to render the list of restaurants

02 - Use Array.map() to iterate over the restaurants.data

03 - Make sure to use key inside the .map()

04 - Render <p>No restaurants.</p> if, hypothetically, there weren’t any restaurants.

## Third step (First day)


[Building Components](https://www.bitovi.com/academy/learn-react/components.html)

Branch: [03-building-Components](https://github.com/thomazbandeira/bitovi-academy-learn-core-react/blob/03-building-components)


#### SETUP


 Create src/pages/ (folder)

 Create src/pages/RestaurantList/ (folder)

 Create src/pages/RestaurantList/index.ts

 Create src/pages/RestaurantList/RestaurantList.tsx

 Update src/App.tsx

 Create src/pages/RestaurantList/RestaurantList.test.tsx

 Update src/App.test.tsx

 #### Exercise 01 


 01 - Move the logic in our App component to our new RestaurantList component.
 
 02 - Update our App component to use our new RestaurantList component.

 ## Fourth step (First day)

[Passing Props](https://www.bitovi.com/academy/learn-react/components.html)

Branch: [04-passing-props](https://github.com/thomazbandeira/bitovi-academy-learn-core-react/tree/04-passing-props)


#### SETUP


Create src/pages/RestaurantList/ListItem.tsx

Update src/pages/RestaurantList/RestaurantList.tsx

 Create src/pages/RestaurantList/ListItem.test.tsx


  #### Exercise 01 

  01 - Update ListItem to accept props with restaurant data.

  02 - Alter ListItem to return the JSX for a single item in restaurants.data, use props for the variable data.

  03 - Refactor RestaurantList to use ListItem to render the items in restaurants.data.

## Fifth step (First day)

[Routing in React](https://www.bitovi.com/academy/learn-react/routing.html)

Branch: [05-routing-in-react](https://github.com/thomazbandeira/bitovi-academy-learn-core-react/tree/05-routing-in-react)


#### SETUP

Run: npm install react-router-dom@6

 Create src/pages/Home/ (folder)

 Create src/pages/Home/index.ts

 Create src/pages/Home/Home.tsx

 Update src/App.tsx

 Update src/main.tsx

 Create src/pages/Home/Home.test.tsx

 Update src/App.test.tsx

  #### Exercise 01 

  01 - Create routes for the <Home> component and <RestaurantList> component. When the route is "", the <Home> component should display, and when the route is /restaurants then the <RestaurantList> component should display. These changes should be made in src/App.tsx and src/main.tsx..

## Sixth step (First day)

[Styling in React](https://www.bitovi.com/academy/learn-react/styling-in-react.html)

Branch: [06-styling-in-react](https://github.com/thomazbandeira/bitovi-academy-learn-core-react/tree/06-styling-in-react)


#### SETUP

Create src/pages/Home/Home.module.css

Update src/pages/Home/Home.test.tsx



  #### Exercise 01 

  01 - Now that we’ve learned to apply styling in React with CSS Modules, it’s time to practice by styling a link in the Home component. You’ll bring in a Link component from React Router.

Update the styles in Home.module.css to be usable as a CSS Module.
Update the <Home> component to include a styled link:
Use <Link> (from the previous section!) to create a link to the /restaurants page.
Import the styles from Home.module.css and apply them to the new link.

## seventh step (First day)

[Managing State in React](https://www.bitovi.com/academy/learn-react/stateful-hooks.html)

Branch: [07-managing-state-in-react](https://github.com/thomazbandeira/bitovi-academy-learn-core-react/tree/07-managing-state-in-react)


#### SETUP 01

Update src/pages/RestaurantList/RestaurantList.tsx to include the State and City dropdown lists.

Update src/pages/RestaurantList/RestaurantList.test.tsx



  #### Exercise 01 

  01 - Let’s create buttons for each state that we can select. Then, when the button for a state is activated, we want to keep track of which state was choosen.

Call useState() to get a state variable and setState setter.
Create a helper function that takes a short state name and calls setState.
Add an onClick handler to the button that calls your helper function.
Update the paragraph to show the currently-selected state.

#### SETUP 02

Update src/pages/RestaurantList/RestaurantList.tsx

Update src/pages/RestaurantList/RestaurantList.test.tsx

#### Exercise 02

01 - Similar to our state buttons, let’s create buttons for selecting a city.

Call useState() to get a city variable and setCity setter.
Filter the cities list based on which state is selected.
Create a helper function that takes a cityName and calls setCity.
Add an onClick handler to the button that calls your helper function.
Update the paragraph to show the currently-selected city.
Hint: Use Array.filter() to narrow down the list of cities based on which state is selected.