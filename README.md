# The Myth of Coyote

### Creating Source Material Items

`*.md` files should be named lowercase with hyphens, as these will be translated by Jekyll directly into URLs.

All source materials should have corresponding `_build/sources/_posts` files.

As those are Jekyll posts, they need to conform to the `YYYY-MM-DD` naming convention. For consistency, let's use this for the date the file was created, **not** the original publication date.

An optional `pubdate` value can be provided in the YAML front matter. This can be omitted if unavailable.

Each `_build/sources/_posts` file must include in the YAML front matter:

* `layout: source`
* `title: ...`: Title of the source item.
* `category: ...`: A single category this item will appear under in the index.
* `tags: ...`: A [YAML list](https://en.wikipedia.org/wiki/YAML#Lists) of tags.
* `type: ...`: article, image, text – Try to stick to a concise set of consistent values.

Optional fields include:

* `pubdate: ...`: Original publication date, in the YYYY-MM-DD format.
* `source: ...`: Available to document the source of the item.