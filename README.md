# Octoprint-Printinfo
Octoprint plugin and Wordpress Plugin to display live print information on a wordpress website.

There are two plugins to install;

## Octoprint - Printinfo Plugin
This plugin sends information of your current print job to wordpress. Only the file and percentage complete. More to add soon
Settings -> Add your wordpress URL and the generated token from https://pass.node0a.com, scroll down. 

## Wordpress - OctoPrint Print Info
Creates a REST API Endpoint to receive the print information from the octoprint plugin. 
Setting -> OctoPrint Print Info -> Paste your token and save. 
The same token will need to be added to the settings section of Octoprint plugin. 

You can generate a token here https://pass.node0a.com

