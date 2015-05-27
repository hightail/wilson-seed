# Wilson-Seed
Seed application for wilson web applications

## Getting Started

Get up and running with your Wilson webapp in minutes


### Install Node, Grunt and Yeoman

First you'll need to make sure you have Nodejs installed. The easiest way to get Nodejs fast is by using Homebrew. Find it here: [http://brew.sh/]

Once you have brew, run these commands:

```
brew install node
npm install -g grunt-cli
npm install -g yo
npm install -g hightail/generator-wilson
```


### Get the Wilson Seed App

Now you just need to get the Wilson seed application. Just run this in your terminal:

```
curl -L https://github.com/hightail/wilson-seed/archive/1.0.0.zip > wilson-seed.zip; unzip wilson-seed.zip; rm wilson-seed.zip;
```

(NOTE: You can name the resulting directory with whatever name you'd like)


### Bootstrap Wilson

Next we need to get Wilson ready to run. Navigate in terminal into the resulting directory and run this:

```
npm install
```


### Run your new Wilson Web Application

Wilson should now be ready to go, so let's start the web server:

```
grunt develop
```