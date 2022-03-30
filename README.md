# react-component-template
A React component template that you can publish to npm easily
#

This is a template you can use to start making an awesome react component, it is built up by [this](https://dev.to/alexeagleson/how-to-create-and-publish-a-react-component-library-2oe) guide (also saved as pdf in /docs)

After using this repo as a template, run:

`npm install`

And then update the packages if necessary, I will try to keep this up to date

#
Then I would recommend following the aforementioned guide, or just follow this simplified version:
<br>
<br>

Make a .npmrc in your home folder (linux/mac), C:\Users\{YOUR_WINDOWS_USERNAME} (windows) (I think)

Put the following in the file:
```
registry=https://registry.npmjs.org/
@YOUR_GITHUB_USERNAME:registry=https://npm.pkg.github.com/
//npm.pkg.github.com/:_authToken=YOUR_AUTH_TOKEN
```

The auth token needs the `write:packages` access. Write your username in lowercase

When your finished run `npm publish`

It might take a while (took a bit for me) but the packages should show up under your profile in the "Packages" tab.

But as I said again, I would recommend following the aforementioned guide, this is just a template that has everything installed.