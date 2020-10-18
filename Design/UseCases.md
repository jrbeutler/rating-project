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

- UC2: Check ratings
  - Through doing this, the apprentice will know who to talk to about any questions they may have on the rating and why they received the number they did. This connects to our BR5. All actors are involved, Admins, FTEs, and Apprentices.
  - Flow:
    - Login
    - Choose rating categories
    - Choose category
    - Show list of ratings

- UC3: Check comments
  - Through doing this, the apprentice will know who to talk to about any questions they may have on the rating and why they received the number they did. This connects to our BR5. All actors are involved, Admins, FTEs, and Apprentices.
  - Flow:
    - Login
    - Choose rating categories
    - Choose category
    - Show list of comments
    
- UC4: Rating apprentices
  - This is a use case because the functionality of this feature is the main goal of our product. This use case is an example  of how our BR1 would work. This would involve all three of our actors, Admins, FTEs and Apprentices
  - Flow:
    - Login
    - Click rate an apprentice
    - Choose apprentice
    - Choose category
    - Input Rating from 1 to 5
    - Click rate apprentice

- UC5: Leave comment(s) for apprentices
  - This will allow the apprentice to know where they are falling short in a given subject. Through this they will be able to work on it and grow. This connects to our BR5. All actors are involved, Admins, FTEs, and Apprentices.
  - Flow:
    - Login
    - Click rate an apprentice
    - Choose apprentice
    - Choose category
    - Input comment(s)
    - Click rate apprentice

- UC6: Edit comment(s) (Only ones you created)
  - Doing this will allow only the person who left the comment to be able to change what they said if improvements are made or if new information pops up. This use case is an example  of how our BR9 would work. This would involve all three of our actors, Admins, FTEs and Apprentices
  - Flow:
    - Login
    - Choose ratings given
    - Choose desired comment(s)
    - Click edit
    - Input edit
    - Click rate apprentice

- UC7: Edit rating(s) (Only ones you created)
  - Doing this will allow only the person who left the rating to be able to change what they said if improvements are made or if new information pops up. This use case is an example  of how our BR9 would work. This would involve all three of our actors, Admins, FTEs and Apprentices
  - Flow:
    - Login
    - Choose ratings given
    - Choose desired rating
    - Click edit
    - Input edit
    - Click rate apprentice

- UC8: Add apprentices/FTEs (Admins only)
  - Since admins will be in charge of the application, they will have the power to add and remove the apprentices, and full time employees as necessary. This would only involve one of our actors, the admins. This also ties into our BR8.
  - Flow:
    - Login
    - Click apprentices
    - Click add new apprentice
    - Input new personnel information
    - Click add new apprentice

- UC9: Remove apprentices/FTE's (Admins only)
  - Since admins will be in charge of the application, they will have the power to add and remove the apprentices, and full time employees as necessary. This would only involve one of our actors, the admins. This also ties into our BR8.
  - Flow:
  - Flow:
    - Login
    - Choose apprentices
    - Choose desired apprentice
    - Click edit
    - Click archive
    - Confirm archive
