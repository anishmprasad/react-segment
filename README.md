# react-segment
Segment.io integration for React.js


### Installation

```
// with npm
$ npm install react-segment --save

// with yarn
$ yarn add react-segment
```

Getting started
---------------

If you're developing using npm and CommonJS modules:

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


Issues
------
Please [file an issue](https://github.com/Anishmprasad/react-segment/issues) if you find a bug, or need help.


License
-------
The MIT License (MIT)
Copyright (c) 2019 Anish M Prasad
