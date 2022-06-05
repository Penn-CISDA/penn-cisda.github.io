This is the GitHub repo of the official website for CISDA, the Computer and Information Science Doctoral Association at the University of Pennsylvania. The website is run with Jekyll.

To make changes to the website, submit a pull request or email [cisda-chairs@seas.upenn.edu](mailto:cisda-chairs@seas.upenn.edu) to be added. In the second case, you can clone the repo and push from your local machine.

To add a person to the People page, edit `/_data/people.yml` following the given structure and add their headshot to `/assets/img`.

To add a guide to the Guides page, make a copy of the `YYYY-MM-DD-guide-title.md` guide template. Make sure you title the file correctly or it will not show up online. Inside the file, update the `title`, `submitted_by`, and `edited_by` fields and insert the content of your guide where indicated. Jekyll can parse Markdown and HTML at the same time, so feel free to format your guide as you'd like. Move your file to `/_posts/guides`. If done correctly, you will see a link to your guide on the Guides webpage.

More substantial changes will require knowledge of [Jekyll](http://jekyllrb.com/docs/usage/). We use the [Minima](https://github.com/jekyll/minima) theme.

Before pushing, run the following command to preview your changes.
```
bundle install # if launching for the first time

bundle exec jekyll serve
```