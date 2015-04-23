# Publican Manual for ERPNext
This a fork of https://github.com/frappe/manual_erpnext_com build with DocBook/XML and Publican

## Install Publican
Please see http://docs.fedoraproject.org/en-US/Fedora_Contributor_Documentation/1/html/Users_Guide/chap-Users_Guide-Installing_Publican.html

## Install ERPNext Brand
1- wget https://williamjmorenor.fedorapeople.org/publican-ERPNext-0.1.tar.gz

2- tar xvzf publican-ERPNext-0.1.tar.gz

3- cd publican-ERPNext

4- publican build --formats xml --langs all --publish

5- sudo publican install_brand --path path

where path is the path to the Publican Common Content files. For example, on a Linux system, run:
sudo publican install_brand --path /usr/share/publican/Common_Content
or on a Windows system, run

publican install_brand --path "C:/Program Files/Publican/Common_Content"

# Build the manual
1- git clone https://github.com/williamjmorenor/manual_erpnext_publican.git

2- cd manual_erpnext_publican

3- publican build --langs=all --formats=pdf,html,epub

