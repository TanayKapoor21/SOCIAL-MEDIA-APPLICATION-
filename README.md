# SOCIAL-MEDIA-APPLICATION-
This is a Java application that will help users to create a profile on a social media application. 
Social media is an internet-based form of communication. Social media platforms allow users to have conversations, share information, and create web content.
This app would be helpful for a user to create social media profile, send friend requests to users, post media content on the application, comment on a friend’s post, and receive notifications.

#Description

A basic social media application that allows users to create profiles, connect with friends, share posts, and comment on posts.

#Definition Of Done:

The application will consist of the following features:
I.	User Profiles: Users will be able to create profiles that include their name, profile picture, and other personal information. Users will be able to view and edit their profiles, and other users can also view their profiles.

II.	Friends Network: Users will be able to connect with other users by sending friend requests, and once the request is accepted, users will be added to each other's friends' list. Users will also be able to view their friends' profiles, posts, and activities.

III.	Posting: Users will be able to share posts with their friends or the public. The posts can be in the form of text, images, videos, or links. Users will also be able to add captions, tags, and locations to their posts.

IV.	Commenting: Users will be able to comment on their friends' posts or public posts. They can also like or share the posts.

V.	Notifications: Users will receive notifications for friend requests, new posts, comments, and other activities related to their profiles.

#ALGORITHM

1. The program starts by creating and initializing necessary files for storing user data, friend requests, friends, posts, comments, and notifications.
2. It presents a menu of options for the user to choose from, including creating a profile, logging into an account, connecting with friends, sharing a post, commenting on a post, viewing notifications, or quitting the application.
3. If the user chooses to create a profile, they are prompted to enter a username and password. The program checks if the username already exists in the “users1.txt” file. If not, the user is asked for their name, profile picture URL, and bio, and this information is saved in the “users1.txt” file.
4. If the user chooses to log into an account, they are asked to enter their username and password. The program checks if the entered credentials match any user’s information in the “users1.txt” file. If there is a match, the user is greeted with a welcome message.
5. If the user chooses to connect with friends, they are asked to enter their name. The program reads the “friends.txt” file and displays the user’s current friends. Then the user can choose to send a friend request or    remove a friend.
6. If the user chooses to send a friend request, they enter the name of the person they want to send the request to. The program checks if a friend request has already been sent to that person and saves the request in the “friend_requests.txt” file.
7. If the user chooses to remove a friend, they enter the name of the person they want to remove from their friends list. The program removes the friend from the “friends.txt” file.
8. If the user chooses to share a post, they enter their name and the post content. The program generates a unique post ID, saves the post in the “posts.txt” file, and notifies the User’s friends about the new post by saving notifications in the “notifications.txt” file.
9. If the user chooses to comment on a post, they enter their name and select a post from the available posts displayed. Then they enter their comment, which is saved in the “comments.txt” file. The program also notifies the author of the post about the comment.
10. If the user chooses to view notifications, they enter their username, and the program reads the “notifications.txt” file to display the user’s notifications.
11. The menu is displayed again, and the user can continue choosing options until they decide to quit the application. That’s the basic flow of the social media application. It allows users to create profiles, log in, connect with friends, share posts, comment on posts, and view notifications. The user’s data is stored in separate files, and the program reads from and writes to these files as needed to perform the desired actions.
