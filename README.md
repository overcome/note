# note
Tech partials note


# How to config email from name in piwik?
Error:
Error was 'Mail from must equal authorized user'

Solution:
1. Find config/config.ini.php
2. Add new line in [General] section:
    
  noreply_email_address = 'From email address'
