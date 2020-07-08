# **coppeliasim\_ros\_services**
update of the vrep\_plugin to be compatible with coppeliasim v4 and ros melodic


## **Description**

Creates ros service server for many services -listed below- to allow remote control of the simulation:
AddStatusbarMessage
AuxiliaryConsoleClose
AuxiliaryConsoleOpen
AuxiliaryConsolePrint
AuxiliaryConsoleShow
BreakForceSensor
ClearFloatSignal
ClearIntegerSignal
ClearStringSignal
CloseScene
CopyPasteObjects
CreateDummy
DisablePublisher
DisableSubscriber
DisplayDialog
EnablePublisher
EnableSubscriber
EndDialog
EraseFile
GetAndClearStringSignal
GetArrayParameter
GetBooleanParameter
GetCollisionHandle
GetDialogInput
GetDialogResult
GetDistanceHandle
GetFloatSignal
GetFloatingParameter
GetInfo
GetIntegerParameter
GetIntegerSignal
GetJointMatrix
GetJointState
GetLastErrors
GetModelProperty
GetObjectChild
GetObjectFloatParameter
GetObjectGroupData
GetObjectHandle
GetObjectIntParameter
GetObjectParent
GetObjectPose
GetObjectSelection
GetObjects
GetStringParameter
GetStringSignal
GetUIButtonProperty
GetUIEventButton
GetUIHandle
GetUISlider
GetVisionSensorDepthBuffer
GetVisionSensorImage
LoadModel
LoadScene
LoadUI
PauseSimulation
ReadCollision
ReadDistance
ReadForceSensor
ReadProximitySensor
ReadVisionSensor
RemoveModel
RemoveObject
RemoveUI
SetArrayParameter
SetBooleanParameter
SetFloatSignal
SetFloatingParameter
SetIntegerParameter
SetIntegerSignal
SetJointForce
SetJointPosition
SetJointState
SetJointTargetPosition
SetJointTargetVelocity
SetModelProperty
SetObjectFloatParameter
SetObjectIntParameter
SetObjectParent
SetObjectPose
SetObjectPosition
SetObjectQuaternion
SetObjectSelection
SetSphericalJointMatrix
SetStringSignal
SetUIButtonLabel
SetUIButtonProperty
SetUISlider
SetVisionSensorImage
StartSimulation
StopSimulation
Synchronous
SynchronousTrigger
TransferFile

### **Sample of Usage** 
Download this package in the _src_ folder of your ROS workspace
Compile the package
Copy the generated file "..devel/lib/libsimExtRosServices.so" to coppeliasim main folder 
Run ros master using Roscore
Start Coppeliasim 
List all available services 

#### **Dependencies** 
This package depends from the [vrep\_common](https://github.com/jocacace/vrep_common) package.

