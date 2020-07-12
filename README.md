# zest
This is a personal collection of notes relating to content management system design

I would like to one day turn my ideas into a real project.

# repository descriptions
1. zest: for the unified download file, and description of the file structure
2. zest-cms: for the CMS, which edits only files and conforms to the file structure. Owns content types and default values.
3. zest-api-php: for the PHP api, which pulls info from the file structure
4. zest-site: uses zest-api-php to serve a website from the file structure. Owns routing and site admin pages. 
5. zest-site-plugin-cms: puts zest-cms in a plugin for zest-site, unifying the two projects
