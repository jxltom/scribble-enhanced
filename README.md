# scribble-cn

## Features

- Duoshuo support

- Customized page width

## Get started

- [Fork the repository](https://github.com/jxltom/scribble-cn/fork).

- Change repository to ```your_username.github.io```

- View your pages from ```Http://your_username.github.io```

## Configuration

- Edit ```_config.yml```

- Change ```about.md``` for blog intro.

- For domain settings, see [the guide from GitHub](https://help.github.com/articles/setting-up-a-custom-domain-with-pages).

- Options during writing

    - **disqus: y**. If disqus is set to 'y', at the end of the post there will be a disqus thread, just like this one. To use disqus, you MUST [set up your own disqus account](http://disqus.com/).

    - **share: y**. An option for showing tweet and like button under a post.

    - **date**: 2013-05-06 18:07:17. Date is not a required header since Jekyll reads the file name for date, this was added in only for the **signoff time**. (as shown at the end of this post) If you don't want the signoff time, go into `/includes/signoff.html` remove the `<span>`, and remove `{% include signoff.html %}` from `/layouts/post.html`.