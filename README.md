# Highlights

Highlights is a simple one page site originally created by [HTML5UP](http://html5up.net). This Hugo theme is a port of theme.
All the information for creating the site is stored at the [config.toml](https://raw.githubusercontent.com/schmanat/hugo-highlights-theme/master/exampleSite/config.toml).
This theme provides the following features

* contact form (via formspree.io)
* Google Analytics
* responsive

![Hugo Highlights Theme screenshot](https://raw.githubusercontent.com/schmanat/hugo-highlights-theme/master/images/screenshot.png)

## Installation

Inside the folder of your Hugo site run:

    $ cd themes
    $ git clone https://github.com/schmanat/hugo-highlights-theme

For more information read the official [setup guide](//gohugo.io/overview/installing/) of Hugo.

## Getting started
After installing the Hugo Highlights Theme it requires a just few more steps to get your site running.

### The config file
Take a look inside the [`exampleSite`](//github.com/schmanat/hugo-highlights-theme/tree/master/exampleSite) folder of this theme. You'll find a file called [`config.toml`](//github.com/schmanat/hugo-highlights-theme/tree/master/exampleSite/config.toml)

### Change the background images
It's possible to change the background files for every section (about, services, ... ). To do this you could set every image in the [`config.toml`](//github.com/schmanat/hugo-highlights-theme/tree/master/exampleSite/config.toml) of your site. The files are stored at `static/images/`.

### Present your skills
This section should show your capabilities and skills. You can change this serverics at `[params.services` in the [`config.toml`](//github.com/schmanat/hugo-highlights-theme/tree/master/exampleSite/config.toml).

All icons are part of Fontawesome's icon font. Look at the website of [Fontawesome](//fortawesome.github.io/Font-Awesome/icons/) for more icons. The icons are represented by their corresponding CSS class of Fontawesome. A skill is defined like this example:

```toml
[[params.services]]
  icon = "fa-camera-retro"
  title = "Magna Etiam"
```

### Make the contact form working
Since this page will be static, you can use [formspree.io](//formspree.io/) as proxy to send the actual email. Each month, visitors can send you up to one thousand emails without incurring extra charges. Begin the setup by following the steps below:

1. Enter your email address under 'email' in the [`config.toml`](//github.com/schmanat/hugo-highlights-theme/tree/master/exampleSite/config.toml)
2. Upload the generated site to your server
3. Send a dummy email yourself to confirm your account
4. Click the confirm link in the email form www.formspree.io
5. Thats all. Enjoy mailing!


### Nearly finished
In order to see your site in action, run Hugo's built-in local server.

    $ hugo server

Now enter [`localhost:1313`](http://localhost:1313) in the address bar of your browser.

## Contributing
Did you found a bug or got an idea for features? Feel free to use the [issue tracker](//github.com/schmanat/hugo-highlights-theme/issues) to let me know.

## License

The theme is licensed under the [Creative Commons Attribution 3.0 Unported](https://creativecommons.org/licenses/by/3.0/)

## Acknowledgements

Thanks to

- [HTML5UP](http://html5up.net) for creating this theme
- [Steve Francia](//github.com/spf13) for creating Hugo and the awesome community around the project.
