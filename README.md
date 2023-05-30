# Install docker by following instructions at:
https://docs.docker.com/engine/install/ubuntu/

# Setup docker user groups
https://docs.docker.com/engine/install/linux-postinstall/

# Create and paste EASAS user Bearer token to datacollector.properties file

# Start docker service
docker compose up -d

# Note on BACnet
Additional UDP ports will need to be mapped if network uses non-default ports
