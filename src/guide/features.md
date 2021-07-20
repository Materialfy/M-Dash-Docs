# Dashboard Features


![Crud Table](https://github.com/ClintOxx/M-Dashboard-Materialfy/blob/master/public/img/Screenshot%202021-07-15%20at%2021-28-53%20M-Dashboard%20by%20Materialfy%20.png)
- **CRUD Data Table** with sorting, pagination, searching, display images...
- Data Tables can:
  - Create
  - Read
  - Update/POST
  - Delete
  - Search filter:
    - Using search bar for filtering table content
    - Sorting by column
  - data table allows selection of the number of records per page, page transition and sorting,
  - Inline table editing
  - Edit item dialog
  - Rest APi support built in
  - dynamic table headers

- **Features**
  - data in demo that requests from https://reqres.in/ 
  - A cool user page?(lol) 
  - Support for REST Api's
  - Dark/light themes, theme colors, components, sidebar images, site name, colors, logo, Menu and footer...

- **Login**
  - login form (communication with rest API via axios, basic validation),
  - redirecting to from login depending on auth status and JWT
  - Gets JWT Refresh token once its expires(pretty sure we put that in)
  - stores JWT in secured local storage(using Secure-LS)
  - beforeEach Router gaurds in router/index.js
  - better off using Auth0


# Whats New in 2.0:

* rewrote from the ground up to fix many of the lingering issues and to make this simplier, easier to read and easier to miantain.
* Redid the design to make it simplier and less neon boy wonder cyberpunktastic
* Removed some baggage that was adding unnecessary weight to the project
* provided in file documentation on many of the more poterinally confusing things, some might have said we went too far.
* fixed routing issues forreal this time
* the process to get it up and running should be simplier now
* the documentation should actually exist now 
* functional basic noticiation component hooked up to state, same for new User Snippets component and settings
* theme picker and dark mode toggle
* toggle side nav drawer to temporary pop up or persistant 
* made a new user page then redid it at the last minute and made another when i should have been sleeping 
* made tables and card components with slots and props that are plug and play 
* 17 custom components
* idk man 
