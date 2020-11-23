# Acrylic case for Quadrant

You can find the case files for the Quadrant here if you would like to go a little fancier than the stock design.
For the build you will need only the top_PCB of the keyboard!

## List of extra parts:
   - 10 or 11 pcs of laser cut acrylic plate
   - optionally 1 pc of laser cut metal/carbon fibre/FR-4 mounting plate (for more details, see the buid guide)
   - 12 pcs M2x8 screws for the main body of the case
   - 4 pcs M2x6 screws for the feet
   - 6 pcs M2x15 brass female-female standoffs for the main body of the case
   - 2 pcs M2x6 brass female-female standoffs for the feet
   - 4 pcs rubber feet

## Build guide
1. Download the Illustrator files.
2. Choose the type of sandwich case you would like to use:
   - There are two main variants of the case: using 3mm acrylic plates for all layers (expect *layer_D2*) or using a 1.5mm plate for mounting the switches (and the PCB in this *case*). For the later, an extra layer must be used to maintain a safety distance below the PCB. This layer is called *layer_X* and you have to laser cut it along with the rest. 
   - You can choose between *"layer_D1-plate-MX+Choc"* file or *"layer_D1-plate-ALPS"* file depending on the type of switches you have. **Caution**: Alps switches can be mounted safely only on 1.5mm plates, therefore you will have to use the *"layer_X"* file as well!
   
   tl;dr:
   For standard 3mm acrylic plates with MX or Choc style switches you will need the following files for cutting: *layer_A, layer_B, layer_C, layer_D1, layer_E, layer_F+H+I+J* (it contains the pieces of the feet as well)*, layer_G*. For *layer_D2* you need to use 2mm acrylic sheet!

3. Send the files to your choice of laser cutting service. Remember that some company uses specific line colors for specific cutting techniques, so check out their instructions about this. The standard color for edge cutting is black.
4. Order the cutting of 3mm and 2mm acrylic sheets. For the switch mounting plate you can use acrylic as well or any other type of material that exists in the form of 1.5mm or 3mm sheets. The *"layer_A"* will be the top of the case, you can use the same type of acrylic as the rest of the case or you can utilize clear acrylic to show off the components of the keyboard.
5. When you get the plates, solder the switches in the *top_PCB* using the mounting plate called *"layer_D1"*.
6. Screw the long plates of the *"layer_F+H+I+J"* file together with *"layer_G"* using M2x6 srcews and brass standoffs - it will be the bottom of the case.
7. Lay the plates on top of each other in the following order:
   *bottom of the case -> layer_F -> layer_E -> layer_D2 -> layer_X (if needed) -> layer_D1 ->layer_C -> layer_B -> layer_A*
8. Assemble them together using the M2x8 screws and M2x15 standoffs.
9. Apply the small rubber feet on the bottom of the case.

![eploded view](/Quadrant/images/acrylic_layered_case-R2_exploded.jpg)
