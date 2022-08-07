# Tor-Server-IP-List
The ``tor_relay_list.csv`` contains a list of all Tor Server Nodes, with Name, IP, Port, Flags and so on.

## List Format
name;hash;reboot_date;reboot_time;ip;or_port;fast;running;stable;v2dir;valid;exit;guard;hsdir;badexit;staledesc;authority
string;string;date;time;string;int;bool;bool;bool;bool;bool;bool;bool;bool;bool;bool;bool;bool;bool

## Data Source
The data comes from the file cached-microdesc-consensus

## Update Interval
The list is automatically updated every **30 minutes** when there are changes.
