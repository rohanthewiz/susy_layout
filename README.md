# A Susy Layout Example

Susy is an awesome and light layout engine written in SASS. It gives you totally flexible column layouts.
Bye, bye large bloated frameworks! This is a solution you can scale with.

You will need a sass compiler to build the project's css.

If you are a rubyist, the Ruby alternative is easier (albeit less performant)
Here are some steps using rvm:

```
git clone https://github.com/rohanthewiz/susy_layout.git
cd susy_layout
rvm gemset create ruby_utils
rvm use ruby-2.2.2@ruby_utils --ruby-version    
gem install sass
sass --watch sass:css
```

I like Wellington because it's a go wrapper around libsass (== fast!):
https://github.com/wellington/wellington
Use a line similar to the below to compile. There is a watch option here also.

```
  wt compile -proj $ProjectFileDir$/sass -b $ProjectFileDir$/css
  # replace $ProjectFileDir$ with the path to your project root
```
  
Here's a couple decent tutorials on Susy:
https://css-tricks.com/build-web-layouts-easily-susy/
http://www.smashingmagazine.com/2015/07/smarter-grids-with-sass-and-susy/
And here's the mothership:
http://susy.oddbird.net/

This is a tool well worth learning if you do any front-end web development. I wholeheartedly recommend sass and susy.

### Upgrading Susy in this Project
- Go to https://github.com/oddbird/susy
- Copy the contents of the *susy* folder into the *sass* folder of this project


### License
There is none. Enjoy!
