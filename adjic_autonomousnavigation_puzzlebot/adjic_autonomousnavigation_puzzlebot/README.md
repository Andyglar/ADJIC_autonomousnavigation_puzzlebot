# adjic_autonomousnavigation_puzzlebot

## Para instalar y correr este proyecto
1. Clona el repositorio dento de tu directorio ```catkin_ws/src/```
2. Instalar el stack de navegación de ROS ```sudo apt-get install ros-noetic-navigation```
3. Compilar usando ```catkin_make``` estando ubicando dentro de ```catkin_ws/``` (debería de compilar correctamente el paquete de ROS)
4. Ir al paquete usando ```roscd adjic_autonomousnavigation_puzzlebot``` y después ir a ```cd src/```
5. Modificar los permisos del archivo ```env_run``` para que tenga permisos de ejecución ```sudo chmod +x env_run```
6. Correr el launch file ```simulation2d.launch```
