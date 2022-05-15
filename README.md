# Heroku buildpack to install Rust and wasm

## [Using this buildpack](https://devcenter.heroku.com/articles/buildpacks#using-a-third-party-buildpack)

If you're creating a new Heroku application,

```sh
heroku create myapp --buildpack https://github.com/sfktrkl/heroku-buildpack-rust-wasm.git
```

To use this as the buildpack for an existing application,

```sh
heroku buildpacks:set --index=1 https://github.com/sfktrkl/heroku-buildpack-rust-wasm.git -a myapp
```
