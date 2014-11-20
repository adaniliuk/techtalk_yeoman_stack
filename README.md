<h1>TechTalk "Modern full-stack JavaScript web app solution structure: Yo, Gulp, NPM and Bower”</h1>

<b>Example of modern full-stack JavaScript web app using Yo, Gulp, NPM and Bower tools for the following development tasks:</b>

- Application template scaffolding 
yo (http://yeoman.io/) scaffolds out a new application, writing your Grunt configuration and pulling in relevant Grunt tasks and Bower dependencies that you might need for your build.

Q: What should web app consist of?

- Dependencies management;
The Package Manager is used for dependency management, so that you no longer have to manually download and manage your scripts. Bower (http://bower.io/) and npm (https://www.npmjs.org/) are two popular options.

Q: How would you manage your app dependencies?

- Build system:
The Build System is used to build, preview and test your project. Grunt (http://gruntjs.com/) and Gulp (http://gulpjs.com/) are two popular options.
  - Code compilation and validation; application start-up and testing;
  - Code metrics reports and documentation generation;
  - Application distribution package generation.

Q: How would you perform each of the above tasks? 
Q: What other common production ready web app build tasks do you know?

<b>There are 3 examples provided:</b>
- Angular frontend application (https://github.com/yeoman/generator-angular).  
- Angular fullstack application (https://github.com/DaftMonk/generator-angular-fullstack)
- Simple web application (https://github.com/yeoman/generator-gulp-webapp)

To work with the above autogenerated examples please install prerequisites:

- Node.js v0.10.x+
- npm (which comes bundled with Node) v2.1.0+
- git
- yo
- bower
- gulp

After that run <b>npm install && bower install</b> in each example application folder to install app specific dependencies.

