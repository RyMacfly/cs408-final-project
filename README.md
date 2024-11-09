# Online Recipe Collection

## Project Spec

# 1. Introduction and Theme

The Online Recipe Collection project is designed as a recipe repository website where users can share, discover, and discuss various recipes. With food blogs, social media recipe accounts, and cooking communities growing in popularity, this site aims to provide a centralized platform for food enthusiasts. The site allows users to contribute their recipes, browse through a collection of diverse dishes, and interact with each other by leaving comments, tips, and variations.

The project is built to support users looking for culinary inspiration and offers a platform for members to save, edit, and manage their own recipes while also contributing to a larger collection. Users will be able to browse different cuisine types and dietary options, making the site ideal for those with specific dietary needs or simply for cooks seeking new dishes to try.

# 2. Site Functionality

The Online Recipe Collection site offers a range of features to ensure users have an engaging, interactive experience.

- Recipe Submission: The home page includes a form for users to submit new recipes. This form collects important information like the recipe’s name, ingredients, cooking instructions, dietary restrictions, and an image of the dish. When a user submits a recipe, the data is stored in an AWS database, ensuring that each submission is recorded and can be retrieved and displayed later.

- Recipe Browsing and Filtering: The site includes a dedicated “All Recipes” page where users can browse the full recipe database. The page allows for filters by cuisine type or dietary restriction, giving users a straightforward way to narrow down the results based on specific preferences. Each recipe is displayed in a brief card format with a title, main ingredients, and a link to a full view.

- Recipe Detail View: For users who want more information, each recipe has a dedicated detail page. This page provides all the information on the recipe, including step-by-step instructions, cooking time, serving size, and an image. The detail view helps users see all necessary information for making the dish.

- Recipe Discussion: Each recipe detail page also includes a discussion section where users can leave comments, ask questions, or share their own variations on the recipe. This feature fosters a sense of community and allows for shared knowledge, tips, and feedback that can enhance the user experience and improve recipe quality.

- Data Management: The site handles full CRUD operations, allowing users to add new recipes, retrieve all or filtered recipe entries, and delete their own submissions or comments if needed.

# 3. Target Audience

The Online Recipe Collection is tailored for a broad audience, making it accessible and useful to multiple types of users:

- Primary Audience: Home cooks, food enthusiasts, and amateur chefs who want to share recipes, experiment with new dishes, and access a variety of culinary options.
- Secondary Audience: Individuals with dietary needs, such as those following vegetarian, vegan, gluten-free, or low-carb diets. The site’s ability to filter by dietary restrictions and cuisine types makes it a valuable tool for this audience.
- Community Engagement: With a built-in discussion section, the site also caters to users who enjoy interacting with others, offering feedback, and sharing cooking tips.

This inclusive approach to the target audience not only helps build a strong user base but also enriches the recipe collection with diverse dishes and perspectives, making the site a versatile resource for anyone interested in cooking.

# 4. Data Management

To support its functionalities, the Online Recipe Collection project relies on a structured database to manage and store the dynamic data generated by user input. Key data includes:

- Recipes: Each recipe entry includes fields like the recipe name, cuisine type, dietary restrictions, cooking time, serving size, instructions, and an image. This data is stored in a Recipes table, allowing each entry to be retrieved, displayed, and managed.

- Ingredients: Each recipe has a list of ingredients stored in a separate table to allow for structured storage. Each ingredient is associated with a recipe ID, and includes fields like ingredient name, quantity, and unit of measurement, making it easy to manage and display ingredient lists.

- Comments: Each recipe’s discussion section is powered by a Comments table. This table stores user-generated comments for each recipe, providing an interactive space for discussion. Users can add, view, and delete their comments, creating a dynamic and responsive forum for each recipe.

- User Input: Dynamic data handled by the site includes all user-submitted recipe information, comments, and any filters or queries used to retrieve recipes. Forms for recipe submission and comments are built to sanitize and validate input, ensuring that only clean and safe data is stored.

# 5. Stretch Goals

Beyond the core functionalities, several stretch goals would enhance the project and create a more engaging user experience:

- User Profiles: Introducing user accounts and profiles would allow users to save favorite recipes, track their own contributions, and customize preferences based on dietary restrictions.

- Rating System: Implementing a star rating system would allow users to rate each recipe, helping other users identify popular recipes and top-rated dishes.

- Enhanced Search and Filtering: Expanding search and filtering options, such as ingredient-specific filters or time-based filters (e.g., recipes under 30 minutes), would improve the site’s usability and user experience.

# 6. Conclusion

The Online Recipe Collection project serves as a comprehensive platform for home cooks, food enthusiasts, and those with dietary restrictions to discover, share, and discuss recipes. By focusing on CRUD functionality, user-friendly forms, and interactive discussion sections, the site delivers value as a community-driven culinary resource.

This project’s design not only provides essential functionalities like recipe submission and retrieval but also promotes community engagement and shared culinary knowledge. The stretch goals outlined would elevate the site further, offering additional value and convenience to users. With these features, the Online Recipe Collection has the potential to become a go-to platform for anyone passionate about cooking and recipe discovery.

## Project Wireframe

TODO: Replace the wireframe below with you own design.

![image](https://github.com/user-attachments/assets/103ab4ef-6aa3-40f1-b010-519688b4a523)



