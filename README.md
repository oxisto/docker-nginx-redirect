# docker-nginx-redirect

A simple Docker container containing a nginx which redirects to another URL.

## Usage

docker run -e REDIRECT_URL=http://www.your-redirect-url.com oxisto/docker-nginx-redirect -p 8080:80 .
