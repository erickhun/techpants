# techpants.io

- See [spreadsheet](https://docs.google.com/spreadsheets/d/1b10Z7avvyVsbqHBqfNaoVelukA7DzOPZRVpN4-UD5IQ/edit#gid=0)



### Install
```
brew install hugo # check https://gohugo.io/getting-started/installing/ for alternative method
git clone https://github.com/erickhun/techpants.git
cd blog
hugo server -D # launch a server and serve it at http://localhost:1313/
```

### New post
```
hugo new "posts/my-post.md"
```

### Structure
- `content` is where we edit posts
- `docs` is where all generated files ends up. , usually never touch it
- We use the [book](https://github.com/alex-shpak/hugo-book#menu) theme. 


### Deploy

`sh deploy.sh`
