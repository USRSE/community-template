# U.S. Research Software Community Template

This is a community template for a USRSE group. It is provided for you
to copy to the [usrse GitHub](https://www.github.com/usrse) and then
have a portal for your center.

**under development** please don't clone and use until it's ready!

## How does it work?

### 1. About you!

You can modify the [about.md](pages/about.md) file to add information about your
center. This will show up on the Community -> About tab.

### 2. Add People

Any interested RSE at your institution can add their
metadata to the [people.yml](_data/people.yml) file. Here is an example
of the required fields that we collect:

```yaml
- name: "Vanessa Dinosaur"
  image: https://profiles.stanford.edu/proxy/api/cap/profiles/23263/resources/profilephoto/350x350.1509557842883.jpg
  url: https://profiles.stanford.edu/vanessa-sochat
  title: Research Software Dinosaur
```

### 3. Write Posts

If you want to use your community space to write articles or post news, you can
do so by adding a new markdown file to the [_posts](_posts) folder. We've left
a few entries there for you as examples. If you then want your post feed to
automatically appear on the [https://us-rse.org/blog](https://us-rse.org/blog)
site, your feed is located at the baseurl + `feed.xml`. So for this template, it
would be at https://localhost:4000/community-template/feed.xml.

## Development

To develop the site, clone the repository and then build with jekyll:

```bash
bundle exec jekyll serve
```

### Important Notes

The "posts" page under the [posts](posts) folder is intentionally separate from
the other pages in [pages](pages) because the pagination plugin needs to find an
index.html to parse. Please don't rename or change the location of this file.

## Credit

The original template was from [bootstrap-clean-jekyll](https://github.com/BlackrockDigital/startbootstrap-clean-blog-jekyll) 
and has been simplified and updated for this case.
