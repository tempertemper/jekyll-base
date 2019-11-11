# jekyll-base
Basic Jekyll website starting point


## Initial setup

First up, make sure [node](https://nodejs.org/en/) (and npm), [ruby](https://www.ruby-lang.org/en/) and [Bundler](https://bundler.io/) are installed globally:

- Run `bundle install`
- Run `npm install` in the project root to install any node packages and allow the npm scripts to run


## Development environment

To work on the site locally you need to build the site and run a development server.

- Run `npm start` in the project root to work on the site content and structure (built with [Jekyll](https://jekyllrb.com/))
- Go to http://localhost:4000/ in your browser


## Site build

Run `npm run build` to build the site out into the /dist/ directory. This doesn't run a local development server or watch the /src/ directory for any SCSS or Jekyll changes.


## Updating dependencies

Do this with caution.

- Run `npm update` in the project root
