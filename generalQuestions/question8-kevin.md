* If you have 5 different stylesheets, how would you best integrate them into the site?

One the first things I think about when I see the number 5 (representing the number of stylesheets) is that your webpage will need to make 5 different requests in order to acquire these CSS assets. Combining these CSS files into one would reduce the number of concurrent requests your browser needs to make in order to fetch assets. In order to simplify this concatenation and optimize it further with minification, I would use a task runner or 'buildpack' for deployment.

These applications can help to minimize the repetitive tasks like bundling and minifying your application and I personally like webpack, which runs automatically on save.

Of course, now that I think about it, one other potential optimization that would work on a multi-page web application is to split up your CSS by the pages that use those specific styles. This would reduce the size of downloads so that your users' browsers will only download the bare minimum needed to style your webpage at any given time.