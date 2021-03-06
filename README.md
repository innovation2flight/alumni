# NASA JPL i2f Alumni Website

To add yourself to the i2f alumni site, complete the following steps (there is no need to clone this repo, all the steps can be completed from the github online interface):

1. Gain access to this repository by getting the username and password for the i2f github account which is stored in the Google Drive in a spreadsheet called "Accounts and Passwords". Either add your own GitHub account as a collaborator to this repo by going to settings > collaborators, and typing your name. Or, you can make changes directly from the innovation2flight GitHub account.

2. Add your professional headshot photo to the directory ```images > headshots```, the image should be ***square*** (equal height and width) and less than 1000 x 1000px. A site like [Croppola](https://croppola.com/) has the functionality to crop and scale your photo.

3. Add a markdown file in the directory ```_members``` for yourself, copy and paste the format below into a new file named ```[NAME].md``` and update your information (colons are used as delimiters in the YAML header of each markdown file, ***do not add any extra colons***, dashes are ok), below is an example you can copy/paste as a template.
```
---
layout: member # don't change this line
name: Hunter Hall
school: UC Berkeley
major: Astrophysics
project: Zephyrus & Talos
email: hall AT berkeley DOT edu
image: hunter.png # the name of the image you added in step 1
---
Here is my bio written in the first person.
```
4. Commit the changes to the markdown file, your webpages should be automatically generated and updated on the website. Allow a few minutes for your changes to show, the temporarily hosted site is [here](https://innovation2flight.github.io/alumni/).

### Github Pages URL Structure in Jekyll
[Here](https://github.com/jekyll/jekyll/blob/master/docs/_docs/github-pages.md) is some well written docs about how to use Jekyll's liquid templating to have local and remote links work locally and when published via Github Pages.

## Credits
Jekyll integration by [Andrew Banchich](https://github.com/andrewbanchich/phantom-jekyll-theme):
```
# How to Use

For those unfamiliar with how Jekyll works, check out [https://jekyllrb.com/](https://jekyllrb.com/) for all the details, 
or read up on just the basics of [front matter](https://jekyllrb.com/docs/frontmatter/), [writing posts](https://jekyllrb.com/docs/posts/), 
and [creating pages](https://jekyllrb.com/docs/pages/).

- GitLab: Simply fork this repository and start editing the `_config.yml` file!  
- GitHub: Fork this reposity and create a branch named `gh-pages`, then start editing the `_config.yml` file! The `.gitlab-ci.yml` file is only needed for GitLab Pages, so feel free to delete this if you are using GitHub instead.

# Added Features

I've integrated lots of nice Jekyll features into the theme, such as:
* [Formspree.io](https://formspree.io/) contact form integration - just add your email to the `_config.yml` and it works!
* Your social profiles are linked from usernames you enter in `_config.yml`. Only social profiles buttons you enter in `config.yml` show up on the site footer.
* Site logo support - Easily set any image or [Font Awesome icon](http://fontawesome.io/icons/) as your logo. If you enter a Font Awesome icon class in `_config.yml` it will override the default image used as the site logo.
* Coming soon: Featured images and thumbnails in front matter for the homepage posts grid.
* Coming soon: Easy featured image settings in `_config.yml` - choose to have Jekyll use a set height for featured images or have it display the entire image, pushing the page content further down.
```

Original README from HTML5 UP:

```
Phantom by HTML5 UP
html5up.net | @ajlkn
Free for personal and commercial use under the CCA 3.0 license (html5up.net/license)


This is Phantom, a simple design built around a grid of large, colorful, semi-interactive
image tiles (of which you can have as many or as few as you like). Makes use of some
SVG and animation techniques I've been experimenting with on that other project of mine
you may have heard about (https://carrd.co), and includes a handy generic page for whatever.

Demo images* courtesy of Unsplash, a radtastic collection of CC0 (public domain) images
you can use for pretty much whatever.

(* = not included)

AJ
aj@lkn.io | @ajlkn


Credits:

	Demo Images:
		Unsplash (unsplash.com)

	Icons:
		Font Awesome (fortawesome.github.com/Font-Awesome)

	Other:
		jQuery (jquery.com)
		html5shiv.js (@afarkas @jdalton @jon_neal @rem)
		Misc. Sass functions (@HugoGiraudel)
		Respond.js (j.mp/respondjs)
		Skel (skel.io)
```

Repository [Jekyll logo](https://github.com/jekyll/brand) icon licensed under a [Creative Commons Attribution 4.0 International License](http://choosealicense.com/licenses/cc-by-4.0/).
