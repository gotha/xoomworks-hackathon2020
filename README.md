# Website for Xoomworks' 2020 Hackathon

## Local  

First [install Hugo](https://gohugo.io/getting-started/installing/)

Clone the repo and update the submodules:

```sh
git clone git@github.com:gotha/xoomworks-hackathon2020.git
cd xoomworks-hackathon2020/
git submodule update --recursive
```

All the pages and posts are in the `content` folder.

Make your changed and previw them by running:

```sh
hugo server
```

and then visit [http://localhost:1313](http://localhost:1313)

Once your PR is merged the changes will be automatically deployed (check `buildspec.yaml`).
