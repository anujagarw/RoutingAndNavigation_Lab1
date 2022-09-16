Use ASP.NET CORE 6 and try to show Routing and navigation of page

Create an Empty ASP.NET Core MVC app. 

Create two modules one for Admin and one for User using Areas.

Admin module will have three pages – Login, dashboard and profile. Create a separate layout for admin pages having a navigation menu for the pages.

After providing login details (username and password) admin will navigate to the admin dashboard

The user module will have three pages – dashboard and profile. Create a separate layout for user pages having a navigation menu for the pages.

After providing login details (username and password) user will navigate to the user dashboard

Use attribute routing to define the routes for Admin and User modules.

Scenario:
1. To login user module, in user name text box pass the value 'user' and it will navigates to User Dashboard

2. To login Admin module, in user name text box pass the value 'admin' and it will navigates to Admin Dashboard
