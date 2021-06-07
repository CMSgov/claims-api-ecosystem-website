## Getting Started

_Disclaimer: This content in this repository is intended for testing and research purposes only and should not be interpreted to be a view, offering, or service from CMS._

---

### Prerequisites

**Install Jekyll**

Jekyll is the static site framework that powers this website. To use Jekyll, you'll also need to make sure you have Ruby/RubyGems installed, although many computers come with Ruby already installed. You can [view the Jekyll documentation for in-depth instructions](https://jekyllrb.com/docs/).

**Install NPM (Node Package Manager)**

NPM is a package manager that helps this website manage integrations, packages, and dependencies like the [CMS Design System](https://design.cms.gov/). 

To install NPM, [please reference the official documentation](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm).

### Unix/MacOS Command-Line Instructions

First, navigate to the directory where you'd like the site to be stored and clone the repository locally on your computer.

```
git clone git@github.com:CMSgov/claims-api-ecosystem-website.git
```

After cloning the repository, you will want to change directory (`cd`) into the folder you just downloaded.

**Install Jekyll Dependencies**

Next, run this command to install Jekyll dependencies:

```
bundle install
```

**Install NPM Dependencies**

While you should be able to immediately run the site without this step, ensuring that you have NPM set up as well as dependencies installed locally can ensure you are able to update easily in the event that a new version of the CMS Design System is released, for example. Run the following command to install NPM dependencies:

```
npm i
```

**Build the site for viewing/editing**

Once all of the previous steps have been completed, you are ready to build the site locally and preview it with the following command:

```
bundle exec jekyll serve
```

This command will build the site and start a server that allows the web page to be viewed in the browser. You should see an address in your terminal window telling you the server address, which is `http://127.0.0.1:4000/` - therefore going to that address in your browser should take you to the homepage.

With this server running, you can now make changes to the site and preview them locally.
