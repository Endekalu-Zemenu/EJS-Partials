# Express Static Website

This is a simple Express.js application that serves static files and renders dynamic HTML using EJS templates.

## Installation

1. Clone this repository:

```bash
git clone https://github.com/Endekalu-Zemenu/EJS-Partials
```
2. Install dependencies:
```npm
npm install
```
## Usage
To start the server, run:
```node
node index.js
```
## Folder Structure
```markdown
- public
  - images
  - styles
- views
  - partials
    - header.ejs
    - footer.ejs
  - index.ejs
  - about.ejs
  - contact.ejs
- index.js
- package.json
```
## Routes
1. `/` - Renders the index page.
2. `/about` - Renders the about page.
3. `/contact` - Renders the contact page.
### Dependencies
`Express.js` and `EJS`
### Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request.
### License
This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
