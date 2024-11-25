# Requirements

## User Needs

### User stories
User Story’s: 
Register Account 
As a student, I want to register for an account, so that I can access the platform and find roommates. 
Set Preferences 
As a student, I want to set my preferences for roommates, so that I can find people who match my lifestyle and habits. 
Search for Roommates 
As a student, I want to search for potential roommates, so that I can find suitable matches quickly. 
View Roommate Profiles 
As a student, I want to view detailed profiles of potential roommates, so that I can make informed decisions about who to contact. 
Send Roommate Requests 
As a student, I want to send requests to potential roommates, so that I can start the conversation about living together. 
Match with Roommates 
As a student, I want to receive roommate suggestions based on compatibility, so that I can connect with individuals who are likely to be a good fit. 
Administer User Accounts 
As an admin, I want to manage user accounts and preferences, so that I can ensure the platform runs smoothly and addresses user needs. 
Provide Feedback 
As a student, I want to provide feedback on my roommate experiences, so that the platform can improve and help future users. 
Login/Logout 
As a student, I want to log in and out of my account, so that I can securely access my profile and preferences. 


### Actors
students
admin
roommate matching filter


### Use Cases table

create using word!!!!!!

![use case table]()
![alt text](<use case table.png>)

TODO: Your Use-Case diagram should include all use-cases.

![Insert your Use-Case Diagram Here](<use case diagram.png>)





## Software Requirements Specification
### Functional requirements
    Indicate which UC the requirement comes from.

Functional Requirements
For Students
FR1: Register Account

Description: Students should be able to create an account on the platform to access roommate matching and accommodation features. Users need a secure login with options for password recovery.
FR2: Set Preferences

Description: Students can specify their preferences for roommates (e.g., noise tolerance, lifestyle habits, academic schedules). The system should store these preferences securely and use them in the compatibility matching algorithm.
FR3: Search for Roommates

Description: Students can search for potential roommates using filters, such as location, lifestyle preferences, and budget. The search functionality should return suitable matches quickly and accurately.
FR4: View Roommate Profiles

Description: Students can view detailed profiles of potential roommates, including preferences, shared interests, and compatibility scores. Profiles should display all relevant details in an organized manner, while protecting private information.
FR5: Send Roommate Requests

Description: Students can send connection or roommate requests to other students. The system should allow users to accept, decline, or ignore roommate requests.
FR6: Match with Roommates

Description: Students receive roommate suggestions based on their preferences and compatibility criteria. The matching algorithm should take students' lifestyle habits and personal preferences into account to suggest compatible individuals.
FR7: Provide Feedback

Description: Students can provide feedback on their roommate experience to improve the matching system for future users. Feedback should be stored securely and used to enhance the roommate matching algorithm.
FR8: Login/Logout

Description: Students can log in and out of their accounts to access personal settings and preferences securely. The system should handle session management to protect user data.
For Admins
FR9: Administer User Accounts
Description: Admins can manage student accounts, including resetting passwords, updating account information, and handling user reports. Admins can also view and moderate profiles and preferences to ensure compliance with platform policies.
System Components
FR10: Roommate Matching Filter
Description: The platform should include a matching algorithm that filters and suggests roommates based on students' preferences and compatibility scores. The algorithm should be continuously improved based on user feedback and new data.

### Non-Functional Requirements
Indicate which UC the requirement comes from.

Non-Functional Requirements
NFR1: Usability

Description: The platform should have an intuitive user interface that allows students to easily set preferences, search for roommates, and send requests.
NFR2: Performance

Description: The system should deliver search results and roommate matches within seconds for an efficient user experience.
NFR3: Security

Description: User data, including preferences and account details, should be stored securely and handled in compliance with privacy regulations. Implement authentication and authorization protocols to prevent unauthorized access.
NFR4: Scalability

Description: The platform should be able to handle an increasing number of users and data as the user base grows.
NFR5: Reliability

Description: Ensure high uptime, with regular backups of user data to prevent data loss.
NFR6: Maintainability

Description: The system should be designed to allow for easy updates, especially in the matching algorithm and user interface.