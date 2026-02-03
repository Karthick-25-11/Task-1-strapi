Clone and Run Strapi Application Locally


I started by checking the prerequisites on my system such as Node.js, npm, and Git. I created a new Strapi application using the create-strapi-app command with the quickstart option. This automatically set up the project, installed dependencies, configured the database, and started the development server.

Once the setup was complete, I accessed the Strapi admin panel using the browser. I created an admin account and explored the dashboard to understand the available features.

Using the Content-Type Builder, I created a collection type called Article. I added fields such as title and content to define the structure of the article data. After saving the content type, Strapi restarted automatically to apply the changes.

Next, I used the Content Manager to create a sample article entry and published it. This confirmed that the content type and database were working correctly.

To make the data accessible through APIs, I enabled public permissions for the Article content type. I allowed the find and findOne actions under the Public role in the Users and Permissions settings.

After enabling permissions, I tested the API by accessing the endpoint in the browser. The API returned the article data in JSON format, which confirmed that the backend setup was working end to end.

Finally, I initialized a Git repository, committed the project files, and pushed them to my GitHub account. I created a main branch and a separate branch with my name, and then raised a pull request from my branch(karthick) to the main branch as required.

Errors Faced and How I overcame:

During the setup, I faced multiple errors such as npm install failing due to missing package.json. This happened because I was running commands outside the correct project directory. I resolved this by navigating to the correct folder before running commands.

I also encountered errors related to unsupported protocols and missing scripts. These issues helped me understand the difference between the Strapi core repository and a runnable Strapi application. I fixed this by creating a Strapi app using create-strapi-app instead of trying to run the core repository directly.

Another issue I faced was GitHub not allowing me to create a pull request because both branches were identical. I resolved this by making a small change in the README file, committing it on my name-based branch, and pushing it again so that the PR could be created successfully.

Outcome

At the end of this task, I successfully ran a Strapi application locally, created and managed content through the admin panel, exposed data using public APIs, and followed a proper Git workflow by creating branches and raising a pull request. This project helped me understand the complete flow of setting up a backend CMS application and managing it professionally.
