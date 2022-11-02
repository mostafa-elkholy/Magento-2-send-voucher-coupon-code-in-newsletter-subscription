# Mostafa Mohamed Elkholy 
# 00201006776010
# Melkholy@maxmize.com, Melkholy@live.com

generate a couponcode after customer subscripe to the newsletter and send it via email

Please enabled and install the module using the below commands.

#COPY CODE
upload files to app/code

#Enable module 
php bin/magento module:enable Maxmize_Newsletter
php bin/magento setup:upgrade
php bin/magento setup:di:compile
