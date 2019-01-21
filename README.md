
This is a **draft** personal website for academic communication. The website address is https://crenteriam.github.io/

The Website is based on [Lanyon](http://lanyon.getpoole.com/). I also adapted some HTML code from [Vitaly Repin's blog](https://github.com/vitalyrepin/vrepinblog). Other exemplary Lanyon themes are [Bradley Boehmke's website](https://bradleyboehmke.github.io/), [Paul Len's Lagrange](https://lenpaul.github.io/Lagrange/menu/about.html), and [UC R Github](https://github.com/uc-r/uc-r.github.io).

Other materialsPersonal site based on:

# Lanyon

http://lanyon.getpoole.com/

AND 
# Vrepinblog
https://github.com/vitalyrepin/vrepinblog

O# Instructions

1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section
1. (Optional) Use the Jupyter notebooks or python scripts in the `markdown_generator` folder to generate markdown files for publications and talks from a TSV file.

See more info at https://vrepin.org/vr/en/index.html

Another good Jekyll template for an academic website: [Academicpages Template](https:/s:.
https://academicpages.github.io/academicpages.github.io/)

[Basic Markdwon Swriting and formatting syntax](https://help.github.com/articles/basic-writing-and-formatting-syntax/)

[![Creative Commons Lizenzvertrag](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)## To run locally (not on GitHub Pages, to serve on your own computer)

1. Clone the repository and made updates as detailed above
1. Make sure you have ruby-dev, bundler, and nodejs installed: `sudo apt install ruby-dev ruby-bundler nodejs`
1. Run `bundle clean` to clean up the directory (no need to run `--force`)
1. Run `bundle install` to install ruby dependencies. If you get errors, delete Gemfile.lock and try again.
1. Run `bundle exec jekyll liveserve` to generate the HTML and serve it from `localhost:4000` the local server will automatically rebuild and refresh the pages on change.

----
A Github Pages template for academic websites. This was forked (then detached) by [Stuart Geiger](https://github.com/staeiou) from the [Minimal Mistakes Jekyll Theme](https://creativecommons.org/licenses/by-sa/4.0/) mmistakes.github.io/minimal-mistakes/), which is © 2016 Michael Rose and released under the MIT License. See LICENSE.md.
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTEwMTgwNzA0MywxMzA4NzIzOV19
-->