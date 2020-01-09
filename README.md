# kephera_IV
Program in C to control the Kephera IV: it finds the closest wall and it finds out the area of the room where it is contained using a LIDAR.

Both folders are prepared to be opened within Webots (as the worlds are also prepared to test the controllers). However, you can find the controllers in :

- Area/Controllers/kephera4.c: which calculates the area of the room in which the robot is found when this room is rectangular or triangular.

- Brujula_Lidar/Controllers/kephera4.c: which finds the closest wall when the robot is turned on.

PD: We are using a Hokuyo LIDAR able to read up to 4 meters.
LIDAR DESCRIPTION: https://en.wikipedia.org/wiki/Lidar
