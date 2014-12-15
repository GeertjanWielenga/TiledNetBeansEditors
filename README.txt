This NetBeans Maven project is a demo for the reusable NetBeans Platform module "tiled-editors" 
contained in a folder with the same name.

tiled-editors exposes 4 actions: tile horizontally, tile vertically, tile evenly and tile single.
They are used to arrange open editor windows as it is known from many imaging applications such 
as Photoshop.

The actions work on the org.esa.snap.netbeans.tile.Tileable interface either provided through 
the global action context or by a default implementation. The default implementation
arranges open editor windows and is based on 16x16=256 (generated) editor "modes".
For details, have a look at
- tiled-editors/src/main/resources/org/esa/snap/netbeans/tile/layer.xml
- tiled-editors/src/main/resources/org/esa/snap/netbeans/tile/modes/*.wsmode
- tiled-editors/src/main/java/org/esa/snap/netbeans/tile/Tileable.java
- tiled-editors/src/main/java/org/esa/snap/netbeans/tile/TileableImpl.java
- tiled-editors/src/main/java/org/esa/snap/netbeans/tile/TileAction.java

For more information on modes refer to http://wiki.netbeans.org/DevFaqWindowsMode.

The sources for the tiled-editors module  have been developed under GPL license within the frame of the ESA
Sentinel Toolboxes project, see https://sentinel.esa.int/web/sentinel/toolboxes.
The sources for the Sentinel Toolboxes can be found at https://github.com/orgs/senbox-org/dashboard


Have fun!

Norman Fomferra
Reinbek, Germany in December 2014
norman.fomferra@brockmann-consult.de
