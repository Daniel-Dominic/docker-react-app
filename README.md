This is Intended to do with docker. If you have docker installed follow the given instructions:
- Clone the repo: `git clone git@github.com:Daniel-Dominic/revolving-react-logo-webpage.git`
- Move into the repo `cd revolving-react-logo-webpage`
- Run this docker command: `docker build -t react-app .`           #This creates a docker image
- To run the image: `docker run --rm -p 3000:80 --name react react-app`
- Open up your browser and type `localhost:3000`
<br>
 
When you are tired seeing the running website: `docker kill react`
