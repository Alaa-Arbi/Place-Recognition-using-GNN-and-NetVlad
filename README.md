# Place-Recognition-using-GNN-and-NetVlad
Place recognition is the task of roughly localizing the place in which some sensor readings was taken in a map. The working principle of place recognition is explained in the diagram in the following figure. 

<p align="center">
<img src="Diagram place recognition.png" title="Diagram place recognition", width=600/>
</p>

In an offline step sensor readings are collected from multiple locations in the map, with different angles and perspectives, converted into a lower dimensional discriminative embedding space and stored in a database. During live runs, whenever a new sensor reading (called the query) is available, it is converted to its embedding using the same model. Using 1-NN method, its nearest neighbor is located from the database. If the nearest neighbor in the database corresponds to a sensor reading taken from a location that is within a certain radius (threshold) from the location of the query then the query was correctly matched and rough localization is successfully achieved.

This project is a team project that I conducted together with my partner Gerhard Arya Wardana in the scope of a practical course at the university. This repository contains the report that we submited. Due to confidentialty reasons, code is not uploaded.
