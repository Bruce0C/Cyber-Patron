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

**Heroku Deployment**

The site was deployed to Heroku. The steps to deploy are as follows:

- Navigate to heroku and create an account
- Click the new button in the top right corner
- Select create new app
- Enter app name
- Select region and click create app
- Click the resources tab and search for Heroku Postgres
- Select hobby dev and continue
- Go to the settings tab and then click reveal config vars
- Add the following config vars:
- SECRET_KEY: (Your secret key)
- DATABASE_URL: (This should already exist with add on of postgres)
- EMAIL_HOST_USER: (email address)
- EMAIL_HOST_PASS: (email app password)
- Click the deploy tab
- Scroll down to Connect to GitHub and sign in / authorize when prompted
- In the search box, find the repositoy you want to deploy and click connect
- Scroll down to Manual deploy and choose the main branch
- Click deploy

The app should now be deployed.


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
