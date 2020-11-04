# campus_simulation

This is a program to simulate sensor output of a campus. Currently, it creates temperature and power readings given some input. In this particular instance the input is power although there may be other inputs available in the future. After creating campus, building, room, corridor, and sensor objects, the state is saved in a json so that way the simulation can be iterated continuing the state of the previous iterations. Output "measurements" are then written to a sql database using the [Meerschaum]('https://github.com/bmeares/meerschaum') module. This data is then organized and displayed using Grafana for the [DaVA](www.dava.io) website. 
