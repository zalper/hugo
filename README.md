# hugo


<b>New Setup:</b>  
Step 1:  
Create repository on github.com and clone it into your local.

Step 2:  
Install Hugo:  
sudo apt -y install hugo

Step 3:  
In your root folder of repository  
hugo new site <YOUR_WEBSITE_NAME>

Step 4:  
Update your info in config.toml file and add theme = "YOUR_THEME_NAME"

Step 5:  
Install your selected theme  
cd /themes  
git submodule add https://github.com/YOUR_THEME_REPOSITORY.git

Step 6:  
Add & Commit your git changes and push to origin
