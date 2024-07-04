# The-modified-IEEE-123-feeder-test-and-modified-8500-node-test
This repo contains two datasets, including the modified IEEE-123 feeder test and modified 8500-node test data.
Each of them has two tables, saving the feeder data and the node data.
## 1.	IEEE-123 feeders data
+ Index: feeder index of the original test data
+ Loads: positive for absorb power, negative for developed power
+ Config: 1 for power node and 2 for load node
+ Coord1: feeder *x*-coordinates in local ENU Cartesian coordinates 
+ Coord2: feeder *y*-coordinates in local ENU Cartesian coordinates
## 2.	IEEE-123 lines data 
+ Endnodes1_2: the feeders connected to the line
+ Weight: 1 for non switch line, 2 for automatic switch line and normally closed manual switch line, 3 for normally open manual switch line
+ FP1_12: line failure probability under each time, from 1h to 12h
+ TTR: line repair time
+ Imp: line importance indicator
## 3.	IEEE-8500 feeders data
+ Loads: positive for absorb power, negative for developed power
+ Config: 1 for power node and 2 for load node
+ X: feeder *x*-coordinates in local ENU Cartesian coordinates 
+ Y: feeder *y*-coordinates in local ENU Cartesian coordinates
## 4.	IEEE-8500 lines data
+ Endnodes1_2: the feeders connected to the line
+ Weight: 1 for non switch line, 2 for automatic switch line and normally closed manual switch line, 3 for normally open manual switch line
+ FP1_12: line failure probability under each time, from 1h to 12h
+ TTR: line repair time
+ Imp: line importance indicator
