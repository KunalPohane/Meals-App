# Meals-App
Meals App


**1. `localStorage` Initialization:**

   - Purpose: Initializes a favorites meal array in local storage if it doesn't exist.
   - Description: Checks if the "favouritesList" item exists in local storage. If not, it initializes it as an empty array.

**2. `fetchMealsFromApi` Function:**

   - Purpose: Fetches meals from an API.
   - Description: This asynchronous function takes a URL and a value as parameters, fetches data from the API by appending the value to the URL, and returns the meals data.

**3. `showMealList` Function:**

   - Purpose: Displays meal cards in the main section based on search input value.
   - Description: Retrieves the search input value, fetches meals from the API, generates HTML for each meal card including favorite status, and updates the main section with the generated HTML.

**4. `showMealDetails` Function:**

   - Purpose: Displays full meal details in the main section.
   - Description: Retrieves meal details by ID from the API, generates HTML for displaying details including meal name, category, area, instructions, and a link to watch a video if available, and updates the main section with the generated HTML.

**5. `showFavMealList` Function:**

   - Purpose: Displays all favorite meals in the favorites section.
   - Description: Retrieves favorite meal IDs from local storage, fetches meal details for each ID from the API, generates HTML for displaying favorite meal cards, and updates the favorites section with the generated HTML. If there are no favorite meals, it displays a message indicating so.

**6. `addRemoveToFavList` Function:**
   - Purpose: Adds or removes meals from the favorites list.
   - Description: Retrieves favorite meal IDs from local storage, checks if the meal is already in the favorites list, adds it if not, or removes it if already present. Then, it updates the favorites list in local storage and refreshes both the meal list and favorites list display. Displays an alert message indicating whether the meal was added or removed from the favorites list.

 
