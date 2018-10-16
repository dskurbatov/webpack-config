Please create a github repository containing your solutions and share with us by sending us a link to that
repo.
1. Create a new, empty npm project and write a webpack configuration that fulfills the following requirements:
- Has a single javascript file as the entrypoint into the application
- Handles Javascript/ES6/React code with both .js and .jsx file extensions; should output a single ES5 .js bundle with a unique hash added to the filename.
- Handles SCSS code with .scss extensions; should output a single .css file with a unique hash added to the filename.
- Handles IMG file with .jpeg, .jpg, .png, and .gif extensions; should return a link referencing the file
- Handles SVG file with .svg extension; return a base-64 data-encoded string if the file is < 1mb and a link to the file otherwise
Feel free to begin with the Babel "Getting Started" template from http://ccoenraets.github.io/es6-
tutorial/setup-webpack/ and modify as needed.
Webpack's docs are also helpful, in particular: https://webpack.js.org/guides/asset-management/.
Please commit your code incrementally, so we can follow your thinking.