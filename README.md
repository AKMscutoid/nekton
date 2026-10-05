# Mr Miller's Hugo Theme

A lightweight hugo theme used on [my website](https://austinmiller.pro).
## Configuration

```sh
hugo new site new-site
cd new-site
git clone https://github.com/127Gar/shulgi themes/shulgi
echo "theme = 'shulgi'" >> config.toml
cp themes/shulgi/static/style.css static/
```

## Notes

- Makes one RSS feed for the entire site at `/index.xml`
- Stylesheet is in `/style.css` and includes some important things for partials.
- If a post is tagged, links to the tags are placed at the bottom of the post.
- `nextprev.html` adds links to the Next and Previous articles to the bottom of a page.
- `taglist.html` links all tags an article is tagged to for related content.
- `rawhtml.html` for inserting raw HTML into markdown.
