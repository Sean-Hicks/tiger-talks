# ReadMe

* ## Assumptions
    * Late(est) version of node/npm installed
    * Late(est) version of Git installed

* ## Getting Started

    * ### Express
        * CD into tiger-talks backend folder
        * run 'npm install express --save' (This is necessary because we cant use version control for node  modules)
        * node index.js to start backend thru localhost:3000/

    * ### Database

    * ### Frontend
        * run "npm install -g @angular/cli" (This will install the Angular CLI globally)
        * verify that Angular is installed using "ng --version"
        * create a "projects" directory workspace to work in
        * clone down tiger-talks from the GitHub repository
        * cd into your tiger-talks directory
        * make sure you are on the right branch
        * use "ng serve" to start the application thru localhost:4200/
            * use "ng serve --open" to automaticlly open it in your default browser on http://localhost:4200/
            * #### Troubleshooting
                * Unable to Commit: you might have to configure your email and name globally on Git on the terminal using "git config --global user.email "your@email"" and "git config --global user.name "Your Name""
                * Client not Opening: try running "npm install @angular-devkit/build-angular"
