To Run this Project

1) Open a console and change to inside the root directory of this repository.

2) Execute the following command to install the Gulp plugins listed in the devDependencies section of the package manifest.

npm install

3) It is advised that you configure jspm with your GitHub credentials in order to avoid problems. You can do this by executing: 

jspm registry config github

and following the prompts.

4) Next, execute the following command to install the Aurelia library, bootstrap and font-awesome, listed in the jspm.dependencies section of the package manifest.

jspm cc             (to clear the caches)

jspm install -y

jspm install aurelia-fetch-client



