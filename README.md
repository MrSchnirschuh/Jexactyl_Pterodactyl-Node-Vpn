# Jexactyl Pterodactyl-Node VPN

## Nginx Configuration to Connect Wing to Panel via VPN Network

This Nginx configuration is used to connect a Pterodactyl Wing to a Jexactyl or Pterodactyl Panel.

In my case, I am using Jexactyl as the panel and connecting the network via Netbird.
I have a VPS hosting the panel and one Wing for a Minecraft proxy.
The other nodes have different geolocations, and I don’t want to expose any ports on the routers.
Therefore, I am using this Nginx configuration.

### Steps:

1. Create a file in `/etc/nginx/sites-enabled/`.
2. Rename the file to match the name of your node, e.g., `node01.conf`.
3. Replace the placeholders with your port, domain, and IP address.
4. Test the configuration with `nginx -t`.
5. If there are no errors, apply the changes with `service nginx restart`.
6. Enjoy! :D
