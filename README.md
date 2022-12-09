# HoneyPot
A simple python honey pot

It takes an IP address, Port, and MOTD (message of the day) as inputs. then it opens a listener. when a device makes a connection to the IP and port, they are presented with the MOTD. At the same time, the listener appends "honey.mmh" with the connecting device's details to include the first 1024 bytes of data, then it closes the connection and starts listening again. The listener can be stopped at any by typing "CTRL + C"

<img width="677" alt="honeypot screenshot" src="https://user-images.githubusercontent.com/120150007/206618019-dc049a1b-49d7-41dd-99e5-55a61969da0c.png">
