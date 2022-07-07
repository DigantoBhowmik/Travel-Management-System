# Travel-Management-System



Type of users

-1. Admin
   - Admin can create admins
   - Admin can delete and edit customers and agents
   - Admin can delete and edit packages and events
   
-2. Agent
   - Agent can create, edit and delete packages and events
   - Agent can see which user bought their which packages and events
   
-3. Customer
   - Customer can buy packages and events
   - Customer can see which packages and events bought from which agent


### Domain

- [x] 1. Login/Registration
- [x] 2. Navbar
- [x] 3. Profile
- [x] 4. Home
- [x] 5. Package
- [x] 6. Event

### View

- [x] 1. Login/Registration
   - Title Label `Welcome or Login or Register`
   - User Name with `validation`
   - User Email `must be unique`
   - Phone with `validation`
   - Password `must be between 6 to 12`
   - Confirm Password `Password must matched`
   - Register Button `onClick()-> Start session and take into the home page with user's information`
   

- [X] 2. Navbar
   - Home `onClick()->move to Home view`
   - User Name Label `onClick()->show user profile where user can edit their profile`
   - Package `onClick()->move to Package view`
   - Event `onClick()->move to Event`
   
- [x] 3. Profile
   - Navbar
   - All user can edit their profile

- [x] 4. Home
   - Navbar
   - Short lists of packages
   - Short lists of event

- [x] 5. Package
   - Navbar
   - List of all packages `onClick()->show the package details` and `user can buy that package`
   
- [x] 6. Event
   - Navbar
   - List of all events `onClick()->show the event details` and `user can buy that event`

