# node-red-contrib-onvif

A <a href="http://nodered.org" target="_blank">Node-RED</a> node that interacts with ip cameras using the ONVIF protocol.

## Install

Run the following command in the root directory of your Node-RED install

    npm install node-red-contrib-aguiar-onvif

## Usage

Input:
To capture the Snapshot you must enter the IP of the cam, the user of the Onvif protocol and the password of the protocol.


    ip Cam:                     msg.ip,
    Username Onvif:             msg.username,
    password Onvif:             msg.password,

OutPut:
ONVIF Snapshot returns msg.payload in the form of a base64 encoded image to use with a Node-RED Dashboard template.
 

 Snapshot: msg.payload,


