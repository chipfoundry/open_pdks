These decap cells were redesigned to cut back on its use of the LI layer because the corresponding SkyWater cell was covered in something like 70-80% LI, and using enough of the decap in any one design would cause an LI density error.

The fill cells were redesigned to add tap diffusion in the middle because otherwise the spacing of the nwells and the height of the cells prevents FOM fill, resulting in a different density error.

The new sky130_ef_sc_hd__decap_[2468]0_12 cells were designed to reduce poly.  They are identical to the sky130_ef_sc_hd__decap_12 cell except less poly (and a few licons).  The number 20, 40, etc represents approximately the percent of poly in the cell relative to the sky130_ef_sc_hd__decap_12 cell. 
