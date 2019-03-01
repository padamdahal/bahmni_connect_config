## Clone the repository in /opt/bahmni-web/etc/
git clone https://github.com/padamdahal/bahmni_connect_config.git

## Rename the bahmni_connect_config to bahmni_config ()
mv bahmni_connect_config bahmni_config
You may create a symlink of the bahmni_config directory to the bahmni_connect_config, instead of renaming the directory

## Fetch the contents from the repository:
git pull

## Generate the concatinated configs for offline app:
bahmni -i <inventory-file> concat-configs