# CreateFeatureSwing
Demonstrates how to contribute a Feature to PolyScope as well as how to store a Feature in the data model

Create Feature Swing is an example that shows how to contribute a feature to PolyScope as well as how to modify and remove it.
In the installation contribution, the user can define a feature and subsequently update and remove it. The created feature is stored in data model of the installation contribution. 
In the program node contribution, the user will be asked to create a feature from the installation contribution, if not done already. When the feature is created, the user can press a button to create a movement relative to the created feature. The movement is achieved by
inserting a pre-configured MoveL program node containing pre-defined Waypoint nodes. When the program node is executed, the robot will perform a square movement centered at the created feature.

Information:
* Available from:
  * URCap API version 1.9.0.
  * PolyScope version 3.12.0/5.6.0.
* Main API interfaces: FeatureContributionModel.
