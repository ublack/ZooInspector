ZooInspector
============

An improved zookeeper inspector(direct connect, cache, sort nodes)

- direct connect the default (config/defaultConnectionSettings.cfg) on start
- the window title show the hosts(now connecting)
- add a map as cache(clean the map when refresh)
- node sorted by name in tree viewer
- Timestamp in more readable format in node metadata viewer


Build
- mvn clean package 

Run
- put the  generated jar in the home dir (e.g. zooInspector)
- put the dependencies in the lib dir
- double click the jar(keep the dir structure)


