<h1 align="center">markshust/phpstorm-magento-live-templates</h1>

<div align="center">
  <p>PHPStorm Live Templates for Magento 2</p>
  <a href="https://opensource.org/licenses/MIT" target="_blank"><img src="https://img.shields.io/badge/license-MIT-blue.svg" /></a>
</div>

## Table of contents

- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Free Course](#free-course)
- [License](#license)

## Installation

1. In PHPStorm, Go to Preferences > Tools > Settings Repository
2. Add a new Read-only Source with the URL: https://github.com/markshust/phpstorm-magento-live-templates
3. Restart PHPStorm

## Usage

With a file open, start typing the live template abbreviation. If a lot of other autocompletes show up, tap the up arrow (live template abbreviations appear last).

### Available live templates

- `magentoConfigClassPreferenceXml`: template for class preference within config XML
- `magentoConfigPluginXml`: template for plugin within config XML
- `magentoDiXml`: template for di.xml
- `magentoEventXml`: template for event.xml
- `magentoLayoutsXml`: template for layouts.xml
- `magentoLayoutViewModelXml`: template for view model within layout XML
- `magentoLayoutXml`: template for layout.xml
- `magentoModuleXml`: template for module.xml
- `magentoRegistrationPhp`: template for registration.php
- `magentoRoutesXml`: template for routes.xml

## Contributing

1. [Find the PHPStorm configuration directory](https://www.jetbrains.com/help/phpstorm/tuning-the-ide.html?_ga=2.80029911.1780511293.1585231724-1306045097.1582457949&keymap=secondary_default_for_macos#config-directory) for your operating system
2. Inside that directory is a `templates` directory
3. You can clone this repo out to this directory and submit edits to the `Magento.xml` file

All live templates are to be suffixed with either `Xml` or `Php` depending on the scope. This is to avoid confusion since a lot of templates will be created over time.

## Free Course

This course is sponsored by <a href="https://m.academy" target="_blank">M.academy</a>. Level up your Magento 2 skills with a collection of resources including lessons, courses & more.

<a href="https://m.academy" target="_blank"><img src="https://raw.githubusercontent.com/markshust/phpstorm-magento-live-templates/master/docs/macademy-logo.png" alt="M.academy"></a>

If you find this repo useful, you may enjoy the following course to learn more about relatively unknown tips, tricks & improvements for PHPStorm:

<a href="https://courses.m.academy/p/obscure-phpstorm-hacks" target="_blank">
<img src="https://raw.githubusercontent.com/markshust/phpstorm-magento-live-templates/master/docs/course.png" alt="Course image"><br />
<br />
Obscure PHPStorm Hacks
</a>

## License

[MIT](https://opensource.org/licenses/MIT)
