# ken-mcewen-books

Author website for Ken McEwen: [KenMcEwenBooks.com][kmb]

## Architecture

- Domain name is registered with NameCheap domain registry.
  - A `CNAME` DNS record has been created for AWS verification.
  - An `ALIAS` DNS record has been created to display the content behind AWS Amplify main branch URL.
- AWS Amplify is used to Build/Deploy the static web files.
  - Main and Staging branches exist and are connected to amplifyapp urls.

## Development Tools

- [Bulma][bulma] is the css framework used to style the website.
  - [Sass][sass] is leveraged by Bulma, and therefore will be needed for some css edits, such as website colors.

<!-- Link References -->

[kmb]: https://KenMcEwenBooks.com
[bulma]: https://bulma.io
[sass]: https://github.com/sass/dart-sass
