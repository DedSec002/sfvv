[IP Lab HW1](https://courses.ncsu.edu/csc573/lec/001/wrap/proj1.pdf)

export PYTHONPATH='../'

##Run rserver
python rserver.py -c ../config.json -d

##Run client
python client.py -c ../config.json -i 1 -d

##TODO
no pickle failure
Update readme
move rfc folder into project dir
add 60 RFCs