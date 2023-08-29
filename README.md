# web-temps
Remote temperature monitoring and data collection arduino ds18b20 mysql jupyter-notebook
---
1) Arduino with wifi connection to a local network with internet access
2) Arduino reads temperatures from 4 (or N) ds18b20 temperature sensors
3) HTTP packet formed and sent to website url
4) Website url receives packet, parses, and writes to a mysql database
5) Website url for downloading temperature data
6) Import into jupyter notebook for graphical analysis
