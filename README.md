# Elegoo Neptune 3 to Switchwire Conversion 

This is a full conversion of the Elegoo Neptune 3 to a Voron Switchwire, forked from boubounokefalos's Ender 3 conversion with prior work by [Triano](https://github.com/walttriano/VoronUsers/tree/master/printer_mods/Triano/Ender_3Pro_Switchwire). Electronics mounting based on Fizzy's Tech's [EMS](https://www.printables.com/model/477791-ft-ems-v02-electronic-management-system)

This is an early stage repository and STL's have not been changed. CAD files are provided but some stock printed components (rear middle grill and front middle grill for different screen options) are missing due to issues during assembly and have not yet been readded. You should get these from the original STLs but other components can be exported from the CAD. Notable changes

- Modified the xz idlers on top beam to sandwich between the extrusions so drilling a new extrusion is not required

- Bottom cross member moved forward instead of just the y extrusion due to the Neptune 3's differences in mounting holes, adding 90 degree brackets is a good idea for rigidity.

- The motor extender on the y axis is required and extra heatset insert points have been added to compensate for the lack of mounting options on the N3s closed extrusions

- Electronics and PSU are mounted in the front with a printable bracket to secure the PSU and electronics (NOT UPDATED IN CAD YET)

- Key back mount modified to work with the for the N3s PSU mount holes.

- A regular 2020 extrusion for the gantry needs to be added
  
- option for XZ idlers on gantry added that use short M5 heatset inserts
  
- Deck Panels modified for Neptune 3, I have access to a larger printer so you may need to modify the CAD accordingly. Only left side fully modified but this can be used as a template. Bottom deck modified to add holes for ventilation of the N3 PSU.
  
- Enclosure panels extended to accomodate the height of the N3
  
- Experimental dragonburner carriage added (extra mounting points for V6 dragonburner with modified cowl only currently, V7 can be used but will not have heatsets for additional rigidity)

- Mirrored cable chain deck mount and added anchor to side of N3 extrusions.
  
- Extra holes for heatsets added on the Y extenders and bottom bar that the feet mount to to allow for screws to further secure the bottom bar to the frame since they can't be secured to the closed extrusions on the bottom as usual with t slot nuts (NOT UPDATED IN CAD YET)

Notes: BOM not updated and you will need a slection of longer M3, M4 and M5 SHCS in addition to those listed in the official BOM for the ender conversion. Plan to buy an assortment of 30-50 mm in 5mm increments for each of these. Longer M5s are essential for the top Z bar with the sandwiched idlers. Some not-voron standard heatset inserts are required in M4 and M5 sizes.
