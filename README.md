## Deep Learning Undergrad Reading Group

### How to add your notes to the site

To add your notes to the site, (1) make a file in the `_posts` subdirectory
and (2) rerun `generate_tags.py`.

#### Uploading your notes or slides

Every post should be accompanied by the week's notes in PDF format. Please
place your notes in the `notes` folder.

> Tip: If you're exporting from Google Slides, the nicest way to do it is to
> click `File > Download > PDF Document`.

#### Adding a post

Make a file in `_posts` in the format `YYYY-MM-DD-week-##-post-title.md`. The
post should contain *front matter*, metadata separated by `---` characters,
as well as a short 2-4 sentence description of the week's reading, and why
we chose it.

> Tip: You can look in the `_posts` directory for sample posts with properly
> formatted front matter.

#### Generating tags

For now, the tag-generation process has to be done manually. If you add tags,
you need to generate their corresponding pages. To do this, you'll have to run
`python generate_tags.py` from the repository root directory. This script will
automatically generate the necessary HTML files for any new tags you may have
added with your post.
