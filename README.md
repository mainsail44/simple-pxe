# simple-pxe

# DOWNLOAD RHEL

If you need to download RHEL 9.x get a offline api key from here:  https://access.redhat.com/management/api
Get the checksum for RHEL 9.x from the Red Hat Downloads page. 
Then add the API Key & Checksum to roles/pxe/defaults/main.yml
Then set DOWNLOAD_RHEL: to "true"

# ADD SSH KEYS

Add your ssh public key to the new pxe booted server via: roles/pxe/defaults/main.yml, METALVISOR_SSH_PUBLIC_KEY