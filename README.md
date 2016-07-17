## zpallin/nodejs-starter

I wanted to have a basic framework to kick off nodejs projects from with docker to remove some of the headache of setting up a repo constantly.

I predict I will rarely take time to add anything to this... if you happen to find or use this, feel free to submit pull requests.

Cheers

## Inspiration

Thanks nodejs for being really easy to setup in the first place.

## Launching your Docker Image

### with Docker

I followed this tutorial: https://nodejs.org/en/docs/guides/nodejs-docker-webapp/

Once you pull the repo, run:

`docker build -t docker build -t <your username>/node-web-app .`

Followed by:

`docker run -p 49160:8080 -d <your username>/node-web-app`

and now you can reach your app at http://localhost:49160.

## License

Apache License 2.0


