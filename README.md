# zest
This is a personal collection of notes relating to content management system design

I would like to one day turn my ideas into a real project.

# repository descriptions
1. **zest**: for the unified download file, and description of the file structure
1. **zest-library-php**: for the PHP api, which provides functions for pulling & editing the file structure
1. **zest-cms**: for the CMS, which uses zest-library-php. Owns content types and default values.
1. **zest-site**: uses zest-api-php to serve a website from the file structure. Owns routing and site admin pages. 
1. **zest-site-plugin-cms**: puts zest-cms in a plugin for zest-site, unifying the two projects
