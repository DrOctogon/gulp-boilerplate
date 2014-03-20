#gulp boilerplate

this is a super simple gulp boilerplate that gives you the following:

* express server w/ livereload browser refresh on change
* jade compilation
* sass compilation
* coffeescript compilation

it's aim is purely to act as a simple starting point for starting with gulp.

##usage
as a prerequisite it's assumed you have `npm` installed and the `gulp-cli`.

1. clone the repo

		git clone https://github.com/jh3y/gulp-boilerplate.git

2. install dependencies

		npm install

3. start gulp with either `gulp` or `gulp --require coffee-script/register` if using a gulpfile in coffeescript.
4. start hacking away with super fast livereload goodness.

__NOTE::__ you may have to run `gulp` once and then restart it to get the livereload working because watch won't pick up on newly generated files out of the box. If you want this functionality, take a look at `gulp-watch`.

Any problems or questions, feel free to post an issue or tweet me, @_jh3y!

@jh3y 2014
