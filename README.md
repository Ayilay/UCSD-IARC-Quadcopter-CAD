<img src="https://img.shields.io/badge/Project%20Status-Abandoned-red" />

# UCSD IARC 2018-2019 Quadcopter CAD
This repository contains the CAD files for the quadcopters designed by UCSD's 2018-2019 IEEE Quadcopter team for the [IARC Mission 8](http://www.aerialroboticscompetition.org/) competition.

<p float="left">
    <img src="/Renders and Pictures/Dimetric.PNG" height="200"/>
    <img src="/Renders and Pictures/Top.PNG"      height="200"/>
</p>

Please refer to the [Main Team repository](https://github.com/TsunamiTTT/UCSD-QuadCopter-2018-2019-) for references to the other components of the project, such as the PCB files and software.

## Current Status
Revision 1 is the most recent manufactured revision of the quadcopter frame. It was CNC'd from 1.5 mm flat carbon fiber.

## File Structure

### Renders and Pictures
Contains renders of the CAD of the quadcopter, and pictures of the assembled product

### REVx
Contains the CAD files for Revision x of the CAD. Usually Rev x is based on Rev (x - 1)

### REVx/Manufacturing Files
Contains the DXF and PDF files for the Carbon Fiber pieces to send to manufacturers for external fabrication

### REVx/STL Files
Contains STL renders of items to be 3D printed with on-campus 3D printer services

## TODO Modifications
The following modifications are corrections to be incorporated into Revision 2:
- [ ] Fix mounting hole distances for motors
- [ ] Add better mounting for base plate (along the center axis)
- [ ] Modify landing gear to accomodate the axel of the motor

## Credits
The entire frame was designed by Georges Troulis, with lots of help from Hongtao Zhang (Project Lead and Chief Engineer).

The frame was designed entirely by engineering students with minimal experience of designing aerodynamic structures, therefore items such as structural integrity and aerodynamics were not very carefully considered. This is however our best effort to keep the frame as robust and lightweight as possible with our minimal experience.
