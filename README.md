# WP-File-Permission

```
sudo chgrp -R www-data .
sudo find . -type d -exec chmod g+rwx {} +  # Change directory permissions 755
sudo find . -type f -exec chmod g+rw {} +  # Change file permissions 644
```
