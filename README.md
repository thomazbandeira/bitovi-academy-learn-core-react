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