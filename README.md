
# AllSwerve - a conceptual NEO Swerve Base with NavX Gyro Mapping </br>

**Sample Swerve code based off of the 364 Falcon Swerve base and 3512 SwerveBot for a Neo/NavX configuration (More configs to be added)** </br>
This code was designed with Swerve Drive Specialties MK3, MK4, and MK4i style modules in mind, but should be easily adaptable to other styles of modules.</br>

**Base Configuration**
----
This code assumes thst you are using MK4i Swerve modules with all NEO motors, CANcoders, and a NavX 9 axis IMU.
If this is your desired configuration, then you will simply need to set your motor IDs and the Absolute encoder offsets in Constants. A more in depth guide on configuration and setup can be found on the github page for the 364 BaseFalconSwerve.

**Controller Mappings**
----
This code is natively setup to use a xbox controller to control the swerve drive. </br>
* Left Stick: Translation Control (forwards and sideways movement)
* Right Stick: Rotation Control </br>
* Y button: Zero Gyro (useful if the gyro drifts mid match, just rotate the robot forwards, and press Y to rezero)
* Left Bumper: Switches To Robot Centric Control while held
