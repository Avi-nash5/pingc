# pingc
Cli application accepts a hostname or an IP address as its argument, then send ICMP "echo requests" in a loop to the target while receiving "echo reply" messages. Reports loss and RTT times for each sent request.

## About
Currently only supports IPv4.

User can specify ttl values.By default it is set to 64.

## Usage 
sudo ./ping "hostname"

To specify your own ttl value

sudo ./ping -t "(int)yourvalue" "hostname"

## Future additions
Support for IPv6
