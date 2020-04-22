
# Buffalo Soldiers website V.1.2 Quote:
### broken down by functionality



# Content management system:
Allows content creators to be assigned to specific chapters to create and edit events, news posts and edit the about and landing pages and any other content areas that you want to be editable.

### Solution used: 
A self hosted instance of the open source CMS, 'Strapi' with a custom integration to allow content to be partitioned and separated by chapter.

### Cost:
$2.50 / month per chapter + $700 development fee

monthly cost includes hosting for the self hosted CMS and all that entails

### Alternative solutions:
CMS service that supports enough roles cost $400 or more but still lack the exact functionality that we want to keep chapters seperated



# Custom Backend for chapter owners / admins:
Includes: customization of themes and templates for each chapter, On-Site login / registration, centralized admin panel and chapter settings  (set accounts to send payments to, membership dues, Location to be found on the chapter map), 

### Solution used: 
A custom backend hosted on AWS servers (Amazon Web Systems) or Google Cloud Servers that will handle all the chapter functionality that isn't handled by the CMS.

### cost: 
$1.50 / ch / month  + $900 development fee

monthly cost includes hosting fees for the different services used (serverless functions, serverless databases, authentication ect...)



# User functionality:
This will allow users to register, login and have the following functionality on the site:
post comments, Rsvp to events, sign up for chapter memberships, Save credit card information, make payments through their user account, view messages and notifications.

This will also add functionality for chapter administrators to get insights for events and memberships. They will be able to view all their current Chapter members + who has paid and have an organized list of exactly who has RSVP'd and paid for events. Without this functionality, any such information about memberships and user activity would have to be manually tracked.

### Solution used: 
Custom Stripe integrations for managing payments and additional custom backend services hosted on AWS servers (Amazon Web Systems) or Google Cloud Servers to handle all user interactions & manage their data.

### cost: 
$2.00 / ch / month  + $1,100 developmentu fee

monthly cost includes hosting fees for the different services used (serverless functions, serverless databases, authentication ect...)


# Support & maintenance: 
includes management and maintenance of all the services used, security updates and e-mail support for chapter administrators.

### cost: 
$1.50 / ch / month 



# Free site hosting on Netlify:
To remain on the free tier of hosting and avoid an extra monthly fee of $45, I can optimize the website to use smart caching, client-side routing, server-side pre-rendering and other techniques to reduce bandwidth to a fraction of what it would be. I will also have intercept and modify the build process so that chapter administrators won't cause site rebuilds from updating to exceed the free tier usage. (https://www.netlify.com/pricing/)

### cost:
 $200 development fee



# Package plan (includes everything above)

### $7.00 / mo / ch
### $2,900 development fee


















