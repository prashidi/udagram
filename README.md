Udacity Cloud Engineering Nanodegree Project 2: Udagram

## Github Repository
https://github.com/prashidi/udagram

## Local deployment
1. npm i
2. npm run dev
3. eb init 
4. Modify the .elasticbeanstalk/config.yml file to include deploy:
  artifact: ./www/Archive.zip
5. npm run build
6. eb create 
7. eb deploy

## EB endpoint

Dev:  http://udagram-rashi-dev.us-east-1.elasticbeanstalk.com

Example: http://udagram-rashi-dev.us-east-1.elasticbeanstalk.com/filteredimage?image_url=https://images.pexels.com/photos/45201/kitty-cat-kitten-pet-45201.jpeg

## Screenshots

Please check in the route directory/deploement_screenshots