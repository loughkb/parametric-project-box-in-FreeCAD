# parametric-project-box-in-FreeCAD

When you open the file, if not already visible, double click the "spreadsheet" in the model tree to open it.  Enter the dimensions you desire and the box, lid, and gasket will automatically recompute.   Then you can click on the box body in the model tree and go to the file menu and select export to export the box as an STL or STEP file for 3D printing.  

Repeat for the Lid body and optionally the Gasket body. 

The program doesn't protect you from entering bad values, it relies on your common sense to choose sane dimensions.  Nobody is going to use 10 mm screws in a 40 mm x 40 mm box. ha!

I would suggest setting the file as read only so you don't accidentally screw it up.  You can always do a save as and create a new file if you want to further modify the box before export.  i.e. adding holes or internal features before printing.  ALternatively you could export as a .step file and re-import into a new project before adding holes and features to your custom box.
