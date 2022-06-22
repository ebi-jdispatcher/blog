## Job Dispatcher's Team Blog

The EMBL-EBI's Job Dispatcher Team is responsible developing [Job Dispatcher Services](https://www.ebi.ac.uk/services/teams/jdispatcher).

This blog is powered by [Jekyll](http://jekyllrb.com/) and [Github Pages](https://pages.github.com/) and others. It uses the [Jasper2](https://github.com/jekyllt/jasper2) Theme.

## Developing locally

Install dependencies with bundle:
```bash
bundle install --path ./vendor/bundle
```

Then run locally:

```bash
bundle exec jekyll serve
```

## Deployment to GitHub Pages

Github actions is used to build and publish the static website. Simply push changes or submit PR's to get your posts or changes published.

## Adding new authors

This blog supports multiple authors. Add a new author info to [\_data/authors.yml](_data/authors.yml) and add the 
corresponding `username` to `author` in the front matter of every post.

## Adding new tags

This blog supports multiple tags. Each post can be tagged with multiple keywords. Add a new tag info to [\_data/tags.yml](_data/tags.yml) and add the 
corresponding `name` to `tags` in the front matter of every post.

## Generating Markdown tables

Thanks to [Tables Generator](https://www.tablesgenerator.com/markdown_tables) we can easily generate tables in Markdown.

## Compiling CSS styles

CSS styles are compiled using Gulp/PostCSS to polyfill future CSS spec. You'll need Node and Gulp installed globally. After that, from the theme's root directory:

```bash
$ npm install
$ gulp
```

Now you can edit `/assets/css/` files, which will be compiled to `/assets/built/` automatically.

## Thanks

Many thanks to the Ghost team for all the design work. Also many thanks to all contributors of [Jasper2](https://github.com/jekyllt/jasper2).


## Copyright & License

Copyright (C) 2022 - Released under the MIT License.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
