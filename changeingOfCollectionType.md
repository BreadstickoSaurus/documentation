# How difficult would it be to changes from Games to something else

The hardest project to change would be the backend since every model, controller, repository, and endpoint needs changing.  
This includes updating the data models to reflect the new collection type, modifying the business logic in the controllers,  
and ensuring that the repositories interact correctly with the new data structures. Additionally, all endpoints that  
expose the data via the API will need to be updated to handle the new collection type. However, the general layout and  
how the code works could be reused.

The frontend would be slightly easier, mainly how the data is handled and some UI elements. This involves updating the  
data fetching logic to call the new endpoints, modifying the state management to store and manipulate the new data type,  
and updating the UI components to display the new data correctly. Some styling adjustments might also be necessary to  
accommodate the new data presentation.

The database has to be fully reworked. This includes designing new tables or collections to store the new data type,  
migrating existing data if necessary, and updating any database queries to interact with the new schema. Indexes and  
relationships may also need to be adjusted to optimize performance for the new data structure.