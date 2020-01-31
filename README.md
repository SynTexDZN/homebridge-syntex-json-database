# Homebridge SynTex JSON Database
A plugin to store information in a JSON database.


# Installation
1. Install homebridge using: `sudo npm install -g homebridge`
2. Install this plugin using: `sudo npm install -g homebridge-syntex-json-database`
3. Update your configuration file. See snippet below.


# Example Config
```
"platforms": [
    {
        "platform": "SynTexJSONDatabase",
        "port": 1710,
        "cache_directory": "./SynTex/",
    }
]
```