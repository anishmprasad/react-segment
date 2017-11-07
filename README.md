# react-segment
Segment.io integration for React.js



Getting started
---------------

If you're developing using npm and CommonJS modules:
```
npm i react-segment
```
```jsx
let analytics = require('react-segment');

if(process.env.NODE_ENV == 'development'){
    analytics.default.load("DEVELOPMENT KEY");
}else if(process.env.NODE_ENV == 'staging' ){
    analytics.default.load("STAGING KEY");
}else if(process.env.NODE_ENV == 'pre-production'){
    analytics.default.load("PRE-PRODUCTION KEY");
}else if(process.env.NODE_ENV == 'production'){
    analytics.default.load("PRODUCTION KEY");
}
```

Don't see your prop? explaining your use case, and I will add it.

Packages Needed
---------------
* prop-types : ^15.5.4
* react : ^15.4.2
* react-dom : ^15.4.2

Testing
-------
The tests are written using [mocha](https://github.com/mochajs/mocha), and ran using [Karma](https://github.com/karma-runner/karma). Run the command `npm test` to perform a single run of the tests in PhantomJS, and `npm run test:dev` to debug the tests in Chrome.

Issues
------
Please [file an issue](https://github.com/Anishmprasad/react-segment/issues) if you find a bug, or need help.


License
-------
The MIT License (MIT)
Copyright (c) 2017 Anish M Prasad
