# netlify-plugin-redirects-demo

This project contains the demo for [netlify-plugin-redirects](https://www.npmjs.com/package/@helloample/netlify-plugin-redirects). 

With this plugin installed, a `_redirects` file will be generated from [CSV](https://github.com/ample/netlify-plugin-redirects-demo/blob/master/redirects.csv) and will contain contents such as the following... 

```
/ample	https://ample.co	301!
/members-only/*	/members-only/:splat	200! Role=user
/profile	/profile	200! Role=user
```

This is helpful if you need to deploy redirects based on environment or deployment context. You can see an example of the build output [here](https://app.netlify.com/sites/netlify-plugin-redirects-demo/deploys/5f2c6f6d0d2a4d0008c4a90a). 

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/ample/netlify-plugin-redirects-demo)
