# OrbitSimulation

Hobby project done to learn Python.
In all the three zip folder set parameters in excel files and then run main.py.

1) Orbit.zip: integration of multiple planets and bodies' orbits, to be chosen in main.py, using leapfrog method (longer time periods induce errors)
2) EarthOrbit.zip: integration of Earth's orbit with sliders to change parameters and plot of energies. Runge-Kutta 4th order method is called from a C++ compiled and optimized file to speed up and accomplish the integration (for long time periods and particular choices of the parameters errors are possible, resulting in wrong precession or open orbits). 
