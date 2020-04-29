# site drupal 8 code base
This is a site drupal 8 with kubernete

## Local environnemenet

Make sure you have docker installed, then run the following commands(in the same directory as this README file)
 1. Build the lical Drupal docker image:
  ...
  docker build -t drupal8-for-kubernetes:latest .
  ...

 2. start the llcal developement environnement with docker-compose
   ...
   docker-compose up -d
   ...

 After the environnment is running , you can visit http://localhost/ and see the Drupal site

