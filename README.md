# WeedMan
An attempt at a robotic weed picker using Python.

The basic idea is to use a Raspberry Pi, mounted on a delta arm with wheels, to capture images and communicate them with my old PC through a local server.

Things to do:
-Build server
-Using OpenCV, analyze and detect unwanted plants.
-segment the unwanted plants, and convert movements to G-Code for the delta arm to move.
-build a nice dashboard to view successes.

Main part is to just build the server, and be able to train a neural network to segment unwanted plants.
