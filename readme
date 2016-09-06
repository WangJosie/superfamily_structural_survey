#1)dataset lists all superfamilies has one to one annotation of SCOP fold and CATH topologies
   #col1 superfamily assignment
   #col2 CATH topology
   #col3 SCOP fold 
   #delimit: Tab
   filename: 1907_repsentative_set


#2)structural representative processed from cdart315 includeing:
   #col1 superfamily assignment (from CDART v.315) 
   #col2 pdb id + chain id 
   #col3 representative footprint for corresponding superfamily->structure start position 
   #col4 representative footprint for corresponding superfamily->structural stop position
   #delimit:Tab
   filename: cdart315_structural_representative


#3) representative structures have both cdart domain annotation and cath annotations 
   #col1 pdbid +chain id
   #col2 superfamily assignment from cdd
   #col3 superfamily domain footprint ->structural start position
   #col4 superfamily domain footprint ->structural stop position
   #col5 CATH topology annotation
   #col6 CATH structure footprint, start postion +"_" + stop postion e.g. 8_153 suggests start amino acid is         8 and stop amino acid is 153
   #col7 the overlap between footprint detemined by CDD superfamily and CATH
         #if CATH footprint is not specified, we use the footprint from superfamily domain and caculate, the
         #overalp would equal to be the domain length determined by CDD superfamily, i.e. col4 -col3
   filename: cdart_cath_compare

#4) representative structures have both cdart domain annotation and scop fold annotations
   #col1 pdbid +chain id
   #col2 superfamily assignment from cdd
   #col3 superfamily domain footprint ->structural start position
   #col4 superfamily domain footprint ->structural stop position
   #col5 SCOP fold  annotation
   #col6 the overlap between CDD domain footprint with SCOP sequence footprint.
         #if SCOP footprint is not specified, we used the CDD domain footprint
   #col7 SCOP footprint if avaliable.
   filename: cdart_scop_compare

#5) intersection of cdart representative structures from "cdart315_structural_representativ" with representative at e-7 from nrpdb(verion 04/26/2016), those structures would present a sets of structues within similairty using blast e-7 as cutoff
   #col1: superfamily assignment
   #col2: pdb id + chain id
   #col3: representative footprint for corresponding superfamily->structure start position
   #col4: representative footprint for corresponding superfamily->structural stop position
   filename: nrpdb042416_e7_cdart
