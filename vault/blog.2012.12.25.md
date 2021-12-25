---
id: JZYGcVtk41Q4za4lfc3Id
title: '25'
desc: ''
updated: 1640452175524
created: 1640451728735
---

* [x] golang text template + json
* [x] docker containers running ruby scripts
* [x] dendron publishing to netlify
* [ ] dendron publishing to github.io

Github.io's build log reports that it is builing a Jekyl project. However it seems to be failing to find an index page as a 404 is evident from the root of the published site. There are no errors in the Git pipeline.

Netlify build looks like its based upon Next.js. It works as expected and even runs locally with :

```
npx dendron publish dev
```


