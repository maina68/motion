# 2 option: Usin Parcel
This option requires you to have node installed.
Once you have Node.js installed, head to your terminal. When you installed Node.js, you also will have gotten a tool called npm.It manages JavaScript packages. What it allows you to do is install things from the npm registry. Let's try. Run the following:
npm install --global parcel
It's going to install a bunch of stuff for you so that you can then use the tool parcel. Parcel is a tool that makes it super simple to bundle all of your code together into one neat little package. You can also install whatever you want from npm and include that too! From there:

Okay, go to your index.html and delete the <script src="https://unpkg.com/popmotion@11.0.3/dist/popmotion.global.min.js"></script> line.

Go to your animation.js file and add to the top of the file as the very first line: const popmotion = require("popmotion");. This will tell the bundler to bring in Popmotion for you.

Navigate in your terminal to the root of your animation project. Run npm init -y. This will generate a package.json file for you which is how Node projects handle their configurations. We need to be able to keep track of dependencies and this will do that.

Run npm install popmotion@11.0.3. This will install Popmotion locally on your computer instead of loading it from somewhere else. Now your users will download just one file from you instead one file from you and one file from another server. Notice in your animation project there's now a node_modules directory: this is where all your installed dependencies (which is what you call the libraries you install from npm) go.
