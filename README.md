## Vehicle Routing Problem (VRP)

![Alt text](https://github.com/atasbh/VRP_Ins/blob/main/In's%20VSP-1.png)

The Vehicle Routing Problem (VRP) is a well-known optimization problem in operations research that aims to find the optimal set of routes for a fleet of vehicles to visit a set of locations, subject to certain constraints. The problem arises in many real-world scenarios such as package delivery, garbage collection, school bus routing, and many more. The goal is to minimize the total distance or time traveled by the vehicles while satisfying constraints such as capacity, time windows, and vehicle availability.

This project pertains to the optimization of delivery routes for three In's Supermarket trucks in Rome. The objective is to identify the shortest path for the trucks to transport goods from the depot to the delivery destination and subsequently return to the depot. The OpenStreetMap API is utilized to obtain accurate distance measurements between the relevant locations, and the VRP algorithm, implemented through Google OR-Tools, is employed to determine the optimal route
