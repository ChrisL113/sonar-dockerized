# sonar-dockerized

dockerized version of sonarQube a tool for code scanning 

## To Run

just type "docker-compose up" in shell and you are ready to go !

### Note

Make sure you have ``` vm.max_map_count ``` with 262144 if not, to make it persistent, you can add this line:

```vm.max_map_count=262144```

in your ``` /etc/sysctl.conf ``` and run

```$ sudo sysctl -p```

to reload configuration with new value
