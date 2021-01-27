# DevBlog

The theme used is [zzo](https://zzo-docs.vercel.app/zzo).

Some config fields are secret and are expected to be loaded from environment. Create a `.env` file and run the following to pass args to hugo:

```sh
export $(cat .env | xargs);
hugo server -DEF
```

## Third party

* [**GitHub corners**](https://github.com/tholman/github-corners): MIT
* [**findAndReplaceDOMText**](https://github.com/padolsey/findAndReplaceDOMText): unlicense

## Continuous Deployment

The CD scripts are taken from https://medium.com/swlh/hosting-a-hugo-blog-on-github-pages-with-travis-ci-e74a1d686f10
