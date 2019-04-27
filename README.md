A production version of  https://github.com/xchintan/complex-app-dev

Prod Workflow:
    Build an app -> Push to Github -> Travis pulls the repo -> Builds and Runs test
    image -> Builds Prod Image -> Pushes Prod Imaeg to Docker Hub -> Travis Pushes
    project to AWS -> AWS Pulls the image from Docker Hub and Deploys.


