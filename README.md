# Cyber-Patron

[![GitHub commit activity](https://img.shields.io/github/commit-activity/t/Bruce0C/Cyber-Patron)](https://www.github.com/Bruce0C/Cyber-Patron/commits/main)
[![GitHub last commit](https://img.shields.io/github/last-commit/Bruce0C/Cyber-Patron)](https://www.github.com/Bruce0C/Cyber-Patron/commits/main)
[![GitHub repo size](https://img.shields.io/github/repo-size/Bruce0C/Cyber-Patron)](https://www.github.com/Bruce0C/Cyber-Patron)
[![badge](https://img.shields.io/badge/deployment-Heroku-purple)](https://cyber-patron-34aa969be4ad.herokuapp.com)

![screenshot](documentation/mockup.png)

source: [Cyber-Patron amiresponsive](https://ui.dev/amiresponsive?url=https://cyber-patron-34aa969be4ad.herokuapp.com)

**Site Goals**

The site is aimed at providing digital for users online. It allowsusers to purchace the available art by downloading the art as a file (e.g pdf or png) to thier device and adding
their collections. The website should offer a seamless and secure way to browse, purchase, and instantly download digital art files without unnecessary friction. The site aims to deliver a smooth, visually engaging shopping experience that builds trust through secure payments, user accounts, and clear order feedback.
Ultimately the goal of the platform is to provide art to digital art enthusiasts in a convenient and reliable way for buyers.

**Agile Planning**

This project was developed using agile methodologies, focusing on delivering functional features in short sprints. The development cycle was divided into three sprints over a seven-day period, with each sprint building upon the previous one to ensure continuous progress.
All features were grouped into epics and prioritized using the MoSCoW method — Must have, Should have, and Could have. “Must have” stories, such as user authentication, product listings, and payment integration, were developed first to ensure that the core e-commerce functionality was in place early. Once the essential features were complete, focus shifted to “Should have” enhancements like user feedback messages and responsive design, followed by “Could have” improvements such as marketing and SEO optimizations.
A GitHub Projects Kanban board was used to manage workflow and track progress throughout development. Each user story was assigned a story point value to reflect its complexity and the effort required for completetion. This approach allowed for clear visibility of progress, flexibility in iteration, and ensured that all critical goals were delivered within the project timeframe.

**Epics & User stories**

**EPIC 1- Base Setup**
    
 The base setup epic is for all stories needed for the base set up of the application. Without the base setup, the app would not be possible so it was the first epic to be delivered as all other features depend on the completion of the base setup.

     User stories:

     - As a developer, I need to create the base.html page and structure so that other pages can reuse the layout

     - As a developer, I need to create static resources so that images, css and javascript work on the website

     - As a developer, I need to set up the project so that it is ready for implementing the core features

     - As a developer, I need to create the footer with social media links and contact information

     - As a developer, I need to create the navbar so that users can navigate the website from any device


**EPIC 2- Stand alone pages**

 The stand alone pages epic is for small pages that did not have enough stories to warrant their own full epics. Instead of creating epics for tiny features, these small deliverables were all added under this epic.

     User stories:

     - As a developer, I need to implement a 404 error page to alert users when they have accessed a page that doesn't exist

     - As a developer, I need to implement a 500 error page to alert users when an internal server error occurs

     - As a developer, I need to implement a 403 error page to redirect unauthorised users to so that I can secure my views

     - As the owner of the website, I would like a home page so that customers can view information on my digital gallery. 


**EPIC 3- Authentication & User Management**

 The authentication epic is for all stories related to the registration, login and authorization of views. This epic provides critical functionality and value as without it the owner would not be able to manage the gallery securely without regular site visitors also being able to see and perform actions. 

     User stories:

     - As a new user, I can register for an account to make purchases and downloads.

     - As a registered user, I can log in and out securely.

     - As an admin, I can manage users and upload artworks.

**EPIC 4- Catalogue & Art Management**

 The catalogue and management epic is for all user stories relataed to the user accesing available artworks and the site owner having the ability to managae the catalogue.

     User stories:

     - As a customer, I can browse all available art pieces in a responsive grid.
     
     - As a customer, I can view detailed information about each artwork.
     
     - As an admin, I can add, edit, or delete artworks.
     

**EPIC 5- Checkout, orders & File Delivery**

This epic focuses on user stories that enable a user to complete the payment process. this payment acceptance of payment and delivery of files. 

     User stories:

     - As a customer, I can securely pay for my selected artwork using Stripe.
     
     - As a customer, I can download my purchased art file after payment.
     
     - As a customer, I can download my purchased art file after payment.

**EPIC 6- UX & Accesibility**

This epic is for user stories related to the user experience. 

     User stories:

     - As a user, I want the site to be fully responsive on all devices.
     
     - As a user, I want the site to be fully responsive on all devices.


**EPIC 7- Deployment**

This epic is for all stories related to deploying the app to heroku so that the site is live for staff and customer use.

     User stories:

     - As a developer, I need to deploy the project to heroku so that it is live for customers



## UX

### The 5 Planes of UX

⚠️ NOTE: make sure to update the text below to match your own project! ⚠️

#### 1. Strategy

**Purpose**
- Provide an e-commerce platform for users to browse, purchase, and manage products.
- Enable site owners to manage inventory and track sales effectively.

**Primary User Needs**
- Easy navigation to browse and filter products.
- A secure and seamless checkout process.
- Ability to track orders and view purchase history.
- Access to promotions and discounts.

**Business Goals**
- Increase sales and revenue through an intuitive online store.
- Build customer loyalty with user accounts and order tracking.
- Promote products effectively through a visually appealing design.
- Collect user data for marketing and analytics purposes.

---

#### 2. Scope

**[Features](#features)** (see below)
- Product catalog with filtering and sorting options.
- Shopping cart functionality with item adjustments.
- User authentication for account creation and login.
- Secure payment integration with Stripe.
- Admin dashboard for inventory management.
- Newsletter signup for promotional updates.

**Content Requirements**
- Product descriptions, images, and pricing.
- User account details and order history.
- Checkout forms for billing and shipping information.
- Marketing banners for promotions and sales.

---

#### 3. Structure

**Information Architecture**
- **Navigation Menu**:
  - Home
  - Products (with categories and filters)
  - Bag/Cart
  - Checkout
  - User Profile (for logged-in users)
  - Admin Dashboard (for site owners)
- **Hierarchy**:
  - Homepage → Product Categories → Product Details → Add to Cart → Checkout
  - User Profile → Order History → Order Details

**User Flow**
1. Guest user browses the store → filters and sorts products by category, price, or name.
2. Guest user adds items to the cart → proceeds to checkout.
3. Guest user creates an account or logs in during checkout → completes purchase.
4. Returning customers log in → view past orders and track purchase history.
5. Site owners manage inventory → add, update, or delete products and categories.
6. Users signup to the newsletter → potentially receive advanced notice of upcoming sales.

---

#### 4. Skeleton

**[Wireframes](#wireframes)** (see below)
- Homepage wireframe with featured products and categories.
- Product listing page with filters and sorting options.
- Product details page with "Add to Cart" functionality.
- Shopping cart page with item adjustments and checkout button.
- Checkout page with billing and shipping forms.
- User profile page with order history and account settings.
- Admin dashboard wireframe for inventory management.

---

#### 5. Surface

**Visual Design Elements**
- **Color Scheme**:
  - Primary colors: Blue and white for a clean and professional look.
  - Accent colors: Green for success messages and red for errors.
- **Typography**:
  - Sans-serif fonts for readability and modern design.
  - Consistent font sizes for headings, subheadings, and body text.
- **Imagery**:
  - High-quality product images with consistent dimensions.
  - Promotional banners for sales and discounts.
- **Buttons and Icons**:
  - Clear and accessible buttons with hover effects.
  - Intuitive icons for navigation and actions (e.g., cart, profile).
- **Layout**:
  - Responsive design for mobile, tablet, and desktop devices.
  - Grid-based layout for product listings and content organization.



# Deployment

**Version Control**

The site was created using the Visual Studio Code editor and pushed to github to the remote repository ‘Cyber-Patron’.

The following git commands were used throughout development to push code to the remote repo:

- git add <file> - This command was used to add the file(s) to the staging area before they are committed.

- git commit -m “commit message” - This command was used to commit changes to the local repository queue ready for the final step.

- git push - This command was used to push all committed code to the remote repository on github.



## Features
### Existing Features

| Feature | Notes | Screenshot |
| --- | --- | --- |
| Register | Authentication is handled by allauth, allowing users to register accounts. | ![screenshot](documentation/features/register.png) |
| Login | Authentication is handled by allauth, allowing users to log in to their existing accounts. | ![screenshot](documentation/features/login.png) |
| Logout | Authentication is handled by allauth, allowing users to log out of their accounts. | ![screenshot](documentation/features/logout.png) |
| Product List | Users can browse all available products with sorting, filtering by categories, and search functionality. | ![screenshot](documentation/features/product-list.png) |
| Product Details | Displays detailed information about a selected product, including its name, description, price, an image, and available sizes. | ![screenshot](documentation/features/product-details.png) |
| Add to Bag | Users can add items to their shopping bag, with support for selecting different sizes if applicable. | ![screenshot](documentation/features/add-to-bag.png) |
| View Bag | Users can view the contents of their shopping bag, adjust quantities, or remove items. | ![screenshot](documentation/features/view-bag.png) |
| Checkout | Users can proceed to checkout, where they provide their delivery details and payment information using Stripe integration. | ![screenshot](documentation/features/checkout.png) |
| Order Confirmation | Users receive an on-screen and email confirmation with details of their purchase. | ![screenshot](documentation/features/order-confirmation.png) |
| Profile Management | Users can manage their profile information, including their default delivery address and order history. | ![screenshot](documentation/features/profile-management.png) |
| Order History | Users can view their past orders and access details of each order, including products purchased and the delivery status. | ![screenshot](documentation/features/order-history.png) |
| Product Management | Superusers can add, edit, and delete products from the site via a CRUD interface. | ![screenshot](documentation/features/product-management.png) |
| Contact | Users can submit a message via the contact form, which stores their name, email, and message in the database. | ![screenshot](documentation/features/contact.png) |
| User Feedback | Clear and concise Django messages are used to provide feedback to users when interacting with various features (e.g., adding products to the bag, checking out, etc.). | ![screenshot](documentation/features/user-feedback.png) |
| Heroku Deployment | The site is deployed to Heroku, making it accessible online for users. | ![screenshot](documentation/features/heroku.png) |
| SEO | SEO optimization with a sitemap.xml, robots.txt, and appropriate meta tags to improve search engine visibility. | ![screenshot](documentation/features/seo.png) |
| Marketing | Social media presence is available in the footer using external links, as well as a Facebook Marketplace wireframe in the README for future integrations. | ![screenshot](documentation/features/marketing.png) |
| 404 | The 404 error page will indicate when a user has navigated to a page that doesn't exist, replacing the default Heroku 404 page with one that ties into the site's look and feel. | ![screenshot](documentation/features/404.png) |


### Future Features

- **Product Reviews & Ratings**: Allow customers to leave reviews and rate products, with admin moderation. Display average ratings and review counts on product pages.
- **Wishlist Functionality**: Enable users to save products to a personal wishlist for future purchases. Notify users if wishlist items go on sale or are back in stock.
- **Product Recommendations**: Implement a "Customers who bought this also bought" or "You might also like" feature to suggest related products.
- **Live Chat Support**: Provide real-time customer support through an integrated live chat or chatbot.
- **Abandoned Cart Recovery**: Automatically send emails to users who add items to their cart but don't complete the purchase, offering discounts or reminders.
- **Discount Codes and Vouchers**: Allow the admin to create discount codes or vouchers for promotions and marketing campaigns.
- **Loyalty Program**: Introduce a points-based loyalty system where customers earn points for purchases, which can be redeemed for discounts.
- **Product Inventory Alerts**: Notify customers when out-of-stock items are back in stock, or when low inventory is approaching.
- **Multi-Currency and Multi-Language Support**: Expand the application to support multiple currencies and languages to reach a global audience.
- **Product Bundles**: Offer discounted product bundles (e.g., buy 3 for the price of 2) or custom product kits.
- **Social Media Integration**: Enable users to share products directly to social media platforms or implement a social login for quick account creation.
- **Shipping Tracking Integration**: Provide real-time shipping updates and tracking information directly within the user’s order history.
- **Advanced Analytics Dashboard for Admin**: Offer an in-depth dashboard that displays sales trends, popular products, customer behavior, and more.
- **Subscription-Based Products**: Allow users to subscribe to certain products (e.g., monthly deliveries of consumables like coffee or skincare products).
- **Product Video Demos**: Support product videos to better showcase features, especially for high-tech or complex items.
- **Mobile App**: Develop a mobile app for iOS and Android, providing users with a more optimized shopping experience on mobile devices.

## Tools & Technologies

| Tool / Tech | Use |
| --- | --- |
| [![badge](https://img.shields.io/badge/Markdown_Builder-grey?logo=markdown&logoColor=000000)](https://markdown.2bn.dev) | Generate README and TESTING templates. |
| [![badge](https://img.shields.io/badge/Git-grey?logo=git&logoColor=F05032)](https://git-scm.com) | Version control. (`git add`, `git commit`, `git push`) |
| [![badge](https://img.shields.io/badge/GitHub-grey?logo=github&logoColor=181717)](https://github.com) | Secure online code storage. |
| [![badge](https://img.shields.io/badge/HTML-grey?logo=html5&logoColor=E34F26)](https://en.wikipedia.org/wiki/HTML) | Main site content and layout. |
| [![badge](https://img.shields.io/badge/CSS-grey?logo=css&logoColor=1572B6)](https://en.wikipedia.org/wiki/CSS) | Design and layout. |
| [![badge](https://img.shields.io/badge/JavaScript-grey?logo=javascript&logoColor=F7DF1E)](https://www.javascript.com) | User interaction on the site. |
| [![badge](https://img.shields.io/badge/Python-grey?logo=python&logoColor=3776AB)](https://www.python.org) | Back-end programming language. |
| [![badge](https://img.shields.io/badge/Heroku-grey?logo=heroku&logoColor=430098)](https://www.heroku.com) | Hosting the deployed back-end site. |
| [![badge](https://img.shields.io/badge/Django-grey?logo=django&logoColor=092E20)](https://www.djangoproject.com) | Python framework for the site. |
| [![badge](https://img.shields.io/badge/PostgreSQL-grey?logo=postgresql&logoColor=4169E1)](https://www.postgresql.org) | Relational database management. |
| [![badge](https://img.shields.io/badge/Stripe-grey?logo=stripe&logoColor=008CDD)](https://stripe.com) | Online secure payments of e-commerce products/services. |
| [![badge](https://img.shields.io/badge/Gmail_API-grey?logo=gmail&logoColor=EA4335)](https://mail.google.com) | Sending emails in my application. |


## Database Design

### Data Model

Entity Relationship Diagrams (ERD) help to visualize database architecture before creating models. Understanding the relationships between different tables can save time later in the project.

![screenshot](/media/erd-diagram.jpeg)

I have used `Mermaid` to generate an interactive ERD of my project.

```erDiagram
    User {
        int id PK
        varchar username
        varchar email
        varchar password
    }

    UserProfile {
        int id PK
        varchar default_phone_number
        varchar default_street_address1
        varchar default_street_address2
        varchar default_town_or_city
        varchar default_county
        varchar default_postcode
        varchar default_country
    }

    User ||--|| UserProfile : has_one

    Category {
        int id PK
        varchar name
        varchar friendly_name
    }

    Product {
        int id PK
        varchar sku
        varchar name
        text description
        bool has_sizes
        decimal price
        decimal rating
        varchar image_url
        image image
    }

    Product ||--o| Category : belongs_to

    Order {
        int id PK
        varchar order_number
        varchar full_name
        varchar email
        varchar phone_number
        varchar country
        varchar postcode
        varchar town_or_city
        varchar street_address1
        varchar street_address2
        varchar county
        datetime date
        decimal delivery_cost
        decimal order_total
        decimal grand_total
        text original_bag
        varchar stripe_pid
    }

    OrderLineItem {
        int id PK
        int quantity
        decimal lineitem_total
        varchar product_size
    }

    Order ||--o| OrderLineItem : has_many
    OrderLineItem ||--o| Product : belongs_to

    Order ||--o| UserProfile : belongs_to

    Newsletter {
        int id PK
        varchar email
    }

    Contact {
        int id PK
        varchar name
        varchar email
        text message
    }

    FAQ {
        int id PK
        varchar question
        text answer
    }
```

source: [Mermaid](https://mermaid.live/edit#pako:eNqVVltvmzAU_ivIz2kV1qRc3qpOk6bdOk17mSIhB58Qa8amx3ZT2uS_z0BISggN4yEy5-5zvu-EV5IqBiQmgB85zZDmC-m557cG9F6bc_VwaTzOvIcvR9ETxXRN0bPOVNIc-hrIKRd9cUG13ihkjWa3kMeUD6hWXMDIzAxW1AqTFGslIZE2XwIOW2mDACahjCFo7Y81_DBsaNRGJgqTlJty2CpVVr6nL5Q21RAuRMDyTL-87fbqarvt9C721lQnriOt4T01kCksR3b1_CxXyEEyUSZH9aESl5nZ1IyMr__aS0kNPBt3e50iLwxX8qhZKiXq-2n-AvooZ5DynAqvQJ5CX4zUcJn10zplBonFNyitRc3vwDWrnqvtsa2xtwShZKYdIFrbH8hGE0hVtoPwXVkhkv_j17t06ICp4zaIw_dxfpFXF_l0yhDmOmt4DvWhP0wGgj8Blo4X2vTVTTuNMlT0lW7DSXaqrOGmkGdcUpEsaXb2DryApOCnW6se9Fcu4bOB_MLAK9GjpdJ0-tiWJlwQ7oKcVneYTwO_Gvnnimhx2a2o2QY5leW5evcuLbKHkbw37O6ZvvF32GgBxozG_hsIH25zr6Sho9fJKGrUE84d-vqs_nT3c2SmRwu6u43qsFTqTUu0HZmQDDkjsUELE5IDukLcK6lTLIhZgyuXxO643-4LspCVW0HlH6Xy1hOVzdbtiy0qJuz_oEm8okI7KbVG_Spl2lq5CCR-Jc8k9qPpdeiH4cyf34SzWRDeTEjpxP70en4zDaK5fxvMouh2vpuQlzrp9Dq4jaJZGIbTMJjOwsh3JbiFD3hfkdP5BlEwIcC4Ufit-WSovxx2_wAte5X_)


## Agile Development Process

### GitHub Projects

[GitHub Projects](https://www.github.com/Bruce0C/Cyber-Patron/projects) served as an Agile tool for this project. Through it, EPICs, User Stories, issues/bugs, and Milestone tasks were planned, then subsequently tracked on a regular basis using the Kanban project board.

![screenshot](/media/agile-methodology.jpeg)

### GitHub Issues

[GitHub Issues](https://www.github.com/Bruce0C/Cyber-Patron/issues) served as an another Agile tool. There, I managed my User Stories and Milestone tasks, and tracked any issues/bugs.

| Link | Screenshot |
| --- | --- |
| [![GitHub issues](https://img.shields.io/github/issues-search/Bruce0C/Cyber-Patron?query=is%3Aissue%20is%3Aopen%20-label%3Abug&label=Open%20Issues&color=yellow)](https://www.github.com/Bruce0C/Cyber-Patron/issues?q=is%3Aissue%20is%3Aopen%20-label%3Abug) | ![screenshot](/media/agile-methodology.jpeg) |
| [![GitHub closed issues](https://img.shields.io/github/issues-search/Bruce0C/Cyber-Patron?query=is%3Aissue%20is%3Aclosed%20-label%3Abug&label=Closed%20Issues&color=green)](https://www.github.com/Bruce0C/Cyber-Patron/issues?q=is%3Aissue%20is%3Aclosed%20-label%3Abug) | ![screenshot](/media/agile-methodology.jpeg) |

### MoSCoW Prioritization

I've decomposed my Epics into User Stories for prioritizing and implementing them. Using this approach, I was able to apply "MoSCoW" prioritization and labels to my User Stories within the Issues tab.

- **Must Have**: guaranteed to be delivered - required to Pass the project (*max ~60% of stories*)
- **Should Have**: adds significant value, but not vital (*~20% of stories*)
- **Could Have**: has small impact if left out (*the rest ~20% of stories*)
- **Won't Have**: not a priority for this iteration - future features


## Ecommerce Business Model

This site sells goods to individual customers, and therefore follows a **Business to Customer** model. It is of the simplest **B2C** forms, as it focuses on individual transactions, and doesn't need anything such as monthly/annual subscriptions.

It is still in its early development stages, and will soon have a newletter and links for social media marketing.

Social media can potentially build a community of users around the business, and boost site visitor numbers, especially when using larger platforms such a Facebook.

A newsletter list can be used by the business to send regular messages to site users. For example, what items are on special offer, new items in stock, updates to business hours, notifications of events, and much more!

## SEO & Marketing

### Keywords

I've identified some appropriate keywords to align with my site, that should help users when searching online to find my page easily from a search engine. This included a series of the following keyword types:

- **Short-tail (head terms) keywords**
   - E-commerce
   - Online store
   - Buy products
   - Shopping cart
   -  Checkout
   - Online shopping
   - Product catalog
   - Secure payments
   - Discounts
   - User accounts

- **Long-tail keywords**
   - Buy affordable electronics online
   - Secure online payment with Stripe
   - Best deals on fashion products
   - How to track orders online
   - Create an account for order tracking
   - Discounted products for sale
   - Easy-to-use shopping cart system
   - Browse product categories online
   - Fast delivery e-commerce platform
   - Sign up for exclusive discounts

I've also played around with [Word Tracker](https://www.wordtracker.com) a bit to check the frequency of some of my site's primary keywords (until the free trial expired).


### Sitemap

I've used [XML-Sitemaps](https://www.xml-sitemaps.com) to generate a sitemap.xml file. This was generated using my deployed site URL: https://cyber-patron-34aa969be4ad.herokuapp.com

After it finished crawling the entire site, it created a [sitemap.xml](sitemap.xml), which I've downloaded and included in the repository.

### Robots

I've created the [robots.txt](robots.txt) file at the root-level. Inside, I've included the default settings:

```txt
User-agent: *
Disallow:
Sitemap: https://cyber-patron-34aa969be4ad.herokuapp.com/sitemap.xml
```

Further links for future implementation:
- [Google search console](https://search.google.com/search-console)
- [Creating and submitting a sitemap](https://developers.google.com/search/docs/advanced/sitemaps/build-sitemap)
- [Managing your sitemaps and using sitemaps reports](https://support.google.com/webmasters/answer/7451001)
- [Testing the robots.txt file](https://support.google.com/webmasters/answer/6062598)

### Social Media Marketing

Creating a strong social base (with participation) and linking that to the business site can help drive sales. Using more popular providers with a wider user base, such as Facebook, typically maximizes site views.

I've created a mockup Facebook business account using the [Balsamiq template](https://code-institute-org.github.io/5P-Assessments-Handbook/files/Facebook_Mockups.zip) provided by Code Institute.

![screenshot](/media/facebook-page.jpeg)

## Testing

> [!NOTE]  
> For all testing, please refer to the [TESTING.md](TESTING.md) file.

## Deployment

The live deployed application can be found deployed on [Heroku](https://cyber-patron-34aa969be4ad.herokuapp.com).


### Heroku Deployment

This project uses [Heroku](https://www.heroku.com), a platform as a service (PaaS) that enables developers to build, run, and operate applications entirely in the cloud.

Deployment steps are as follows, after account setup:

- Select **New** in the top-right corner of your Heroku Dashboard, and select **Create new app** from the dropdown menu.
- Your app name must be unique, and then choose a region closest to you (EU or USA), then finally, click **Create App**.
- From the new app **Settings**, click **Reveal Config Vars**, and set your environment variables to match your private `env.py` file.

> [!IMPORTANT]  
> This is a sample only; you would replace the values with your own if cloning/forking my repository.

| Key | Value |
| --- | --- |
| `AWS_ACCESS_KEY_ID` | user-inserts-own-aws-access-key-id |
| `AWS_SECRET_ACCESS_KEY` | user-inserts-own-aws-secret-access-key |
| `DATABASE_URL` | user-inserts-own-postgres-database-url |
| `DISABLE_COLLECTSTATIC` | 1 (*this is temporary, and can be removed for the final deployment*) |
| `EMAIL_HOST_PASS` | user-inserts-own-gmail-api-key |
| `EMAIL_HOST_USER` | user-inserts-own-gmail-email-address |
| `SECRET_KEY` | any-random-secret-key |
| `STRIPE_PUBLIC_KEY` | user-inserts-own-stripe-public-key |
| `STRIPE_SECRET_KEY` | user-inserts-own-stripe-secret-key |
| `STRIPE_WH_SECRET` | user-inserts-own-stripe-webhook-secret |
| `USE_AWS` | True |

Heroku needs some additional files in order to deploy properly.

- [requirements.txt](requirements.txt)
- [Procfile](Procfile)
- [.python-version](.python-version)

You can install this project's **[requirements.txt](requirements.txt)** (*where applicable*) using:

- `pip3 install -r requirements.txt`

If you have your own packages that have been installed, then the requirements file needs updated using:

- `pip3 freeze --local > requirements.txt`

The **[Procfile](Procfile)** can be created with the following command:

- `echo web: gunicorn app_name.wsgi > Procfile`
- *replace `app_name` with the name of your primary Django app name; the folder where `settings.py` is located*

The **[.python-version](.python-version)** file tells Heroku the specific version of Python to use when running your application.

- `3.12` (or similar)

For Heroku deployment, follow these steps to connect your own GitHub repository to the newly created app:

Either (*recommended*):

- Select **Automatic Deployment** from the Heroku app.

Or:

- In the Terminal/CLI, connect to Heroku using this command: `heroku login -i`
- Set the remote for Heroku: `heroku git:remote -a app_name` (*replace `app_name` with your app name*)
- After performing the standard Git `add`, `commit`, and `push` to GitHub, you can now type:
	- `git push heroku main`

The project should now be connected and deployed to Heroku!

### PostgreSQL

This project uses a [Code Institute PostgreSQL Database](https://dbs.ci-dbs.net) for the Relational Database with Django.

> [!CAUTION]
> - PostgreSQL databases by Code Institute are only available to CI Students.
> - You must acquire your own PostgreSQL database through some other method if you plan to clone/fork this repository.
> - Code Institute students are allowed a maximum of 8 databases.
> - Databases are subject to deletion after 18 months.

To obtain my own Postgres Database from Code Institute, I followed these steps:

- Submitted my email address to the CI PostgreSQL Database link above.
- An email was sent to me with my new Postgres Database.
- The Database connection string will resemble something like this:
    - `postgres://<db_username>:<db_password>@<db_host_url>/<db_name>`
- You can use the above URL with Django; simply paste it into your `env.py` file and Heroku Config Vars as `DATABASE_URL`.

### Stripe API

This project uses [Stripe](https://stripe.com) to handle the ecommerce payments.

Once you've created a Stripe account and logged-in, follow these series of steps to get your project connected.

- From your Stripe dashboard, click to expand the "Get your test API keys".
- You'll have two keys here:
	- `STRIPE_PUBLIC_KEY` = Publishable Key (starts with **pk**)
	- `STRIPE_SECRET_KEY` = Secret Key (starts with **sk**)

As a backup, in case users prematurely close the purchase-order page during payment, we can include Stripe Webhooks.

- From your Stripe dashboard, click **Developers**, and select **Webhooks**.
- From there, click **Add Endpoint**.
	- `https://cyber-patron-34aa969be4ad.herokuapp.com/checkout/wh/`
- Click **receive all events**.
- Click **Add Endpoint** to complete the process.
- You'll have a new key here:
	- `STRIPE_WH_SECRET` = Signing Secret (Wehbook) Key (starts with **wh**)

### Gmail API

This project uses [Gmail](https://mail.google.com) to handle sending emails to users for purchase order confirmations.

Once you've created a Gmail (Google) account and logged-in, follow these series of steps to get your project connected.

- Click on the **Account Settings** (cog icon) in the top-right corner of Gmail.
- Click on the **Accounts and Import** tab.
- Within the section called "Change account settings", click on the link for **Other Google Account settings**.
- From this new page, select **Security** on the left.
- Select **2-Step Verification** to turn it on. (*verify your password and account*)
- Once verified, select **Turn On** for 2FA.
- Navigate back to the **Security** page, and you'll see a new option called **App passwords** (*search for it at the top, if not*).
- This might prompt you once again to confirm your password and account.
- Select **Mail** for the app type.
- Select **Other (Custom name)** for the device type.
    - Any custom name, such as "Django" or `Cyber-Patron`
- You'll be provided with a 16-character password (API key).
    - Save this somewhere locally, as you cannot access this key again later!
    - If your 16-character password contains *spaces*, make sure to remove them entirely.
    - `EMAIL_HOST_PASS` = user's 16-character API key
    - `EMAIL_HOST_USER` = user's own personal Gmail email address


### Local Development

This project can be cloned or forked in order to make a local copy on your own system.

For either method, you will need to install any applicable packages found within the [requirements.txt](requirements.txt) file.

- `pip3 install -r requirements.txt`.

You will need to create a new file called `env.py` at the root-level, and include the same environment variables listed above from the Heroku deployment steps.

> [!IMPORTANT]  
> This is a sample only; you would replace the values with your own if cloning/forking my repository.

Sample `env.py` file:

```python
import os

os.environ.setdefault("AWS_ACCESS_KEY_ID", "user-inserts-own-aws-access-key-id")
os.environ.setdefault("AWS_SECRET_ACCESS_KEY", "user-inserts-own-aws-secret-access-key")
os.environ.setdefault("DATABASE_URL", "user-inserts-own-postgres-database-url")
os.environ.setdefault("EMAIL_HOST_PASS", "user-inserts-own-gmail-host-api-key")
os.environ.setdefault("EMAIL_HOST_USER", "user-inserts-own-gmail-email-address")
os.environ.setdefault("SECRET_KEY", "any-random-secret-key")
os.environ.setdefault("STRIPE_PUBLIC_KEY", "user-inserts-own-stripe-public-key")
os.environ.setdefault("STRIPE_SECRET_KEY", "user-inserts-own-stripe-secret-key")
os.environ.setdefault("STRIPE_WH_SECRET", "user-inserts-own-stripe-webhook-secret")  # only if using Stripe Webhooks

# local environment only (do not include these in production/deployment!)
os.environ.setdefault("DEBUG", "True")
os.environ.setdefault("DEVELOPMENT", "True")
```

Once the project is cloned or forked, in order to run it locally, you'll need to follow these steps:

- Start the Django app: `python3 manage.py runserver`
- Stop the app once it's loaded: `CTRL+C` (*Windows/Linux*) or `⌘+C` (*Mac*)
- Make any necessary migrations: `python3 manage.py makemigrations --dry-run` then `python3 manage.py makemigrations`
- Migrate the data to the database: `python3 manage.py migrate --plan` then `python3 manage.py migrate`
- Create a superuser: `python3 manage.py createsuperuser`
- Load fixtures (*if applicable*): `python3 manage.py loaddata file-name.json` (*repeat for each file*)
- Everything should be ready now, so run the Django app again: `python3 manage.py runserver`

If you'd like to backup your database models, use the following command for each model you'd like to create a fixture for:

- `python3 manage.py dumpdata your-model > your-model.json`
- *repeat this action for each model you wish to backup*
- **NOTE**: You should never make a backup of the default *admin* or *users* data with confidential information.

#### Cloning

You can clone the repository by following these steps:

1. Go to the [GitHub repository](https://www.github.com/Bruce0C/Cyber-Patron).
2. Locate and click on the green "Code" button at the very top, above the commits and files.
3. Select whether you prefer to clone using "HTTPS", "SSH", or "GitHub CLI", and click the "copy" button to copy the URL to your clipboard.
4. Open "Git Bash" or "Terminal".
5. Change the current working directory to the location where you want the cloned directory.
6. In your IDE Terminal, type the following command to clone the repository:
	- `git clone https://www.github.com/Bruce0C/Cyber-Patron.git`
7. Press "Enter" to create your local clone.

Alternatively, if using Ona (formerly Gitpod), you can click below to create your own workspace using this repository.

[![Open in Ona-Gitpod](https://ona.com/run-in-ona.svg)](https://gitpod.io/#https://www.github.com/Bruce0C/Cyber-Patron)

**Please Note**: in order to directly open the project in Ona (Gitpod), you should have the browser extension installed. A tutorial on how to do that can be found [here](https://www.gitpod.io/docs/configure/user-settings/browser-extension).

#### Forking

By forking the GitHub Repository, you make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original owner's repository. You can fork this repository by using the following steps:

1. Log in to GitHub and locate the [GitHub Repository](https://www.github.com/Bruce0C/Cyber-Patron).
2. At the top of the Repository, just below the "Settings" button on the menu, locate and click the "Fork" Button.
3. Once clicked, you should now have a copy of the original repository in your own GitHub account!

### Local VS Deployment

The key differences between the local and deployed version is the static files not loding in the deployed version 
| Source | Notes |
| --- | --- |

**Credits**

### Content

| Source | Notes |
| --- | --- |
| [Markdown Builder](https://markdown.2bn.dev) | Help generating Markdown files |
| [Chris Beams](https://chris.beams.io/posts/git-commit) | "How to Write a Git Commit Message" |
| [Boutique Ado](https://codeinstitute.net) | Code Institute walkthrough project inspiration |
| [Bootstrap](https://getbootstrap.com) | Various components / responsive front-end framework |
| [AWS S3](https://aws.amazon.com/s3) | Cloud storage for static/media files |
| [Whitenoise](https://whitenoise.readthedocs.io) | Static file service |
| [Stripe](https://docs.stripe.com/payments/elements) | Online payment services |
| [Gmail API](https://developers.google.com/gmail/api/guides) | Sending payment confirmation emails |
| [Python Tutor](https://pythontutor.com) | Additional Python help |

### Media


| Source | Notes |
| --- | --- |
| [procreate](https://procreate.com/) | designing and editing original art products |
| [favicon.io](https://favicon.io) | Generating the favicon |
| [Boutique Ado](https://codeinstitute.net) | Sample images provided from the walkthrough projects |
| [Font Awesome](https://fontawesome.com) | Icons used throughout the site |
| [DALL-E 3](https://openai.com/index/dall-e-3) | AI generated artwork |
| [CloudConvert](https://cloudconvert.com/webp-converter) | Converting images to `.webp` |
### Acknowledgements

- I would like to thank my Code Institute mentor, [Tim Nelson](https://www.github.com/TravelTimN) for the support throughout the development of this project.
- I would like to thank my partner and family, for believing in me, and allowing me to attempt this transition into software development.
