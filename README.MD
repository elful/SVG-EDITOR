# SVG Editor

The SVG Editor allows the administrator to create, manage and distribute floor plans. Those are the equivalent of Google Maps for indoor localization.  
The file format is SVG. The editor allows the user to add active elements like:  
* LocaIR - Infra Red based bulbs used for indoor localization via an Wearable IR detector
* LocaBeacon - Bluetooh Smart Beacon that is used for indoor positioning  
This elements allow the mobile applications to identify the room and load the corresponding plans. The mobile application is designed to work mainly off-line.  

Plans contain information about room name, room number, a minimum of architectural elements: doors, windows, poles, and localization elements, like: GPS coordinates, building location, street name, street number etc.  

The application is written in JavaScript and is served directly from CouchDB. The SVG files are stored documents in the same CouchDB as attachments.  

# Deployment

`TODO`

# Usage

`TODO`

# Integration with other systems

`TODO`

# References

`TODO`
