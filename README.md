# wkhtmltopdf

wkhtmltopdf for odoo , follow below steps

sudo wget  https://github.com/ananthukrishna/wkhtmltopdf/raw/master/wkhtmltox-0.12.1_linux-trusty-amd64.deb

Install the package using command

dpkg -i wkhtmltox-0.12.1_linux-trusty-amd64.deb

Copy wkhtmltoimage to /usr/bin location from /usr/local/bin by using below command

sudo cp /usr/local/bin/wkhtmltoimage /usr/bin/wkhtmltoimage

Copy wkhtmltopdf to /usr/bin location from /usr/local/bin by using below command

sudo cp /usr/local/bin/wkhtmltopdf /usr/bin/wkhtmltopdf
