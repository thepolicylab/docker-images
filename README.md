# docker-images

Some docker images we use at The Policy Lab.

## Adding new images

If you'd like to add a new image, complete the following steps:

* Create a new folder with the name of the image, e.g., `foo-base`.
* In that folder, create a `Dockerfile` that creates your container however you'd like.
* In `.github/workflows/build.yml` look at the `Build docker image` section and create
  a similar one for your container.


## License

MIT