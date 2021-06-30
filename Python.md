Install python 3.x.x from bootstrap website

set permission:
sudo chown -R $(whoami) /usr/local/bin
or sudo chown -R $(whoami) /usr/local

Change python version 
ls -l /usr/local/bin/python*

make 3.x.x default 
ln -s -f /usr/local/bin/python3.7 /usr/local/bin/python

install pip
download file
curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
execute file
python3 get-pip.py

install flask
 pip install flask
