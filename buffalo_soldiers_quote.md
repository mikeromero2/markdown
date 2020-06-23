
# Buffalo Soldiers Web App (V.1.2)
##  Development Quote:

### $7.00 / month / chapter (rounded down)
### $2,900 development fee

---

# Application Features:
## #1 - Content management system:
Allows content creators (Chapter admins) to create and edit events, news posts and the 'about' and landing pages and any other content areas that you want to be editable.

### Solution used: 
A self hosted instance of the open source CMS, 'Strapi' with a custom integration to allow content to be partitioned and separated by chapter.

### Cost:
$2.50 / month per chapter + $700 development fee


# #2 - Custom Back-end for chapter owners / admins:
Includes: 
- customization of themes and templates for each chapter, 
- On-Site login / registration, 
- centralized admin panel and chapter settings  (set accounts to send payments to, membership dues, Location to be found - on the chapter map), 

### Solution used: 
A custom back-end hosted on AWS servers (Amazon Web Systems) that will handle all the chapter functionality that isn't handled by the CMS.

### cost: 
$1.50 / ch / month  + $900 development fee

monthly cost includes hosting fees for the different services used (serverless functions, serverless databases, authentication ect...)



# #3 - User functionality:
Provides functionality for users to register, login and have the following functionality on the site:
- post comments, 
- Rsvp to events, 
- register / pay for chapter memberships, 
- Save credit card information, 
- make payments through their user account, 
- view messages and notifications.

This will also add functionality for chapter administrators to get insights for events and memberships. They will be able to view all their current Chapter members + who has paid and have an organized list of exactly who has RSVP'd and paid for events. Without this functionality, any such information about memberships and user activity would have to be manually tracked.

### Solution used: 
Custom Stripe integrations for managing payments and additional custom backend services hosted on AWS servers (Amazon Web Systems) or Google Cloud Servers to handle all user interactions & manage their data.

### cost: 
$2.00 / ch / month  + $1,100 developmentu fee

monthly cost includes hosting fees for the different services used (serverless functions, serverless databases, authentication ect...)


# #4 - Support & maintenance: 
includes management and maintenance of all the services used, security updates and e-mail support for chapter administrators.

### cost: 
$1.50 / ch / month 



# #5 - Free site hosting on Netlify:
To remain on the free tier of hosting and avoid an extra monthly fee of $45 / month, I can optimize the front-end by implementing smart caching, client-side routing, server-side pre-rendering and other techniques to reduce bandwidth to a fraction of what it would be. I will also modify the build process so that chapter administrators won't exceed the free tier usage for site rebuilds. (https://www.netlify.com/pricing/)

### cost:
 $200 development fee





















