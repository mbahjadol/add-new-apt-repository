# add-new-apt-repository
This script is to to make it easier to add the ubuntu repository which since the last ubuntu update version made the apt-key command deprecated, and this script helps to add a new repository according to the new procedures implemented by ubuntu with gpg-keyring easily.

## Usage:
 download the script add-new-apt-repository and chmod +x to this script then you can run this script.
 warning this script need sudo to run so you will need to entry your password if you not root user.

## Parameter:
- first parameter is url of file is an armored ASCII file used by Pretty Good Privacy (PGP)
- second parameter is url of file description of debian list repository info
All parameter you can add with 'https://' or no

## Examples:
- ./add-new-apt-repository packages.microsoft.com/keys/microsoft.asc packages.microsoft.com/config/ubuntu/20.04/mssql-server-2019.list

- ./add-new-apt-repository https://packages.microsoft.com/keys/microsoft.asc https://packages.microsoft.com/config/ubuntu/20.04/mssql-server-2019.list

