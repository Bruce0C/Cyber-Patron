# Cyber-Patron

**Site Goals**

The site is aimed at providing digital for users online. It allowsusers to purchace the available art by downloading the art as a file (e.g pdf or png) to thier device and adding
their collections. The website SHOULD offer a seamless and secure way to browse, purchase, and instantly download digital art files without unnecessary friction. The site aims to deliver a smooth, visually engaging shopping experience that builds trust through secure payments, user accounts, and clear order feedback.
Ultimately the goal of the platform is to provide art to digital art enthusiasts in a convenient and reliable way for buyers.

**Agile Planning**

This project was developed using agile methodologies, focusing on delivering functional features in short sprints. The development cycle was divided into three sprints over a seven-day period, with each sprint building upon the previous one to ensure continuous progress.
All features were grouped into epics and prioritized using the MoSCoW method — Must have, Should have, and Could have. “Must have” stories, such as user authentication, product listings, and payment integration, were developed first to ensure that the core e-commerce functionality was in place early. Once the essential features were complete, focus shifted to “Should have” enhancements like user feedback messages and responsive design, followed by “Could have” improvements such as marketing and SEO optimizations.
A GitHub Projects Kanban board was used to manage workflow and track progress throughout development. Each user story was assigned a story point value to reflect its complexity and the effort required for completetion. This approach allowed for clear visibility of progress, flexibility in iteration, and ensured that all critical goals were delivered within the project timeframe.

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

**Run Locally**

Navigate to the GitHub Repository you want to clone to use locally:

- Click on the code drop down button
- Click on HTTPS
- Copy the repository link to the clipboard
- Open your IDE of choice (git must be installed for the next steps)
- Type git clone copied-git-url into the IDE terminal

The project will now have been cloned on your local machine for use.
