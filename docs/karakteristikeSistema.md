# **4. System characteristics**

## **4.1 View coupons on the site**

### *4.1.1 Description and priority*

The user, whether a visiting user or a registered user, will be able to view everything
available and currently active coupons. Also, the user will have the option of a detailed review
of each individual coupon, showing details such as: Expiry date
coupon available, category, activation code, description, etc.

### *4.1.2 Stimulus/response sequences*

^^Incentives^^: The user accesses the platform using the appropriate domain and selects a coupon
of interest.

^^Answer^^: A web page opens, where available and active are displayed on the home page
coupons. When the user requests details about the coupon, the system responds with additional ones
information about the coupon of interest.

### *4.1.3 Functional requirement*

| Functional requirement  | Description                                                                                                                      |
|-------------------------|----------------------------------------------------------------------------------------------------------------------------------|
| FZ-1                    | Every user, regardless of the category he belongs to, must be able to review the available coupons.                              |
| FZ-2                    | Every user, regardless of the category he belongs to, must be able to review detailed information about the coupon of interest.  |

## **4.2 Publishing coupons on the site**

### *4.2.1 Description and priority*

How bbKupons is conceived as an open platform for publishing coupons, registered
we will enable users to publish them. A registered user will be
enabled to enter more detailed information about the coupon when publishing the coupon, such as
are name, description, code, category and image.

### *4.2.2 Stimulus/response sequences*

^^Incentives^^: The user accesses the system and enters the appropriate combination of credentials that he is
used when registering on the system.

^^Answer^^: The system allows the user to log in to the system, thereby unlocking it
the ability to publish coupons.

^^Incentives^^: The user starts the coupon posting process by clicking "Add".

^^Answer^^: The system opens a coupon posting form, where the user is expected to enter
relevant information about the coupon he wants to publish.

^^Incentives^^: The user publishes the coupon by clicking "Submit".

^^Answer^^: The system adds the coupon to the coupon database and presents it to all users
on the home page.

### *4.2.3 Functional requirements *

| Functional requirements     | Description                                                                                                                                                               |
|-----------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| FZ-3                        | The registered user must be able to start the process of publishing the coupon on the page by clicking "Add". Any other category of users must not have this possibility. |
| FZ-4                        | A logged in user must be able to enter relevant information about the coupon they want to post.                                                                           |
| FZ-5                        | The registered user must be able to complete the information about the coupon with an image.                                                                              |
| FZ-6                        | The registered user must be able to finalize the coupon posting by clicking "Submit".                                                                                     |

## **4.3 Liking and commenting on coupons**

### *4.3.1 Description and priority*

To enable service and product providers to have insight into impressions and feedback
information about the same, registered users will be able to mark individual coupons
with 'I like it'. In addition, registered users will be able to leave a comment
on each individual coupon.

### *4.3.2 Stimulus/response sequences*

^^Incentives^^: The user marks the coupon as positive by clicking on the "heart" icon.

^^Answer^^: The system increases the number of positive reactions on a particular coupon.

^^Incentives^^: The user enters text in the comments section and publishes the above
comments.

^^Answer^^: The system enters the comment into the comment database, and links it to a specific one
coupon.
### *4.3.3 Functional requirement*

| Functional requirements | Description                                                                                                                                                                                             |
|-------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| FZ-7                    | The registered user must be able to "like" a certain coupon by clicking on the "heart" icon, which is located below each individual coupon. Any other category of users must not have this possibility. |
| FZ-8                    | The registered user must be able to enter text in the text field provided for comments, which is located below each individual coupon. Any other category of users must not have this possibility.      |
| FZ-9                    | The registered user must be able to finalize the posting of comments on the coupon by clicking on "Comment".                                                                                            |

# **4.4 Filter coupons by name**

### *4.4.1 Description and priority*

In order to enable the users of this system to find a particular coupon more easily, the system
will allow filtering coupons by name.

### *4.4.2 Stimulus/response sequences*

^^Incentives^^: The user enters a value in the coupon filter by name.

^^Answer^^: The system filters all coupons and responds to the user with a coupon that
meets the name requirement.
### *4.4.3 Functional requirement*

| Functional requirements | Description                                                                                                                                                   |
|-------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------|
| FZ-10                   | Every user, regardless of category, must be able to enter a value in the text field provided for entering the criteria by which the coupons will be filtered. |

## **4.5 Filter coupons by category**

### *4.5.1 Description and priority*

In order to enable the users of this system to find coupons for a specific product more easily
category of products or services, the system will allow filtering coupons by category.

### *4.4.2 Stimulus/response sequences*

^^Incentives^^: The user selects category criteria for coupon filtering.

^^Answer^^: The system filters all coupons and responds to the user with coupons that
meet the set requirement for the category.

### *4.4.3 Functional requirement*

| Functional requirements | Description                                                                                                                               |
|-------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| FZ-11                   | Every user, regardless of the category he belongs to, must be able to select the category by which he wants the system to filter coupons. |