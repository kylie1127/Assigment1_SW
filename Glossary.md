Users: University Students in BC who are whether GUS or individual student 

ID: student’s account and personal informations such as their student number and verification 

Platform: the place or hub for the users such as social media and application that helps with events 

Group of university Students (GUS): A group of students who run activities based on their purpose. Such as clubs or student unions. 

| Data Item | Data Type | Data Format | Description | Validation |
|-----------|-----------|-------------|-------------|------------|
| StudentID | String | A-Z, 0-9 | Unique student ID for each user | Only Strings |
| UserID | Integer | 0-9 | Unique identifier for each user | Only integers |
| Username | String | A-Z, 0-9 | The name chosen by the user | Only strings |
| Password | String | A-Z, 0-9, special characters | Hashed password for the user | Only strings |
| Email | String | A-Z, 0-9, @, . | Email address of the user | Valid email format |
| DateJoined | Date | YYYY-MM-DD | The date the user joined the app | Valid date format |
| ProfileID | Integer | 0-9 | Unique identifier for each profile | Only integers |
| Bio | String | A-Z, 0-9 | A short bio about the user | Only strings |
| ProfilePicture | Blob | - | The user's profile picture | Valid image format |
| PostID | Integer | 0-9 | Unique identifier for each post | Only integers |
| Content (Post) | String | A-Z, 0-9 | The content of the post | Only strings |
| DatePosted | Date | YYYY-MM-DD | The date the post was created | Valid date format |
| CommentID | Integer | 0-9 | Unique identifier for each comment | Only integers |
| Content (Comment) | String | A-Z, 0-9 | The content of the comment | Only strings |
| DateCommented | Date | YYYY-MM-DD | The date the comment was made | Valid date format |

