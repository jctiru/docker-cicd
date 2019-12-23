# Docker React CICD to AWS Elastic Beanstalk using Travis CI

[![Build Status](https://travis-ci.com/jctiru/docker-cicd.svg?branch=master)](https://travis-ci.com/jctiru/docker-cicd)

1. Push code in master branch to github
2. Travis automatically pulls repo
3. Travis builds image, tests code
4. Travis pushes code to AWS EB
5. EB reads Dockerfile, builds image, deploys it
