# Frontity-Playground

### Documentation
Set up a new folder, and in the terminal, type "frontity react [name of site]". Frontity will then create a scaffolded react app hooked up to wordpress.

Go to frontity.settings.js and change the @frontity/wp-source to point to the wordpress website of your choice. 

If you don't have a wp site already, you can set one up with docker like so: 

After downloading docker and putting together the docker-compose.yaml file (or cloning this one), run "docker compose up -d" to build the container associated with this project. Your docker-compose.yaml should have configs for phpmyadmin, MySQL, and WordPress. 

For more detail, see: https://gist.github.com/bradtraversy/faa8de544c62eef3f31de406982f1d42

Otherwise, you can use ngnix to set up a WP site (not the method I used, but also an option) - https://www.ionos.com/digitalguide/hosting/blogs/wordpress-nginx/