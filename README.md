Hacklab
===
Container with tools for hacking. At this moment contains Opendoor and Nikto.

Example usage:
```sh
$ docker run --name hacklab hacklab
$ docker exec hacklab nikto example.com
$ docker exec -i hacklab bash -c "cd /opt/opendoor/ && python3.6 opendoor.py --host example.com"
```