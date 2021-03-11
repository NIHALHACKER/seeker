# TERMUX ONLY WORKING 

* `pkg update && pkg upgrade`

* `pkg install php python openssh -y`

* `git clone https://github.com/NIHALHACKER/seeker.git`

* `pip3 install requests`


# USAGE
```
python3 seeker.py -h

usage: seeker.py [-h] [-s SUBDOMAIN]

optional arguments:

  -h, --help            show this help message and exit

  -k KML, --kml         Provide KML Filename ( Optional )

  -p PORT, --port       Port for Web Server [ Default : 8080 ]

  -t TUNNEL, --tunnel   Specify Tunnel Mode [ Available : manual ]

##################

# Usage Examples #

##################

# Step 1 : In first terminal

$ python3 seeker.py -t manual

# Step 2 : In second terminal start a tunnel service such as ngrok

$ ./ngrok http 8080

###########

# Options #

###########

# Ouput KML File for Google Earth

$ python3 seeker.py -t manual -k <filename>

# Use Custom Port

$ python3 seeker.py -t manual -p 1337

$ ./ngrok http 1337











