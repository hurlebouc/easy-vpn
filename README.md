# openvpnconfig

To install the vpn configuration :

    git clone https://github.com/hurlebouc/openvpnconfig.git
    cp -r openvpnconfig/* /etc/openvpn/
    cd /etc/openvpn

Create all SSL stuffs

    ./create-ssl

Set iptables et IP forwarding rules

    ./set-iptables

Adapt remote file to give IP address of your server

    vim remote

Create a new user

    ./adduser dupont
Configuration of your new user is in clientconf directory.

Remove a user

    ./deluser dupont
