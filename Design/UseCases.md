# **Use Cases**
## **Actors**
### Admins
- The admin is the administrator of the entire program, and the administrator has the authority to allow or prevent FTE and apprentices from accessing the rating program.

### FTEs (full-time employees)
- FTEs can evaluate apprentices’ performance through programs, including rating a student from 1 dot to 5 dots, and optionally writing a note.

### Apprentices
- Apprentices need to obtain FTEs' evaluation of their performance in the project through this program, and apprentices can know their scores and comments left by FTMs.

## **Use Cases**
- UC1:Logging into application
  - For an application that will be saving information on different people this will be necessary. This connects to our BR2. All actors are involved, Admins, FTEs, and Apprentices. 
  - Flow:
    - Open site
    - Input email
    - Input password
    - Click submit

- UC2: Creating a login(account) **
  - Full Time Employees, Admins and Apprentices. BR8
  - Flow:
    - Open site
    - Click sign up
    - Input email and password
    - Click submit

- UC3: Check ratings
  - Through doing this, the apprentice will know who to talk to about any questions they may have on the rating and why they received the number they did. This connects to our BR5. All actors are involved, Admins, FTEs, and Apprentices.
  - Flow:
    - Login
    - Choose category
    - Choose ratings
    - Show list of ratings

- UC4: Check comments
  - Through doing this, the apprentice will know who to talk to about any questions they may have on the rating and why they received the number they did. This connects to our BR5. All actors are involved, Admins, FTEs, and Apprentices.
  - Flow:
    - Login
    - Choose category
    - Choose comments
    - Show list of comments
    
- UC5: Rating apprentices
  - This is a use case because the functionality of this feature is the main goal of our product. This use case is an example  of how our BR1 would work. This would involve all three of our actors, Admins, FTEs and Apprentices
  - Flow:
    - Login
    - Choose an apprentice
    - Choose category
    - Input Rating from 1 to 5

- UC6: Leave comment(s) for apprentices
  - This will allow the apprentice to know where they are falling short in a given subject. Through this they will be able to work on it and grow. This connects to our BR5. All actors are involved, Admins, FTEs, and Apprentices.
  - Flow:
    - Login
    - Choose apprentice
    - Choose category
    - Input comment(s)

- UC7: Edit comment(s) (Only ones you created)
  - Doing this will allow only the person who left the comment to be able to change what they said if improvements are made or if new information pops up. This use case is an example  of how our BR9 would work. This would involve all three of our actors, Admins, FTEs and Apprentices
  - Flow:
    - Login
    - Choose apprentice
    - Choose category
    - Choose comment(s)
    - Input edit
    - Click submit

- UC8: Edit rating(s) (Only ones you created)
  - Doing this will allow only the person who left the rating to be able to change what they said if improvements are made or if new information pops up. This use case is an example  of how our BR9 would work. This would involve all three of our actors, Admins, FTEs and Apprentices
  - Flow:
    - Login
    - Choose apprentice
    - Choose category
    - Choose rating(s)
    - Input edit
    - Click submit

- UC9: Add apprentices/FTEs (Admins only)
  - Since admins will be in charge of the application, they will have the power to add and remove the apprentices, and full time employees as necessary. This would only involve one of our actors, the admins. This also ties into our BR8.
  - Flow:
    - Login
    - Choose category
    - Choose add
    - Input new personnel information
    - Click submit

- UC10: Remove apprentices/FTEs (Admins only)
  - Since admins will be in charge of the application, they will have the power to add and remove the apprentices, and full time employees as necessary. This would only involve one of our actors, the admins. This also ties into our BR8.
  - Flow:
  - Flow:
    - Login
    - Choose category
    - Choose apprentice/FTE
    - Choose remove
    - Click submit
