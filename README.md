# Eat Express 
## Traveling Salesman Problem

<img src="https://lh6.googleusercontent.com/8uKkxmRMOTsO9fjEJDOWupcgsSQP718gcXPs-81V3TUZAwpMweE_XNODG-YAlR5YZI4wkRHxxCkW_9gzpoJImrECgr8hWNBx_Tn47O0nzsHpboDOiA3lNybuo6BfKJUDRkEfcEiV" width="100%">
<br><br>
EatExpress is a food delivery system between the restaurants registered on the platform and the users of its application. When a user accesses the application, they choose the restaurant and dish they want, and it is delivered to the user location by a courier who uses his own means of transportation to get there (on foot, bicycle, motorcycle, car etc).

## Specification

In this project we looked for a system to generate the fastest routes, between the restaurants and the customers, for the couriers. It was considered initially that there was only one courier working for the platform. Later, was considered the addition of more couriers. At the later stage, were used couriers with faster vehicles for long distance routes, and larger ones for large orders.

## Constraints

Sometimes works on public roads can make certain areas inaccessible, making it impossible to access the addresses of some restaurants and users. The connectivity of the graph was evaluated in order to identify points of sale and delivery points with little accessibility.

Some real maps were used, taken from OpenStreetMaps (www.openstreetmap.org), with geographic coordinates of addresses and the express service support center.

## Src

All the classes and algorithms are inside the [`src`](src) folder. It also contains some generated city maps in the form of graphs with vertices and edges connecting them, some representing grid street structures, others representing real cities.

These graphs have the nodes' info represented by tuples with (id, x-coordinate, y-coordinate) and the edges' info like (node1, node2, distance).

# Plots

Plots about the gathered data were generated with some python scripts, `pandas` and `matplotlib` libraries.
These can be found inside the [`plots`](plots) folder.
The logs generated can be found inside the [`logs`](logs) folder.

# Report

The final project report can be found [here](report/CAL-T3G4.pdf).

## Authors

* Diana Freitas, [@dianaamfr](https://github.com/dianaamfr)
* Eduardo Brito, [@edurbrito](https://github.com/edurbrito)
* Pedro Ponte, [@pedrovponte](https://github.com/pedrovponte)