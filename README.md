# try-snowpack
## Why? 

I keep hearing good things about snow pack, and on their website they do say _Once you try it, it's impossible to go back to anything else_. sounds pretty hyped, but we'll give it a go and see.


## What is snowpack?
Snowpack is a frontend build took which simplifies the build process so there's less overhead in your project.

Check out Snowpack: https://www.snowpack.dev/


Tools:
 - Visual Studio Code (VSC)


Before even writing this, I created this repo in github.
After the repo was initialized, I opened the folder in VSC and got started.
I'm following the [Quick start guide](https://www.snowpack.dev/tutorials/quick-start), so a lot of this might be repetitive.

I'm using NPM for installation
`npm install --save-dev snowpack`

I had some errors because of a missing package.json. I ran `npm init -y` to get started.

I run `npx snowpack dev` and get 404'd because an index.html isn't created. This is not a problem. It's nice that files don't get created for me right now, but at the same time it might be nice to mention it earlier in the quick start guide.

After adding a really basic index.html and running `npx snowpack dev`... it works! 