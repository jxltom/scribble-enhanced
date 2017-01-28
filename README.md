An enhanced [scribble](https://github.com/muan/scribble) Jekyll theme. [https://jxltom.github.io/scribble-cn/](https://jxltom.github.io/scribble-cn/).

## Overview

- Features

    - Wide page

    - Enable/disable comments for each post

- Intergrations

    - [Disqus](https://disqus.com/)

    - [duoshuo](http://duoshuo.com/)

    - Google Analytics

## Usage

- Getting started

    - [Fork the repository](https://github.com/jxltom/scribble-cn/fork).

    - Change repository name to ```yourgithubusername.github.io```.

    - Set ```master``` branch as source of GitHub Pages. Then your website will be ```Http://yourgithubusername.github.io```.

- Configuration

    - Configuration of ```_config.yml```

        - Set ```url``` if you website domain is not ```yourgithubusername.github.io```.

    - Change ```about.md``` for ```about``` page.

    - For custom domain settings, set ```CNAME``` to your domain.

- Posts

    - Push new post with name as ```YYYY-MM-DD-post-name.md``` in ```_posts``` folder.

    - Options of a post. You can add options in meta-data of post source.

        - ```comment: y```. If ```comment``` is set to ```y```, at the end of the post there will be a ```Disqus``` or ```duoshuo``` thread. To enable comments, you also need to provide ```disqus_shortname``` or ```duoshuo_id``` in ```_config.yml```.

        - ```share: y```. An option for showing tweet and like button under a post.

    - GFM

        - Start header from ```##``` in your post since the post title will be considered as ```#```.

        - Hard line breaks in paragraphs are enforced by default in GFM parser of kramdown, which is the only parser of markdown in GitHub.

        - Note that following features of GFM are not supported since kramdown GFM parser, which is the only Github mardown parser, doesn't support them currently.

            - Emoji

            - Check box

## Development

Note that there are currently two branches. **All development should be pushed to ```master```**. Branch ```gh-pages``` is only for demo.

- Custom page width

    - Change ```max-width``` of ```footer``` and ```#container```.

    - Change ```margin-left``` of ```.paging .right``` to half width of desired width plus ```20px```.

    - Change ```margin-right``` of ```.paging .left``` to half width of desired width plus ```40px```.

### TODO

- SEO optimization

- Better share function

- CNZZ integration

- Tags support

### References

- [Mastering Markdown](https://guides.github.com/features/mastering-markdown)
- [GFM mode does not support check boxes](https://github.com/gettalong/kramdown/issues/346)
- [Feature Requests](https://github.com/gettalong/kramdown/projects/1)
- [GFM input for Kramdown not working](https://github.com/jekyll/jekyll/issues/4529)
- [kramdown Parser](https://kramdown.gettalong.org/parser/kramdown.html)
- [GFM Parser](https://kramdown.gettalong.org/parser/gfm.html)
- [The Open Graph protocol](http://ogp.me/)