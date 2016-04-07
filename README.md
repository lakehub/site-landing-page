# Landing page for lakehub official site 

This project uses Zurb foundation as css framework + Compass. a node server has
also been included. It is purely html, js and css (SCSS). No Ruby or other backend
knowledge required.


## Get started

This project has been generated using [yeoman](http://yeoman.io) with [foundation-5 generator](https://github.com/juliancwirko/generator-zf5). It uses SASS for stylesheet


## How to contribute
If you’d like to add features (or bug fixes) to improve the example application, you can fork the repo and make pull requests.

1. Fork it
2. run `npm install` and `bower install` to install project depedancies.
3. Create your feature branch (`git checkout -b my-new-feature`)
4. Commit your changes (`git commit -am 'add some feature'`)
5. Push to the branch (`git push origin my-new-feature`)
6. Create a new Pull Request

To keep you forked repo with the upstream repo read through [this for
instructions](http://2buntu.com/articles/1459/keeping-your-forked-repo-synced-with-the-upstream-source/)

## Quickstart

When you're working on your project immediately after having it in your
local repo, move to the root of the app.

NB: You should have node and ruby installed in your system

1. Install node modules `node install`
2. The project uses compass so install the compass ruby gem `gem install compass`. This will land you in trouble if its not installed, grunt will keep throwing unexplained error
3. To start development run `grunt` from the project directory
4. Run `grunt publish` to get production ready code which will be in the dist
         directory
5. To see how the website will be in production `grunt publish` then run
         production server as `grunt server-dist`


##### For more information about grunt tasks for zf5 genetator visit its [github page](https://github.com/juliancwirko/generator-zf5)

NB: If you are familiar with grunt then you can change the above commands to
what you are comfortable with.

