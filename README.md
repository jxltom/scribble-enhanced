# scribble-cn

## Features

- Duoshuo support

- Wide page width

- Enable or disable comments for each post

## Usage

- Getting started

    - [Fork the repository](https://github.com/jxltom/scribble-cn/fork).

    - Change repository to ```your_username.github.io```

    - View your pages from ```Http://your_username.github.io```

- Writing posts

    - Push new post with name ```YYYY-MM-DD-more-post.md``` in ```_posts``` folder.

    - Options in meta-data during writing

        - **disqus: y**. If disqus is set to 'y', at the end of the post there will be a disqus thread, just like this one. To use disqus, you MUST [set up your own disqus account](http://disqus.com/).

        - **share: y**. An option for showing tweet and like button under a post.

        - **date**: 2013-05-06 18:07:17. Date is not a required header since Jekyll reads the file name for date, this was added in only for the **signoff time**. (as shown at the end of this post) If you don't want the signoff time, go into `/includes/signoff.html` remove the `<span>`, and remove `{% include signoff.html %}` from `/layouts/post.html`.

- Configuration

    - Edit ```_config.yml```

    - Change ```about.md``` for blog intro.

    - For domain settings, see [the guide from GitHub](https://help.github.com/articles/setting-up-a-custom-domain-with-pages).

## Development

- Custom page width

    - Change ```max-width``` of ```footer``` and ```#container```

    - Change ```margin-left``` of ```.paging .right``` to half width pf desired width plus ```20px```

    - Change ```margin-right``` of ```.paging .left``` to half width pf desired width plus ```40px```

- GFM

    - Example of GFM

        - [Mastering Markdown](https://guides.github.com/features/mastering-markdown)

    - Features

        - Hard line breaks in paragraphs are enforced by default

        - Note that following features are not supported since Githubpages only support kramdown and kramdown doesn't support them.

            - Emoji

            - Check box

### References

- [GFM mode does not support check boxes](https://github.com/gettalong/kramdown/issues/346)
- [Feature Requests](https://github.com/gettalong/kramdown/projects/1)
- [GFM input for Kramdown not working](https://github.com/jekyll/jekyll/issues/4529)
- [kramdown Parser](https://kramdown.gettalong.org/parser/kramdown.html)
- [GFM Parser](https://kramdown.gettalong.org/parser/gfm.html)