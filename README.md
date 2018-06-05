# nearair_server_node-red

NearAir Server (node-red)

## Required additional node
- node-red-contrib-web-worldmap
- node-red-node-sqlite
- node-red-contrib-slack

## How to setup

### sqlite DB Set up
1. Open "NearAir sqlite DB" node
2. Set the file path of sqlite db in the property "Database"  
node-red must be running on same environment as sqlite db file  
node-red must be able to access to sqlite db file
3. Push the button of node of "Create DB"

### twitter node set up
1. Set up "twitter" node

### slack notification set up
1. Set up "nearair notification" node (for slack)

### GPS MQTT device setup
1. Set up "GPS MQTT device" node
