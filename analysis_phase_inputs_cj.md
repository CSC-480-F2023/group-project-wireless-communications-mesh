# Stakeholder Personas
1. Techie Tim (User) - Knows how the ESP32 chips work and wants them to run as fast and optimally as possible.
2. Average Aaron (User) - Doesn't know how the ESP32 chips work and just wants to be able to turn them on and have them connect.
3. EarthBox Elijah (Acquirer) - Requires that the controllers must send a specific size of data that corresponds with the common use case.
4. Coder Charles (Producer) - Specifies the use of dijkstra's algorithm and working in low-power mode of the ESPs.
5. Nervous Nick (Producer) - Specifies the ESP32 and working in C based languages.
6. Superior Sarah (Regulator) - Determines how many controllers need to be connected to the mesh network.
7. Extrordianry IEEE (Regulator) - Helps determine how wireless communications need to be used. Will require team to adhere to IEEE 802.15.1, a bluetooth standard.

# Relevant Requirements/Constraints
1. The system must use the ESP32-C6-DevKitC-1 (functional)
2. The system must connect multiple ESP32s in a mesh network (functional)
3. The system must be able to access any ESP at any time (functional)
4. The system must be able to send data from the mesh controllers to the hub controller (functional)
5. The system should be able to at least 32KB of data (non-functional)
6. The system should be able to add a mesh controller and restructure the mesh to be the most optimal configuration (non-functional)
