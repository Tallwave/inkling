# Inkling

Inkling is a framework for creating responsive emails quickly using modern web technology.

## Before you Begin

- Clone the repo
- Be sure you've installed the dependencies. `bundle install` from the repo root. Alternately, install them manually (the list of dependencies is below) 

## Building the email

In terminal, `cd` to project root.

While you're building HTML and Styles, you can use jekyll's dev server to demo your code `jekyll serve --watch`.
This will look for changes, rebuild and allow you to preview the site at `localhost:4000`.

When you're satisfied with your design, `Ctrl + C` to quit the server.

Then just type `rake`. This will compile the jekyll and sass, then inline the styles to get it all ready to send. The inlined html will be in the _inlined directory.

## How to use

The best way to start is by modifying one of the examples. These are based on the Ink examples, but should feel a little simpler because of the use of the Liquid templating engine and SASS.

Update the SCSS files in the _scss directory to match your design. _variables.scss works very similar to Foundation's variables system.

See the [Ink Documentation](http://zurb.com/ink/) for additional classes and elements that are included.

## Requirements

- Ruby
- [Jekyll](http://jekyllrb.com/) `gem install jekyll`
- Nokogiri `gem install nokogiri`
- Premailer `gem install premailer`

## SCSS

- [Sassy Ink](https://github.com/29thdrive/sassy-ink) Based on [Zurb's Ink](http://zurb.com/ink/)

## Future Plans
 - Use YML file for configuration
 - Set this up as a ruby gem with an init script (like Foundation, Bootstrap, Compass, etc)
