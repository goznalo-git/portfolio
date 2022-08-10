# My portfolio

As soon as I learned that one can host their own website on GitHub, I decided to go for it. This is the result of my incursion into that territory.

I am always up for adventure, hence I decided to create something slightly more sophisticated than a plain html+css site. GitHub itself recommends _Jekyll_, a static webpage compositor, which is integrated in GitHub Pages. I decided to give it a try, it didn't seem that complicated.

The headaches came with the theming part: after researching a bit, I found a theme which I found appealing, _Hyde_ (or, rather, its _Hydeout_ version, available in [this repository](https://github.com/fongandrew/hydeout) ). In the end I managed to subjugate it and damn, does it seem cool.

## Structure of this repo

This repo's structure follows closely that of the original repository: the homepage is contained in `index.html`, with each page refered to in the sidebar lies in the `categories/` directory. Blog posts (WIP) will be kept in the `_posts/` directory, if I ever write any.

Each page has a header, read by Jekyll, telling Jekyll about the needed layout, the title of the page and whether it should be included in the sidebar or not. Layouts themselves are stored in `_layouts/`, I have barely touched them. Html chunks are also stored in their original directory, `_includes/`, and are called using Liquid syntax (e.g. `{% include timeline.html%}`). Finally, .scss style files are contained in `_sass/hydeout/`, then called by `_sass/hydeout.scss` and this is itself imported by `assets/css/main.scss`.

I have, however, made a few changes: some css and html includes have been removed as I do not intend to use them, for instance those related to RSS and tags. Other smaller ones too, such as those related to a back arrow.

I have also included two folders, `files/` and `imgs/`, where some PDFs and images can be found (although refering to them within the code was quite painful).

## Usage and troubleshooting

Jekyll is built with the Ruby language. While I know nothing about that language, and the components surrounding it, I still managed to set this site up and fix some errors along the way. 

After cloning this repository, navigate to the folder, and run `bundle install`. AFAIK this reads the content of the `Gemfile` file (containing gems, which are like libraries, and remote sources from which gems can be downloaded), and installs all gems (dependencies). For more information, check out [https://jekyllrb.com/docs/ruby-101/](https://jekyllrb.com/docs/ruby-101/). If there are no errors, we can test this repo locally by running `bundle exec jekyll serve` and navigating to the site shown afterwards (usually something like [http://localhost:4000/portfolio](http://localhost:4000/portfolio).

I have happened to come across an error during the installation: the gem 'http_parser.rb' failed to install its version 0.6.0. This is a problem of that version, and installing a higher version (e.g. `bundle install http_parser.rb --version 0.6.1`) should suffice.
