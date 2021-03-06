## Contributing to expressjs.com

This repository is only for issues related to the website [http://expressjs.com](http://expressjs.com). For issues related to Express, the framework, go to [https://github.com/expressjs/express](https://github.com/expressjs/express).

Feel free to make changes to the template files or the document files. The supporting docs are located in their respective directories, and the API docs are located under the `_includes` directory.

## Contributing translations

**IMPORTANT:** We have professional translations of the Express documentation into:
- German
- French
- Italian
- Spanish
- Brazilian Portuguese
- Japanese
- Simplified Chinese
- Traditional Chinese
- Russian
- Korean

Therefore we can no longer accept community translations for these languages, except for corrections
to the existing translations.

We welcome contributions of translations into other languages, following the procedure below.

Follow these steps:

0. Clone the [`expressjs.com` repository](https://github.com/expressjs/expressjs.com)
1. Create a directory for the language of your choice using its [ISO 639-1 code](http://www.loc.gov/standards/iso639-2/php/code_list.php) as its name.
2. Copy `index.md`, `api.md`, `starter/`, `guide/`, `advanced/`, `resources/`, `4x/`, and `3x/`, to the language directory.
3. Remove the link to 2.x docs from the "API Reference" menu.
4. Update the `lang` variable in the copied markdown files.
5. Update the `title` variable in the copied markdown files.
6. Create the header, footer, notice, and announcement file for the language in the `_includes/` directory, in the respective directories, and make necessary edits to the contents.
7. Create the announcement file for the language in the `_includes/` directory.
8. Create a copy of the `_includes/api/en` and rename it according to the language code.
9. Make sure to append `/{{ page.lang }}` to all the links within the site.
