# MongoDBGrapesSearch-P1

MongoDBGrapesSearch-P1 is a powerful, easy-to-integrate search plugin for GrapesJS that leverages MongoDB's full-text search capabilities and Bootstrap for a responsive and visually appealing UI. Enhance your GrapesJS projects with a robust search feature that offers seamless integration with MongoDB and an elegant design using this plugin.

## Directory Structure

mongodb-grapes-search-p1
├── dist
│ └── index.js
├── src
│ ├── index.js
│ ├── search-plugin.js
│ └── search-api.js
├── package.json
├── rollup.config.js
├── .babelrc
└── README.md

## Installation

```shell
npm install mongodb-grapes-search-p1
```

## Usage

```javascript
import grapesjs from "grapesjs";
import MongoDBGrapesSearchP1 from "mongodb-grapes-search-p1";

const editor = grapesjs.init({
  // editor configurations
});

new MongoDBGrapesSearchP1(editor);
```

## Contributing

If you'd like to contribute to the development of MongoDBGrapesSearch-P1, please follow these steps:

- Fork the repository on GitHub.
- Clone your fork to your local machine: git clone https://github.com/<your-username>/mongodb-grapes-search-p1.git
- Create a new branch for your changes: git checkout -b <branch-name>
- Make your changes and commit them to the branch.
- Push the changes to your fork: git push origin <branch-name>
- Create a pull request on GitHub to merge your changes into the main repository.

## License

MIT License
