# Django_Blog

## About the app

This Desktop Blog is to demonstrate Registration, login and CRUD operations in Django.

## Login

The Login screen allows users with an account to login.
<br>
<br>
<img src="./README_Screenshots/Django_Blog_Login.png" alt="login" width="300"/>

## Create Account

To create an account, the user can click on the register link in the navbar or 'Sign Up Now' from the Login Page
<br>
<br>
<img src="./README_Screenshots/Django_Blog_Register.png" alt="drrep" width="300"/>

## Forgot Password

If a user forgot their password they can click 'forgot password' from the login page to:
<br>
<br>
1. Enter their email and have a link to reset their password emailed to them. 
<br>
<img src="./README_Screenshots/Django_Blog_Reset_Password.png" alt="drrep" width="300"/>

2. Upon entering a valid email they will receive a confirmation the email has been sent.
<br>
<img src="./README_Screenshots/Django_Blog_Reset_Password_Email_Sent.png" alt="drrep" width="300"/>

3. They can then click on the link in their email to be redirected to a reset password page on the blog.
<br>
<img src="./README_Screenshots/Django_Blog_Reset_Password_Email.png" alt="drrep" width="300"/>

4. They will then be able to enter a new password for their account.
<br>
<img src="./README_Screenshots/Django_Blog_Reset_Password_Page.png" alt="drrep" width="300"/>

## Homepage

The first time a user logs in, the homepage will dispaly all Blog posts. 

<br>
<br>
<img src="./README_Screenshots/Django_Blog_Home.png" alt="home" width="300"/>

The user can click New Post in the nav-bar to create a new post. 
<br>
<br>
<img src="./README_Screenshots/Django_Blog_New_Post.png" alt="home" width="300"/>

The user can fill out the form and submit the post by selecting the post button. 
<br>
<br>
<img src="./README_Screenshots/Django_Blog_New_Post_Filled_In.png" alt="home" width="300"/>

Once the user selects post, they will be redirected to a detailed view of the new post. 
<br>
<br>
<img src="./README_Screenshots/Django_Blog_New_Post_Posted_Detail_View.png" alt="home" width="300"/>



The user can click on the author's name to filter out all blog posts by that author.
<br>
<br>
<img src="./README_Screenshots/Django_Blog_Users_Posts.png" alt="home" width="300"/>

The user can select a specific post to reveal more information about it. <br>
If the user is the author of the post, they will be able to update and/or delete the post.
<br>
<br>
<img src="./README_Screenshots/Django_Blog_Post_Detail_User.png" alt="login" width="300"/>

If the user is not the author of the post, they will not be able to edit or delet the posting.
<br>
<br>
<img src="./README_Screenshots/Django_Blog_Post_OtherUser.png" alt="login" width="300"/>

If the user has selected the update feature for one of their own posts, they will be redirected to the update page for that specific post.
<br>
<br>
<img src="./README_Screenshots/Django_Blog_Post_Updating.png" alt="login" width="300"/> 

After updating the prefilled information and selecting post, they will be redirected to a detailed view of the updated post.
<br>
<br>
<img src="./README_Screenshots/Django_Blog_Post_Updated.png" alt="login" width="300"/> 

If the user has selected the delete feature for one of their own posts, they will be redirected to the delete page for that specific post.
<br>
<br>
<img src="./README_Screenshots/Django_Blog_Post_Deleting.png" alt="login" width="300"/> 

After deleting the selected post, they will be redirected to the blog home page.
<br>
<br>
<img src="./README_Screenshots/Django_Blog_Home_Post_Deleted.png" alt="login" width="300"/> 


Users can also view their profile page once logged in. From here they are able to update their username, email or profile image.
<br>
<br>
<img src="./README_Screenshots/Django_Blog_Update_Profile.png" alt="login" width="300"/> 

After updating the prefilled information and selecting update, they will be given a confirmation notice.
<br>
<br>
<img src="./README_Screenshots/Django_Blog__Update_Profile_Completed.png" alt="login" width="300"/>

All of their posts will then be updated with their new information if appropriate.
<br>
<br>
<img src="./README_Screenshots/Django_Blog_Home_Updated_Final.png" alt="login" width="300"/>

Once a user has completed creating, editing and deleting posts, they are able to logout with the logout button located in the navbar. 
<br>
<br>
<img src="./README_Screenshots/Django_Blog_Logout.png" alt="login" width="300"/>
