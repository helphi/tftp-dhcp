# tftp-dhcp
docker run -it \
-v /home/hefei/git/github.com/tftp-dhcp/tftp:/tftp \
-v /home/hefei/git/github.com/tftp-dhcp/dhcpd.conf:/etc/dhcpd.conf \
tftp-dhcp

dhcpd
in.tfptd -s -l -c /tftp
