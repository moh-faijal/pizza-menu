This code represents a React application for a pizza restaurant's website. Here's a breakdown of its structure and functionality:

1. **Imports**: The code imports React, ReactDOM, and a CSS file for styling.

2. **Pizza Data**: An array named `pizzaData` holds information about different types of pizzas offered by the restaurant, including their names, ingredients, prices, photo filenames, and whether they are sold out or not.

3. **Components**:

   - **App**: The root component of the application. It renders a container div with `Header`, `Menu`, and `Footer` components.
   - **Header**: Renders the header of the website, displaying the restaurant name.
   - **Menu**: Renders the menu section, displaying a list of pizzas. It checks if there are pizzas available, and if so, it renders them dynamically using the `Pizza` component.
   - **Pizza**: Renders individual pizza items based on the data provided. It includes the pizza's image, name, ingredients, and price. If a pizza is sold out, it displays a "SOLD OUT" label.
   - **Footer**: Renders the footer section, displaying information about the restaurant's opening hours. It dynamically determines whether the restaurant is open or closed based on the current time.
   - **Order**: Renders an order section with a message indicating the restaurant's opening hours and an order button.

4. **Rendering**:
   - The `ReactDOM.createRoot` method is used to create a root instance for rendering the app.
   - The `App` component is rendered within a `React.StrictMode` wrapper.

Overall, this code creates a simple but functional React application for showcasing a pizza restaurant's menu and ordering options.
