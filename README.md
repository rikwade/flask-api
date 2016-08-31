# Flask API server

##### To clone project:
---
    $ git clone https://github.com/denewman/flask-api.git
##### To initialize the database:
---
    $ cd flask-api
    $ export FLASK_APP=sqlite-api.py
    $ flask initdb
    Initialized the database.
##### To run server:
---
    $ python sqlite-api.py
    
##### You can now make GET and POST requests to the following URLs:
___
- http://localhost:5002/subscription
    - **parameters:** subscriptionName (string), destinationGroupName (string), sensorName (string), subscriptionInterval (integer)
- http://localhost:5002/destinationGroup
    - **parameters:** destinationGroupName (string), destinationGroupAddress (string), destinationGroupPort (string), destinationGroupEncoding (string), destinationGroupProtocol (string)
- http://localhost:5002/sensor
    - **parameters:** sensorName (string)
    
