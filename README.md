# CIT384-vHostAndHtaccess

# We had to create a dockerfile that will do the following

1. Create a user, `public_html` directory for that user and add a index.html file to that directory
1. Create a `dev` directory under `public_html` and add another index.html with some confidential information this time. 
1. Place the .htaccess file under `Dev` directory that will ask for password to view the contents of that directory. 
1. Create 3 more directory under `/var/www/html` to host 3 websites with [Name Based](https://httpd.apache.org/docs/2.4/vhosts/name-based.html) routing and add a index.html file in each of the directories.     
1.  Create 3 vHost files
- site1.conf
  - Use `site1.internal` as domain name
  - Update DocumentRoot
  - Add Alias Directive for the user created above
- site2.conf
  - Use `site2.internal` as domain name
  - Update DocumentRoot
- site3.conf
  - Use `site3.internal` as domain name
  - Update Document Root
1. Update `/etc/hosts` files for the above three domains   
