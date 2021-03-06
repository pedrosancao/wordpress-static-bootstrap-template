# Wordimpress Bootstrap template

Bootstrap template for Wordimpress, a static site generator using Wordpress API as content source.
The project still a prototype.

This implementation retrieves content from [https://wordpress.org/news](https://wordpress.org/news).

## Black lives matter

**This repository has no master**. Read more:
[GitHub abandons 'master' term to avoid slavery row][master-replace].

## Key features

- uses Twig as template engine
- supports Sass (using Bootstrap Sass via composer)
- support Facebook comment plugin
- built-in watcher to compile as files change
- convert images to WebP format
- supports markdown to HTML

## Usage

Copy ".env.example" to ".env" and adjust the properties.

Install composer packages: `composer install`.

To compile templates, Sass and copy media once run `composer run-script compile`
and to keep watching for changes `composer run-script watch`.

To compile all minifying the generated CSS use `composer run-script prod`.

## To do list

Tasks prioritized are updated on the library [pedrosancao/wordimpress][0] project.

[0]: https://github.com/pedrosancao/wordimpress/
[master-replace]: https://www.bbc.com/news/technology-53050955
