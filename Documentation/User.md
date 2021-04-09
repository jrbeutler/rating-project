# This is a document to help users get familiar with the Rating Project

### Admin view

#### Login Page

Web View :
![Login Page](https://github.com/Eli017/rating-project/blob/master/Documentation/Images/Login%20page.png)
Mobile View: \
![Mobile Login](https://github.com/Eli017/rating-project/blob/master/Documentation/Images/Mobile%20login%20page.png)

1. The input box for the user to enter their current email address for their
2. The input box for the user to enter their temporary/current password that matches the email placed above
3. The eye icon that shows/hides the user's password based on if there is a line through the eye or not. Clicking on the icon will switch from hide to show and vice versa (Not a step in the Mobile View, replace with step 4).
4. The Login button, to be used when both input boxes above are filled with the required information. It will take this info, run it through the database, find the exact person and log them in under their credentials (Step 3 in the Mobile view).
5. Mobile Landing Page preview to showcase web application's mobile friendly settings.

#### Landing Page

Web View :
![Landing Page](https://github.com/Eli017/rating-project/blob/master/Documentation/Images/Account%20Page%20Ratings.png)
Mobile View : \
![Mobile Landing](https://github.com/Eli017/rating-project/blob/master/Documentation/Images/Account%20landing%20page%20-%20admin.png)

1. The User's name and their position (Admin/User/Full-Time Employee)
2. The User's overall rating on all categories.
3. Only available to Admins and Full-Time Employees. This button will take you to the manage content page where categories and users can be updated.
4. The current Rating Categories and the ratings the user has given to others.

- The Ratings Given will have the ratings the user has given to any apprentices based on dates.
- Rating Categories continued in Landing Page Cont.

6. The Edit Profile button. Used to change any information in the system, whether that be the person's name, or to update the current password.
7. The Page menu of the application. This will allow the User to travel to the rating page and return to their personal Profile page by clicking the EduSource logo. If the user is an Admin, they will also have the View Apprentices page available.

#### Landing Page Cont.

![Landing Page cont](https://github.com/Eli017/rating-project/blob/master/Documentation/Images/Account%20Page%20Categories.png) 8. The rating categories side page of the Landing/Profile main page

- The Rating Categories will have the users own personal overall score in each category, and will each be clickable to take to a separate page with more details on each category.

#### Category Page

![Category Page](https://github.com/Eli017/rating-project/blob/master/Documentation/Images/Category%20page.png)

1. The name of the Category being viewed.
2. The graph that shows the ratings of a user over time with a best-fit line to view performance.
3. The individual reviews the user has received in this Category, sorted by date.

#### Rating Page

![Rating Page](https://github.com/Eli017/rating-project/blob/master/Documentation/Images/Rate%20apprentice%20page.png)

1. The dropbox for choosing which apprentice to rate. (Required)
2. The dropbox for chooosing which category to rate the apprentice on. (Required)
3. The rating that will be given on the category selected. (Required)
4. Any comments on the selected apprentice will be entered here. (Not required)
5. After all the information has been entered, clicking this button will submit the review to the selected Apprentice.

#### Manage Content Page

![Manage Content, Categories](https://github.com/Eli017/rating-project/blob/master/Documentation/Images/Manage%20Content%20Categories.png)

1. Select between managing Categories or Users.
2. Select a category from a list to archive.
3. Select a category from a list to reactivate.
4. Enter a new category into the system.

![Manage Content, Users](<https://github.com/Eli017/rating-project/blob/master/Documentation/Images/Manage%20Content%20Users(1).png>)

5. Select a user from the list and change their role from either Apprentice, Full-Time Employee, or Admin.
6. Select a user from a list to archive.

![Manage Content, Users (continued)](<https://github.com/Eli017/rating-project/blob/master/Documentation/Images/Manage%20Content%20Users(2).png>)

7. Select a user from a list to reactivate.
8. Enter in a new user's information to add them into the system.

#### Edit Profile Page

![Edit Profile](https://github.com/Eli017/rating-project/blob/master/Documentation/Images/Edit%20profile%20page.png)

1. The User's new first name if they are deciding to change it.
2. The User's new last name if they are deciding to change it.
3. The User's old password must be entered to change to a new password.
4. The User's new password that must be different than the old password.
5. The submit button to save all the changes and update the user's information.

#### View Apprentices Page

![Apprentices Page](https://github.com/Eli017/rating-project/blob/master/Documentation/Images/Apprentices%20page.png)

1. The list of all Users with their names and role.
2. A link to view a User's page with their overall rating and individual category ratings.
