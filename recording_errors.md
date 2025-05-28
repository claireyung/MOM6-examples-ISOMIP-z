# without drag params 
```
mpirun  -host localhost ../../../build/ocean_only/MOM6 -n 8
NOTE: MPP_DOMAINS_SET_STACK_SIZE: stack size set to    32768.
&MPP_IO_NML
 HEADER_BUFFER_VAL=16384      ,
 GLOBAL_FIELD_ON_ROOT_PE=T,
 IO_CLOCKS_ON=F,
 SHUFFLE=0          ,
 DEFLATE_LEVEL=-1         ,
 CF_COMPLIANCE=F,
 /
NOTE: MPP_IO_SET_STACK_SIZE: stack size set to     131072.
NOTE: MPP_DOMAINS_SET_STACK_SIZE: stack size set to   960000.
NOTE: ======== Model being driven by MOM_driver ========
NOTE: callTree: o Program MOM_main, MOM_driver.F90
&OCEAN_SOLO_NML
 DATE_INIT= 3*1          , 3*0          ,
 CALENDAR="julian          ",
 MONTHS=0          ,
 DAYS=20         ,
 HOURS=0          ,
 MINUTES=0          ,
 SECONDS=0          ,
 OCEAN_NTHREADS=1          ,
 USE_HYPER_THREAD=F,
 /
NOTE: open_param_file: MOM_input has been opened successfully.
NOTE: open_param_file: MOM_override has been opened successfully.
 MOM_in domain decomposition
whalo =    4, ehalo =    4, shalo =    4, nhalo =    4
  X-AXIS =  240
  Y-AXIS =   40
 MOM_inc domain decomposition
whalo =    2, ehalo =    2, shalo =    2, nhalo =    2
  X-AXIS =  120
  Y-AXIS =   20

WARNING: diag_manager_mod::diag_manager_init: DIAG_MANAGER_NML not found in input.nml.  Using defaults.


WARNING: diag_manager_mod::diag_manager_init: DIAG_MANAGER_NML not found in input.nml.  Using defaults.

NOTE: diag_manager_mod::diag_manager_init: prepend_date only supported when diag_manager_init is called with time_init present.
 MOM_in domain decomposition
whalo =    4, ehalo =    4, shalo =    4, nhalo =    4
  X-AXIS =  240
  Y-AXIS =   40
 MOM_in domain decomposition
whalo =    2, ehalo =    2, shalo =    2, nhalo =    2
  X-AXIS =  120
  Y-AXIS =   20
 MOM_in domain decomposition
whalo =    4, ehalo =    4, shalo =    4, nhalo =    4
  X-AXIS =  240
  Y-AXIS =   40
 MOM_in domain decomposition
whalo =    2, ehalo =    2, shalo =    2, nhalo =    2
  X-AXIS =  120
  Y-AXIS =   20

WARNING: MOM_file_parser : REGRIDDING_COORDINATE_MODE over-ridden.  Line: 'REGRIDDING_COORDINATE_MODE = "ZSTAR"' in file MOM_override.


WARNING: MOM_file_parser : REGRIDDING_COORDINATE_MODE over-ridden.  Line: 'REGRIDDING_COORDINATE_MODE = "ZSTAR"' in file MOM_override.

 MOM_in domain decomposition
whalo =    4, ehalo =    4, shalo =    4, nhalo =    4
  X-AXIS =  240
  Y-AXIS =   40
 MOM_in domain decomposition
whalo =    2, ehalo =    2, shalo =    2, nhalo =    2
  X-AXIS =  120
  Y-AXIS =   20
 MOM_Ice_Shelf_in domain decomposition
whalo =    4, ehalo =    4, shalo =    4, nhalo =    4
  X-AXIS =  240
  Y-AXIS =   40
 MOM_Ice_Shelf_inc domain decomposition
whalo =    2, ehalo =    2, shalo =    2, nhalo =    2
  X-AXIS =  120
  Y-AXIS =   20
 MOM_Ice_Shelf_in domain decomposition
whalo =    4, ehalo =    4, shalo =    4, nhalo =    4
  X-AXIS =  240
  Y-AXIS =   40
 MOM_Ice_Shelf_in domain decomposition
whalo =    2, ehalo =    2, shalo =    2, nhalo =    2
  X-AXIS =  120
  Y-AXIS =   20

WARNING: MOM_file_parser : SHELF_S_ROOT over-ridden.  Line: 'SHELF_S_ROOT = False' in file MOM_override.


WARNING: MOM_file_parser : SHELF_S_ROOT over-ridden.  Line: 'SHELF_S_ROOT = False' in file MOM_override.


WARNING: MOM_file_parser : COL_THICK_MELT_THRESHOLD over-ridden.  Line: 'COL_THICK_MELT_THRESHOLD = 1.0' in file MOM_override.


WARNING: MOM_file_parser : COL_THICK_MELT_THRESHOLD over-ridden.  Line: 'COL_THICK_MELT_THRESHOLD = 1.0' in file MOM_override.

NOTE: Initialize_ice_thickness_from_file: reading thickness

WARNING: MOM_file_parser : ICE_THICKNESS_FILE over-ridden.  Line: 'ICE_THICKNESS_FILE = "Ocean1_3D.nc"' in file MOM_override.


WARNING: MOM_file_parser : ICE_THICKNESS_FILE over-ridden.  Line: 'ICE_THICKNESS_FILE = "Ocean1_3D.nc"' in file MOM_override.


WARNING: Ice shelf thickness initialized without setting the shelf mask from variable h_mask, which does not exist in INPUT/Ocean1_3D.nc


WARNING: Ice shelf thickness initialized without setting the shelf mask from variable h_mask, which does not exist in INPUT/Ocean1_3D.nc

 MOM_Ice_Shelf_in domain decomposition
whalo =    4, ehalo =    4, shalo =    4, nhalo =    4
  X-AXIS =  240
  Y-AXIS =   40
 MOM_Ice_Shelf_in domain decomposition
whalo =    2, ehalo =    2, shalo =    2, nhalo =    2
  X-AXIS =  120
  Y-AXIS =   20
NOTE: ISOMIP_initialization.F90, ISOMIP_initialize_thickness: setting thickness

WARNING: MOM_file_parser : SURFACE_PRESSURE_FILE over-ridden.  Line: 'SURFACE_PRESSURE_FILE = "Ocean1_3D.nc"' in file MOM_override.


WARNING: MOM_file_parser : SURFACE_PRESSURE_FILE over-ridden.  Line: 'SURFACE_PRESSURE_FILE = "Ocean1_3D.nc"' in file MOM_override.


WARNING: KVML is a deprecated parameter. Use KV_ML_INVZ2 instead.


WARNING: KVML is a deprecated parameter. Use KV_ML_INVZ2 instead.

 MOM_in domain decomposition
whalo =    4, ehalo =    4, shalo =    4, nhalo =    4
  X-AXIS =  240
  Y-AXIS =   40
 MOM_in domain decomposition
whalo =    2, ehalo =    2, shalo =    2, nhalo =    2
  X-AXIS =  120
  Y-AXIS =   20
NOTE: MOM_ice_shelf.F90, initialize_ice_shelf: allocating fluxes.
NOTE: MOM_ice_shelf.F90, initialize_ice_shelf: allocating forces.

WARNING: Previous msg:DT_FORCING = 300.0              !   [s] default = 0.0


WARNING: Previous msg:DT_FORCING = 300.0              !   [s] default = 0.0


WARNING: New message :DT_FORCING = 300.0              !   [s] default = 300.0


WARNING: Encountered inconsistent documentation line for parameter DT_FORCING!


WARNING: New message :DT_FORCING = 300.0              !   [s] default = 300.0


WARNING: Encountered inconsistent documentation line for parameter DT_FORCING!

NOTE: Segment run length determined from ocean_solo_nml.

WARNING: Unused line in MOM_input : INTERPOLATION_SCHEME = "P1M_H4"


WARNING: Unused line in MOM_input : REGRIDDING_ANSWER_DATE = 20181231


WARNING: Unused line in MOM_input : BOUNDARY_EXTRAPOLATION = True


WARNING: Unused line in MOM_override : #override ISOLATE_MASS_WEIGHT_PGF = True


WARNING: Unused line in MOM_input : INTERPOLATION_SCHEME = "P1M_H4"


WARNING: Unused line in MOM_input : REGRIDDING_ANSWER_DATE = 20181231


WARNING: Unused line in MOM_input : BOUNDARY_EXTRAPOLATION = True


WARNING: Unused line in MOM_override : #override ISOLATE_MASS_WEIGHT_PGF = True


WARNING: MPP_OPEN: File ./CPU_stats opened WRONLY already exists!


WARNING: MPP_OPEN: File ./CPU_stats opened WRONLY already exists!

NOTE: MOM_surface_forcing: buoyancy forcing has been set to omitted.
 MOM_in domain decomposition
whalo =    4, ehalo =    4, shalo =    4, nhalo =    4
  X-AXIS =  240
  Y-AXIS =   40
 MOM_in domain decomposition
whalo =    2, ehalo =    2, shalo =    2, nhalo =    2
  X-AXIS =  120
  Y-AXIS =   20
NOTE: MPP_IO_SET_STACK_SIZE: stack size set to     240000.
NOTE: MPP_IO_SET_STACK_SIZE: stack size set to     241000.
NOTE: MPP_IO_SET_STACK_SIZE: stack size set to     246000.
NOTE: MPP_IO_SET_STACK_SIZE: stack size set to     249600.

WARNING: MPP_OPEN: File ./ocean.stats opened WRONLY already exists!


WARNING: MPP_OPEN: File ./ocean.stats opened WRONLY already exists!

MOM Day       0.000      0: En 0.000000E+00, MaxCFL  0.00000, Mass 1.335202226302E+16, Salt  34.19123986838, Temp  -1.90000000000
    Total Energy: 0000000000000000  0.0000000000000000E+00
    Total Mass:   1.3352022263022774E+16, Change:   0.0000000000000000E+00 Error:  0.00000E+00 ( 0.0E+00)
    Total Salt:   4.5652219592295469E+14, Change:   0.0000000000000000E+00 Error:  0.00000E+00 ( 0.0E+00)
    Total Heat:  -9.9572706026492297E+19, Change:   0.0000000000000000E+00 Error:  0.00000E+00 (-0.0E+00)
MOM Day       0.125     36: En 8.749402E-10, MaxCFL  0.00057, Mass 1.335202520279E+16, Salt  34.19123234036, Temp  -1.90001873621
    Total Energy: 41664835E59AB021  1.1682223175132813E+07
    Total Mass:   1.3352025202788980E+16, Change:   2.9397662059537625E+09 Error:  5.67730E-02 ( 4.3E-18)
    Total Salt:   4.5652219592295456E+14, Change:  -1.0845878982545230E-01 Error: -1.08459E-01 (-2.4E-16)
    Total Heat:  -9.9573709852812935E+19, Change:  -1.0038263206264276E+15 Error: -1.72757E+04 ( 1.7E-16)
MOM Day       0.250     72: En 3.727380E-09, MaxCFL  0.00083, Mass 1.335202809449E+16, Salt  34.19122493543, Temp  -1.90003716682
    Total Energy: 4187BB349C0A6F96  4.9768083505095646E+07
    Total Mass:   1.3352028094490128E+16, Change:   2.8917011483749413E+09 Error:  5.41664E-03 ( 4.1E-19)
    Total Salt:   4.5652219592295456E+14, Change:   4.3309803008982446E-03 Error:  4.33098E-03 ( 9.5E-18)
    Total Heat:  -9.9574697305651331E+19, Change:  -9.8745283840829812E+14 Error:  1.24499E+04 (-1.3E-16)

WARNING: diag_util_mod::opening_file: module/field_name (ocean_model/dudt_dia) NOT registered


WARNING: diag_util_mod::opening_file: module/field_name (ocean_model/dvdt_dia) NOT registered


WARNING: diag_util_mod::opening_file: module/field_name (ocean_model/dudt_dia) NOT registered


WARNING: diag_util_mod::opening_file: module/field_name (ocean_model/dvdt_dia) NOT registered


WARNING: diag_util_mod::opening_file: module/field_name (ocean_model/tr1) NOT registered


WARNING: diag_util_mod::opening_file: module/field_name (ocean_model/tr1) NOT registered

MOM Day       0.375    108: En 8.080802E-09, MaxCFL  0.00132, Mass 1.335203094267E+16, Salt  34.19121764195, Temp  -1.90005532072
    Total Energy: 4199B965236FB48B  1.0789511285908715E+08
    Total Mass:   1.3352030942672976E+16, Change:   2.8481828495255575E+09 Error: -2.33129E-02 (-1.7E-18)
    Total Salt:   4.5652219592295456E+14, Change:   8.6875915527011489E-04 Error:  8.68759E-04 ( 1.9E-18)
    Total Heat:  -9.9575669932501647E+19, Change:  -9.7262685030536862E+14 Error:  1.27899E+04 (-1.3E-16)
MOM Day       0.500    144: En 1.280117E-08, MaxCFL  0.00204, Mass 1.335203375046E+16, Salt  34.19121045191, Temp  -1.90007321772
    Total Energy: 41A4601D66127398  1.7092165103603816E+08
    Total Mass:   1.3352033750459158E+16, Change:   2.8077861796641974E+09 Error:  1.53286E-02 ( 1.1E-18)
    Total Salt:   4.5652219592295456E+14, Change:   6.4117279052710663E-03 Error:  6.41173E-03 ( 1.4E-17)
    Total Heat:  -9.9576628795656389E+19, Change:  -9.5886315473990875E+14 Error:  1.22960E+04 (-1.2E-16)
MOM Day       0.625    180: En 1.732415E-08, MaxCFL  0.00340, Mass 1.335203652027E+16, Salt  34.19120335913, Temp  -1.90009087319
    Total Energy: 41AB931A07850048  2.3131264375976777E+08
    Total Mass:   1.3352036520266262E+16, Change:   2.7698071053387060E+09 Error:  1.11445E-03 ( 8.3E-20)
    Total Salt:   4.5652219592295456E+14, Change:  -1.5123176574909092E-04 Error: -1.51232E-04 (-3.3E-19)
    Total Heat:  -9.9577574717768122E+19, Change:  -9.4592211173321138E+14 Error:  1.30670E+04 (-1.3E-16)
MOM Day       0.750    216: En 2.242623E-08, MaxCFL  0.00588, Mass 1.335203925402E+16, Salt  34.19119635867, Temp  -1.90010829936
    Total Energy: 41B1D90763CD2E52  2.9943587580148804E+08
    Total Mass:   1.3352039254022470E+16, Change:   2.7337562078905501E+09 Error: -1.38286E-02 (-1.0E-18)
    Total Salt:   4.5652219592295456E+14, Change:   2.0500106811504448E-03 Error:  2.05001E-03 ( 4.5E-18)
    Total Heat:  -9.9578508354885370E+19, Change:  -9.3363711724658600E+14 Error:  1.31492E+04 (-1.3E-16)
MOM Day       0.875    252: En 2.886730E-08, MaxCFL  0.00741, Mass 1.335204195326E+16, Salt  34.19118944661, Temp  -1.90012550596
    Total Energy: 41B6F94EF4900A7C  3.8543742856265998E+08
    Total Mass:   1.3352041953258236E+16, Change:   2.6992357660570335E+09 Error: -1.50234E-02 (-1.1E-18)
    Total Salt:   4.5652219592295456E+14, Change:   2.8020286560043583E-03 Error:  2.80203E-03 ( 6.1E-18)
    Total Heat:  -9.9579430227636224E+19, Change:  -9.2187275085441962E+14 Error:  1.24206E+04 (-1.2E-16)
MOM Day       1.000    288: En 3.646093E-08, MaxCFL  0.00803, Mass 1.335204461936E+16, Salt  34.19118261941, Temp  -1.90014250175
    Total Energy: 41BD0467889C63CC  4.8682791261089778E+08
    Total Mass:   1.3352044619355346E+16, Change:   2.6660971087788892E+09 Error:  2.36189E-03 ( 1.8E-19)
    Total Salt:   4.5652219592295456E+14, Change:   3.2168045043931598E-03 Error:  3.21680E-03 ( 7.0E-18)
    Total Heat:  -9.9580340806124732E+19, Change:  -9.1057848852426775E+14 Error:  1.35576E+04 (-1.4E-16)
MOM Day       1.125    324: En 3.983203E-08, MaxCFL  0.00635, Mass 1.335204725365E+16, Salt  34.19117587367, Temp  -1.90015929521
    Total Energy: 41BFB338AA69507F  5.3183914641138452E+08
    Total Mass:   1.3352047253646246E+16, Change:   2.6342909018466630E+09 Error:  1.16478E-02 ( 8.7E-19)
    Total Salt:   4.5652219592295456E+14, Change:   2.5461597442612777E-03 Error:  2.54616E-03 ( 5.6E-18)
    Total Heat:  -9.9581240543786484E+19, Change:  -8.9973766174159850E+14 Error:  1.36215E+04 (-1.4E-16)
MOM Day       1.250    360: En 4.057262E-08, MaxCFL  0.00567, Mass 1.335204985727E+16, Salt  34.19116920647, Temp  -1.90017589353
    Total Energy: 41C0250DC6027C97  5.4172762801942718E+08
    Total Mass:   1.3352049857265894E+16, Change:   2.6036196486093173E+09 Error:  1.22479E-03 ( 9.2E-20)
    Total Salt:   4.5652219592295462E+14, Change:   4.4850025176988214E-03 Error:  4.48500E-03 ( 9.8E-18)
    Total Heat:  -9.9582129826836595E+19, Change:  -8.8928305011786925E+14 Error:  1.28905E+04 (-1.3E-16)
MOM Day       1.375    396: En 4.367434E-08, MaxCFL  0.00649, Mass 1.335205243127E+16, Salt  34.19116261510, Temp  -1.90019230343
    Total Energy: 41C1610569453AD3  5.8314209854085767E+08
    Total Mass:   1.3352052431269918E+16, Change:   2.5740040237700362E+09 Error: -1.31585E-02 (-9.9E-19)
    Total Salt:   4.5652219592295462E+14, Change:   3.4559955596909857E-03 Error:  3.45600E-03 ( 7.6E-18)
    Total Heat:  -9.9583009014525002E+19, Change:  -8.7918768840464025E+14 Error:  1.30305E+04 (-1.3E-16)
MOM Day       1.500    432: En 5.125687E-08, MaxCFL  0.00723, Mass 1.335205497654E+16, Salt  34.19115609733, Temp  -1.90020853048
    Total Energy: 41C465707A641720  6.8438450078195572E+08
    Total Mass:   1.3352054976536960E+16, Change:   2.5452670384350605E+09 Error: -1.86462E-02 (-1.4E-18)
    Total Salt:   4.5652219592295462E+14, Change:   2.3398132324205091E-03 Error:  2.33981E-03 ( 5.1E-18)
    Total Heat:  -9.9583878405838406E+19, Change:  -8.6939131340076750E+14 Error:  1.35318E+04 (-1.4E-16)
MOM Day       1.625    468: En 6.062391E-08, MaxCFL  0.00791, Mass 1.335205749391E+16, Salt  34.19114965099, Temp  -1.90022458004
    Total Energy: 41C81FA4C4E31082  8.0945396177394128E+08
    Total Mass:   1.3352057493909744E+16, Change:   2.5173727879809914E+09 Error: -2.36244E-02 (-1.8E-18)
    Total Salt:   4.5652219592295462E+14, Change:   4.3319263458238538E-03 Error:  4.33193E-03 ( 9.5E-18)
    Total Heat:  -9.9584738287590425E+19, Change:  -8.5988175202432050E+14 Error:  1.37463E+04 (-1.4E-16)
MOM Day       1.750    504: En 7.014094E-08, MaxCFL  0.00846, Mass 1.335205998419E+16, Salt  34.19114327402, Temp  -1.90024045722
    Total Energy: 41CBE9207040DD7C  9.3652604850675917E+08
    Total Mass:   1.3352059984194912E+16, Change:   2.4902851643536072E+09 Error: -1.27869E-02 (-9.6E-19)
    Total Salt:   4.5652219592295462E+14, Change:  -4.8976898194743157E-05 Error: -4.89769E-05 (-1.1E-19)
    Total Heat:  -9.9585588934342869E+19, Change:  -8.5064675244610550E+14 Error:  1.25031E+04 (-1.3E-16)
MOM Day       1.875    540: En 8.016677E-08, MaxCFL  0.00871, Mass 1.335206244816E+16, Salt  34.19113696446, Temp  -1.90025616689
    Total Energy: 41CFE670D1A7E159  1.0703917153115646E+09
    Total Mass:   1.3352062448155038E+16, Change:   2.4639601266250677E+09 Error: -1.28554E-04 (-9.6E-21)
    Total Salt:   4.5652219592295462E+14, Change:   2.6844539642320200E-03 Error:  2.68445E-03 ( 5.9E-18)
    Total Heat:  -9.9586430605705544E+19, Change:  -8.4167136266511362E+14 Error:  1.39347E+04 (-1.4E-16)
MOM Day       2.000    576: En 9.088878E-08, MaxCFL  0.00944, Mass 1.335206488653E+16, Salt  34.19113072044, Temp  -1.90027171371
    Total Energy: 41D215563B3F585F  1.2135528769897687E+09
    Total Mass:   1.3352064886525824E+16, Change:   2.4383707894946756E+09 Error: -2.24632E-02 (-1.7E-18)
    Total Salt:   4.5652219592295462E+14, Change:   1.0083198547349364E-03 Error:  1.00832E-03 ( 2.2E-18)
    Total Heat:  -9.9587263552157319E+19, Change:  -8.3294645178026650E+14 Error:  1.33619E+04 (-1.3E-16)
MOM Day       2.125    612: En 1.014629E-07, MaxCFL  0.01013, Mass 1.335206730002E+16, Salt  34.19112454012, Temp  -1.90028710219
    Total Energy: 41D42FEC1F1DA01D  1.3547398364628975E+09
    Total Mass:   1.3352067300017784E+16, Change:   2.4134919595644250E+09 Error: -5.53746E-04 (-4.1E-20)
    Total Salt:   4.5652219592295462E+14, Change:   6.5694599151597255E-03 Error:  6.56946E-03 ( 1.4E-17)
    Total Heat:  -9.9588088015611068E+19, Change:  -8.2446345375178988E+14 Error:  1.32785E+04 (-1.3E-16)
MOM Day       2.250    648: En 1.105221E-07, MaxCFL  0.01034, Mass 1.335206968930E+16, Salt  34.19111842181, Temp  -1.90030233657
    Total Energy: 41D5FD582D3AFE02  1.4756988689217534E+09
    Total Mass:   1.3352069689295816E+16, Change:   2.3892780305923076E+09 Error:  2.05776E-03 ( 1.5E-19)
    Total Salt:   4.5652219592295462E+14, Change:   3.9318599700914215E-03 Error:  3.93186E-03 ( 8.6E-18)
    Total Heat:  -9.9588904222462575E+19, Change:  -8.1620685149593812E+14 Error:  1.29905E+04 (-1.3E-16)
MOM Day       2.375    684: En 1.182509E-07, MaxCFL  0.01055, Mass 1.335207205498E+16, Salt  34.19111236393, Temp  -1.90031742076
    Total Energy: 41D78700C5623951  1.5788941015347483E+09
    Total Mass:   1.3352072054976112E+16, Change:   2.3656802965846095E+09 Error: -1.07741E-03 (-8.1E-20)
    Total Salt:   4.5652219592295462E+14, Change:   1.5305385589585870E-03 Error:  1.53054E-03 ( 3.4E-18)
    Total Heat:  -9.9589712382526915E+19, Change:  -8.0816006433757200E+14 Error:  1.25782E+04 (-1.3E-16)
MOM Day       2.500    720: En 1.256588E-07, MaxCFL  0.01077, Mass 1.335207439766E+16, Salt  34.19110636495, Temp  -1.90033235855
    Total Energy: 41D900525366DB6F  1.6778059016071432E+09
    Total Mass:   1.3352074397655948E+16, Change:   2.3426798369808059E+09 Error: -1.56711E-02 (-1.2E-18)
    Total Salt:   4.5652219592295462E+14, Change:   1.9678115844712946E-03 Error:  1.96781E-03 ( 4.3E-18)
    Total Heat:  -9.9590512699201831E+19, Change:  -8.0031667492901450E+14 Error:  1.31689E+04 (-1.3E-16)
MOM Day       2.625    756: En 1.331995E-07, MaxCFL  0.01093, Mass 1.335207671794E+16, Salt  34.19110042332, Temp  -1.90034715380
    Total Energy: 41DA8066280F98A3  1.7784895042436912E+09
    Total Mass:   1.3352076717940906E+16, Change:   2.3202849563257775E+09 Error:  2.08844E-02 ( 1.6E-18)
    Total Salt:   4.5652219592295462E+14, Change:   6.0833740234236095E-04 Error:  6.08337E-04 ( 1.3E-18)
    Total Heat:  -9.9591305378755068E+19, Change:  -7.9267955322560125E+14 Error:  1.29153E+04 (-1.3E-16)
MOM Day       2.750    792: En 1.412193E-07, MaxCFL  0.01101, Mass 1.335207901640E+16, Salt  34.19109453759, Temp  -1.90036181010
    Total Energy: 41DC18E1C524B50F  1.8855708365735509E+09
    Total Mass:   1.3352079016397014E+16, Change:   2.2984561098152833E+09 Error:  8.15076E-03 ( 6.1E-19)
    Total Salt:   4.5652219592295462E+14, Change:   6.4378585815417508E-03 Error:  6.43786E-03 ( 1.4E-17)
    Total Heat:  -9.9592090613980594E+19, Change:  -7.8523522554047188E+14 Error:  1.35515E+04 (-1.4E-16)
MOM Day       2.875    828: En 1.499021E-07, MaxCFL  0.01111, Mass 1.335208129356E+16, Salt  34.19108870640, Temp  -1.90037633082
    Total Energy: 41DDD322519E0900  2.0015045824692993E+09
    Total Mass:   1.3352081293555034E+16, Change:   2.2771580195304942E+09 Error: -2.26864E-03 (-1.7E-19)
    Total Salt:   4.5652219592295462E+14, Change:   3.7709140777576673E-03 Error:  3.77091E-03 ( 8.3E-18)
    Total Heat:  -9.9592868585651421E+19, Change:  -7.7797167082443112E+14 Error:  1.29937E+04 (-1.3E-16)
MOM Day       3.000    864: En 1.589619E-07, MaxCFL  0.01118, Mass 1.335208354992E+16, Salt  34.19108292844, Temp  -1.90039071921
    Total Energy: 41DFA096AEDF4CFE  2.1224721234890742E+09
    Total Mass:   1.3352083549924242E+16, Change:   2.2563692083382316E+09 Error:  1.52268E-03 ( 1.1E-19)
    Total Salt:   4.5652219592295462E+14, Change:  -9.7507286071889254E-04 Error: -9.75073E-04 (-2.1E-18)
    Total Heat:  -9.9593639467226431E+19, Change:  -7.7088157500889262E+14 Error:  1.30827E+04 (-1.3E-16)
MOM Day       3.125    900: En 1.503557E-07, MaxCFL  0.00954, Mass 1.335208578597E+16, Salt  34.19107720252, Temp  -1.90040497826
    Total Energy: 41DDEA3E752F79C6  2.0075627087418075E+09
    Total Mass:   1.3352085785974432E+16, Change:   2.2360501848055844E+09 Error:  1.48060E-02 ( 1.1E-18)
    Total Salt:   4.5652219592295462E+14, Change:   2.6416759490955652E-03 Error:  2.64168E-03 ( 5.8E-18)
    Total Heat:  -9.9594403418710311E+19, Change:  -7.6395148387169462E+14 Error:  1.24822E+04 (-1.3E-16)
MOM Day       3.250    936: En 1.506748E-07, MaxCFL  0.00975, Mass 1.335208800213E+16, Salt  34.19107152755, Temp  -1.90041911065
    Total Energy: 41DDFA7F321F12B7  2.0118233044855173E+09
    Total Mass:   1.3352088002130032E+16, Change:   2.2161556004559817E+09 Error: -9.04820E-03 (-6.8E-19)
    Total Salt:   4.5652219592295462E+14, Change:   5.0270061492908762E-03 Error:  5.02701E-03 ( 1.1E-17)
    Total Heat:  -9.9595160584690287E+19, Change:  -7.5716597998320988E+14 Error:  1.30743E+04 (-1.3E-16)
MOM Day       3.375    972: En 1.554619E-07, MaxCFL  0.00994, Mass 1.335209019880E+16, Salt  34.19106590248, Temp  -1.90043311898
    Total Energy: 41DEEE53C0C0209F  2.0757419550019910E+09
    Total Mass:   1.3352090198799242E+16, Change:   2.1966692129930873E+09 Error:  8.39685E-03 ( 6.3E-19)
    Total Salt:   4.5652219592295462E+14, Change:  -1.2731170654405499E-04 Error: -1.27312E-04 (-2.8E-19)
    Total Heat:  -9.9595911104217137E+19, Change:  -7.5051952684038975E+14 Error:  1.24135E+04 (-1.2E-16)
MOM Day       3.500   1008: En 1.609747E-07, MaxCFL  0.01010, Mass 1.335209237635E+16, Salt  34.19106032636, Temp  -1.90044700561
    Total Energy: 41E0038F2C291A2E  2.1493497292844458E+09
    Total Mass:   1.3352092376350628E+16, Change:   2.1775513880248742E+09 Error:  1.23230E-02 ( 9.2E-19)
    Total Salt:   4.5652219592295462E+14, Change:   1.1714820861804930E-03 Error:  1.17148E-03 ( 2.6E-18)
    Total Heat:  -9.9596655102830084E+19, Change:  -7.4399861295565500E+14 Error:  1.36483E+04 (-1.4E-16)
MOM Day       3.625   1044: En 1.673393E-07, MaxCFL  0.01022, Mass 1.335209453518E+16, Salt  34.19105479820, Temp  -1.90046077301
    Total Energy: 41E0A5A5C8725882  2.2343306915733042E+09
    Total Mass:   1.3352094535175852E+16, Change:   2.1588252230684261E+09 Error: -2.50353E-02 (-1.9E-18)
    Total Salt:   4.5652219592295462E+14, Change:   1.8898162841785764E-03 Error:  1.88982E-03 ( 4.1E-18)
    Total Heat:  -9.9597392713972875E+19, Change:  -7.3761114278676212E+14 Error:  1.35460E+04 (-1.4E-16)
MOM Day       3.750   1080: En 1.627789E-07, MaxCFL  0.00805, Mass 1.335209667567E+16, Salt  34.19104931698, Temp  -1.90047442372
    Total Energy: 41E03181ABF1E9D5  2.1734393275597939E+09
    Total Mass:   1.3352096675672570E+16, Change:   2.1404967173658655E+09 Error:  1.54969E-03 ( 1.2E-19)
    Total Salt:   4.5652219592295462E+14, Change:   5.2885150909412976E-03 Error:  5.28852E-03 ( 1.2E-17)
    Total Heat:  -9.9598124073150857E+19, Change:  -7.3135917799102950E+14 Error:  1.17672E+04 (-1.2E-16)
MOM Day       3.875   1116: En 1.546847E-07, MaxCFL  0.00594, Mass 1.335209879816E+16, Salt  34.19104388188, Temp  -1.90048795975
    Total Energy: 41DEC6BE43185F89  2.0653652603808310E+09
    Total Mass:   1.3352098798157070E+16, Change:   2.1224845010390265E+09 Error: -7.36388E-03 (-5.5E-19)
    Total Salt:   4.5652219592295462E+14, Change:   9.0955162048251832E-04 Error:  9.09552E-04 ( 2.0E-18)
    Total Heat:  -9.9598849288122827E+19, Change:  -7.2521497195803950E+14 Error:  1.25043E+04 (-1.3E-16)
MOM Day       4.000   1152: En 1.515382E-07, MaxCFL  0.00489, Mass 1.335210090296E+16, Salt  34.19103849206, Temp  -1.90050138321
    Total Energy: 41DE267B8AECA575  2.0233538996975987E+09
    Total Mass:   1.3352100902961348E+16, Change:   2.1048042771500945E+09 Error: -1.78497E-02 (-1.3E-18)
    Total Salt:   4.5652219592295462E+14, Change:   8.9811134338292306E-04 Error:  8.98111E-04 ( 2.0E-18)
    Total Heat:  -9.9599568471997481E+19, Change:  -7.1918387466127625E+14 Error:  1.29515E+04 (-1.3E-16)
MOM Day       4.125   1188: En 1.546439E-07, MaxCFL  0.00648, Mass 1.335210299045E+16, Salt  34.19103314658, Temp  -1.90051469641
    Total Energy: 41DEC4AAAFA57D87  2.0648209265857866E+09
    Total Mass:   1.3352102990447262E+16, Change:   2.0874859159954045E+09 Error: -3.15259E-03 (-2.4E-19)
    Total Salt:   4.5652219592295462E+14, Change:   2.9016857147208127E-03 Error:  2.90169E-03 ( 6.4E-18)
    Total Heat:  -9.9600281748065960E+19, Change:  -7.1327606848426538E+14 Error:  1.18130E+04 (-1.2E-16)

WARNING: btstep: eta has dropped below bathyT:  -2.9719887537883039E+02 vs.  -2.9718414221305966E+02 at   4.8500E+02  1.5000E+01     83      8


WARNING: btstep: eta has dropped below bathyT:  -2.9719887537883039E+02 vs.  -2.9718414221305966E+02 at   4.8500E+02  1.5000E+01     83      8


WARNING: btstep: eta has dropped below bathyT:  -2.9722386094511540E+02 vs.  -2.9718414221305966E+02 at   4.8500E+02  1.5000E+01     83      8


WARNING: btstep: eta has dropped below bathyT:  -2.9722386094511540E+02 vs.  -2.9718414221305966E+02 at   4.8500E+02  1.5000E+01     83      8


WARNING: btstep: eta has dropped below bathyT:  -2.9731695127125164E+02 vs.  -2.9718414221305966E+02 at   4.8500E+02  1.5000E+01     83      8


WARNING: btstep: eta has dropped below bathyT:  -2.9731695127125164E+02 vs.  -2.9718414221305966E+02 at   4.8500E+02  1.5000E+01     83      8


WARNING: btstep: eta has dropped below bathyT:  -2.9733641329710144E+02 vs.  -2.9718414221305966E+02 at   4.8500E+02  1.5000E+01     83      8


WARNING: btstep: eta has dropped below bathyT:  -2.9733641329710144E+02 vs.  -2.9718414221305966E+02 at   4.8500E+02  1.5000E+01     83      8


WARNING: btstep: eta has dropped below bathyT:  -2.9778357572997299E+02 vs.  -2.9718414221305966E+02 at   4.8500E+02  1.5000E+01     83      8


WARNING: btstep: eta has dropped below bathyT:  -2.9778357572997299E+02 vs.  -2.9718414221305966E+02 at   4.8500E+02  1.5000E+01     83      8


WARNING: btstep: eta has dropped below bathyT:  -2.9780928683201466E+02 vs.  -2.9718414221305966E+02 at   4.8500E+02  1.5000E+01     83      8


WARNING: btstep: eta has dropped below bathyT:  -2.9780928683201466E+02 vs.  -2.9718414221305966E+02 at   4.8500E+02  1.5000E+01     83      8


WARNING: btstep: eta has dropped below bathyT:  -2.9770773564386820E+02 vs.  -2.9718414221305966E+02 at   4.8500E+02  1.5000E+01     83      8


WARNING: btstep: eta has dropped below bathyT:  -2.9770773564386820E+02 vs.  -2.9718414221305966E+02 at   4.8500E+02  1.5000E+01     83      8


WARNING: btstep: eta has dropped below bathyT:  -2.9853690410763824E+02 vs.  -2.9718414221305966E+02 at   4.8500E+02  1.5000E+01     83      8


WARNING: btstep: eta has dropped below bathyT:  -2.9853690410763824E+02 vs.  -2.9718414221305966E+02 at   4.8500E+02  1.5000E+01     83      8


WARNING: btstep: eta has dropped below bathyT:  -2.9854782268393126E+02 vs.  -2.9718414221305966E+02 at   4.8500E+02  1.5000E+01     83      8


WARNING: btstep: eta has dropped below bathyT:  -2.9854782268393126E+02 vs.  -2.9718414221305966E+02 at   4.8500E+02  1.5000E+01     83      8


WARNING: btstep: eta has dropped below bathyT:  -2.9815301030200413E+02 vs.  -2.9718414221305966E+02 at   4.8500E+02  1.5000E+01     83      8


WARNING: btstep: eta has dropped below bathyT:  -2.9815301030200413E+02 vs.  -2.9718414221305966E+02 at   4.8500E+02  1.5000E+01     83      8


WARNING: btstep: eta has dropped below bathyT:  -2.9755534328881924E+02 vs.  -2.9718414221305966E+02 at   4.8500E+02  1.5000E+01     83      8


WARNING: btstep: eta has dropped below bathyT:  -2.9755534328881924E+02 vs.  -2.9718414221305966E+02 at   4.8500E+02  1.5000E+01     83      8


WARNING: btstep: eta has dropped below bathyT:  -2.9880213894415726E+02 vs.  -2.9718414221305966E+02 at   4.8500E+02  1.5000E+01     83      8


WARNING: btstep: eta has dropped below bathyT:  -2.9880213894415726E+02 vs.  -2.9718414221305966E+02 at   4.8500E+02  1.5000E+01     83      8


WARNING: btstep: eta has dropped below bathyT:  -2.9881803938977981E+02 vs.  -2.9718414221305966E+02 at   4.8500E+02  1.5000E+01     83      8


WARNING: btstep: eta has dropped below bathyT:  -2.9881803938977981E+02 vs.  -2.9718414221305966E+02 at   4.8500E+02  1.5000E+01     83      8

MOM Day       4.250   1224: En 1.098619E-03, MaxCFL  0.45784, Mass 1.335210506161E+16, Salt  34.19102784290, Temp  -1.90052790568
MOM Day       4.250 Energy/Mass: 1.09862E-03 Truncations 139
    Total Energy: 42AAAEBAD069990E  1.4668880426188527E+13
    Total Mass:   1.3352105061612612E+16, Change:   2.0711653483983309E+09 Error:  3.24970E-01 ( 2.4E-17)
    Total Salt:   4.5652219592295469E+14, Change:   1.0237598033360336E-02 Error:  1.02376E-02 ( 2.2E-17)
    Total Heat:  -9.9600989456449438E+19, Change:  -7.0770838347138350E+14 Error:  9.89942E+03 (-9.9E-17)

WARNING: btstep: eta has dropped below bathyT:  -1.9894813926968834E+02 vs.  -1.9894813926968260E+02 at   4.8700E+02  1.3000E+01     84      7


WARNING: btstep: eta has dropped below bathyT:  -1.9637753417512459E+02 vs.  -1.9637753417510459E+02 at   4.9700E+02  1.3000E+01     89      7


WARNING: btstep: eta has dropped below bathyT:  -1.9894813926968834E+02 vs.  -1.9894813926968260E+02 at   4.8700E+02  1.3000E+01     84      7


WARNING: btstep: eta has dropped below bathyT:  -1.9637753417512459E+02 vs.  -1.9637753417510459E+02 at   4.9700E+02  1.3000E+01     89      7


WARNING: btstep: eta has dropped below bathyT:  -1.9894813926968831E+02 vs.  -1.9894813926968260E+02 at   4.8700E+02  1.3000E+01     84      7


WARNING: btstep: eta has dropped below bathyT:  -1.9637753417512457E+02 vs.  -1.9637753417510459E+02 at   4.9700E+02  1.3000E+01     89      7


WARNING: btstep: eta has dropped below bathyT:  -1.9894813926968831E+02 vs.  -1.9894813926968260E+02 at   4.8700E+02  1.3000E+01     84      7


WARNING: btstep: eta has dropped below bathyT:  -1.9637753417512457E+02 vs.  -1.9637753417510459E+02 at   4.9700E+02  1.3000E+01     89      7


WARNING: btstep: eta has dropped below bathyT:  -1.9894813926969474E+02 vs.  -1.9894813926968260E+02 at   4.8700E+02  1.3000E+01     84      7


WARNING: btstep: eta has dropped below bathyT:  -1.9831938420379169E+02 vs.  -1.9831938420378179E+02 at   4.8900E+02  1.3000E+01     85      7


WARNING: btstep: eta has dropped below bathyT:  -1.9894813926969474E+02 vs.  -1.9894813926968260E+02 at   4.8700E+02  1.3000E+01     84      7


WARNING: btstep: eta has dropped below bathyT:  -1.9831938420379169E+02 vs.  -1.9831938420378179E+02 at   4.8900E+02  1.3000E+01     85      7


WARNING: btstep: eta has dropped below bathyT:  -1.1084256210985453E+02 vs.  -1.1076859396845470E+02 at   5.1500E+02  7.0000E+00     98      4


WARNING: btstep: eta has dropped below bathyT:  -1.9894813926969471E+02 vs.  -1.9894813926968260E+02 at   4.8700E+02  1.3000E+01     84      7


WARNING: btstep: eta has dropped below bathyT:  -1.1084256210985453E+02 vs.  -1.1076859396845470E+02 at   5.1500E+02  7.0000E+00     98      4


WARNING: btstep: eta has dropped below bathyT:  -1.9894813926969471E+02 vs.  -1.9894813926968260E+02 at   4.8700E+02  1.3000E+01     84      7

MOM_forcing_type, forcing_SinglePointPrint: Called from applyBoundaryFluxesInOut (grounding)
MOM_forcing_type, forcing_SinglePointPrint: lon,lat =       5.230E+02      3.000E+00
MOM_forcing_type, forcing_SinglePointPrint: ustar =       4.413E-03
MOM_forcing_type, forcing_SinglePointPrint: tau_mag =       2.000E-02
MOM_forcing_type, forcing_SinglePointPrint: buoy is not associated.
MOM_forcing_type, forcing_SinglePointPrint: sw =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: sw_vis_dir is not associated.
MOM_forcing_type, forcing_SinglePointPrint: sw_vis_dif is not associated.
MOM_forcing_type, forcing_SinglePointPrint: sw_nir_dir is not associated.
MOM_forcing_type, forcing_SinglePointPrint: sw_nir_dif is not associated.
MOM_forcing_type, forcing_SinglePointPrint: lw =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: latent =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: latent_evap_diag =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: latent_fprec_diag =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: latent_frunoff_diag =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: latent_frunoff_glc_diag =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: sens =       2.687E-01
MOM_forcing_type, forcing_SinglePointPrint: evap =      -8.046E-07
MOM_forcing_type, forcing_SinglePointPrint: lprec =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: fprec =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: vprec =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: seaice_melt =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: seaice_melt_heat =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: p_surf =       4.583E+05
MOM_forcing_type, forcing_SinglePointPrint: salt_flux is not associated.
MOM_forcing_type, forcing_SinglePointPrint: BBL_tidal_dis is not associated.
MOM_forcing_type, forcing_SinglePointPrint: ustar_tidal is not associated.
MOM_forcing_type, forcing_SinglePointPrint: lrunoff =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: lrunoff_glc =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: frunoff =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: frunoff_glc =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: heat_content_lrunoff =      -0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: heat_content_lrunoff_glc =      -0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: heat_content_frunoff =      -0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: heat_content_frunoff_glc =      -0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: heat_content_lprec =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: heat_content_fprec =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: heat_content_vprec =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: heat_content_cond =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: heat_content_massout =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: heat_content_evap is not associated.
MOM_forcing_type, forcing_SinglePointPrint: heat_content_massout =       6.682E-04
MOM_forcing_type, forcing_SinglePointPrint: heat_content_massin =      -0.000E+00

WARNING: MOM_diabatic_aux.F90, applyBoundaryFluxesInOut(): Mass created. x,y,dh=       5.230E+02      3.000E+00     -2.088E-07


WARNING: MOM_diabatic_aux.F90, applyBoundaryFluxesInOut(): Mass created. x,y,dh=       5.230E+02      3.000E+00     -2.088E-07

MOM_forcing_type, forcing_SinglePointPrint: Called from applyBoundaryFluxesInOut (grounding)
MOM_forcing_type, forcing_SinglePointPrint: lon,lat =       5.190E+02      5.000E+00
MOM_forcing_type, forcing_SinglePointPrint: ustar =       4.413E-03
MOM_forcing_type, forcing_SinglePointPrint: tau_mag =       2.000E-02
MOM_forcing_type, forcing_SinglePointPrint: buoy is not associated.
MOM_forcing_type, forcing_SinglePointPrint: sw =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: sw_vis_dir is not associated.
MOM_forcing_type, forcing_SinglePointPrint: sw_vis_dif is not associated.
MOM_forcing_type, forcing_SinglePointPrint: sw_nir_dir is not associated.
MOM_forcing_type, forcing_SinglePointPrint: sw_nir_dif is not associated.
MOM_forcing_type, forcing_SinglePointPrint: lw =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: latent =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: latent_evap_diag =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: latent_fprec_diag =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: latent_frunoff_diag =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: latent_frunoff_glc_diag =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: sens =      -4.388E-01
MOM_forcing_type, forcing_SinglePointPrint: evap =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: lprec =       1.314E-06
MOM_forcing_type, forcing_SinglePointPrint: fprec =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: vprec =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: seaice_melt =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: seaice_melt_heat =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: p_surf =       6.856E+05
MOM_forcing_type, forcing_SinglePointPrint: salt_flux is not associated.
MOM_forcing_type, forcing_SinglePointPrint: BBL_tidal_dis is not associated.
MOM_forcing_type, forcing_SinglePointPrint: ustar_tidal is not associated.
MOM_forcing_type, forcing_SinglePointPrint: lrunoff =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: lrunoff_glc =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: frunoff =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: frunoff_glc =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: heat_content_lrunoff =      -0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: heat_content_lrunoff_glc =      -0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: heat_content_frunoff =      -0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: heat_content_frunoff_glc =      -0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: heat_content_lprec =      -9.806E-03
MOM_forcing_type, forcing_SinglePointPrint: heat_content_fprec =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: heat_content_vprec =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: heat_content_cond =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: heat_content_massout =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: heat_content_evap is not associated.
MOM_forcing_type, forcing_SinglePointPrint: heat_content_massout =      -0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: heat_content_massin =      -9.761E-04

WARNING: MOM_diabatic_aux.F90, applyBoundaryFluxesInOut(): Mass created. x,y,dh=       5.190E+02      5.000E+00      3.456E-07


WARNING: MOM_diabatic_aux.F90, applyBoundaryFluxesInOut(): Mass created. x,y,dh=       5.190E+02      5.000E+00      3.456E-07

MOM_forcing_type, forcing_SinglePointPrint: Called from applyBoundaryFluxesInOut (grounding)
MOM_forcing_type, forcing_SinglePointPrint: lon,lat =       5.230E+02      5.000E+00
MOM_forcing_type, forcing_SinglePointPrint: ustar =       4.413E-03
MOM_forcing_type, forcing_SinglePointPrint: tau_mag =       2.000E-02
MOM_forcing_type, forcing_SinglePointPrint: buoy is not associated.
MOM_forcing_type, forcing_SinglePointPrint: sw =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: sw_vis_dir is not associated.
MOM_forcing_type, forcing_SinglePointPrint: sw_vis_dif is not associated.
MOM_forcing_type, forcing_SinglePointPrint: sw_nir_dir is not associated.
MOM_forcing_type, forcing_SinglePointPrint: sw_nir_dif is not associated.
MOM_forcing_type, forcing_SinglePointPrint: lw =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: latent =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: latent_evap_diag =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: latent_fprec_diag =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: latent_frunoff_diag =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: latent_frunoff_glc_diag =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: sens =       1.359E-01
MOM_forcing_type, forcing_SinglePointPrint: evap =      -4.068E-07
MOM_forcing_type, forcing_SinglePointPrint: lprec =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: fprec =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: vprec =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: seaice_melt =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: seaice_melt_heat =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: p_surf =       4.969E+05
MOM_forcing_type, forcing_SinglePointPrint: salt_flux is not associated.
MOM_forcing_type, forcing_SinglePointPrint: BBL_tidal_dis is not associated.
MOM_forcing_type, forcing_SinglePointPrint: ustar_tidal is not associated.
MOM_forcing_type, forcing_SinglePointPrint: lrunoff =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: lrunoff_glc =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: frunoff =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: frunoff_glc =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: heat_content_lrunoff =      -0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: heat_content_lrunoff_glc =      -0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: heat_content_frunoff =      -0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: heat_content_frunoff_glc =      -0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: heat_content_lprec =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: heat_content_fprec =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: heat_content_vprec =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: heat_content_cond =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: heat_content_massout =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: heat_content_evap is not associated.

WARNING: MOM_diabatic_aux.F90, applyBoundaryFluxesInOut(): Mass created. x,y,dh=       5.230E+02      5.000E+00     -1.023E-07


WARNING: MOM_diabatic_aux.F90, applyBoundaryFluxesInOut(): Mass created. x,y,dh=       5.210E+02      7.000E+00      2.501E-07


WARNING: MOM_diabatic_aux.F90, applyBoundaryFluxesInOut(): Mass created. x,y,dh=       5.230E+02      7.000E+00      2.119E-07


WARNING: MOM_diabatic_aux:F90, applyBoundaryFluxesInOut():   54 groundings remaining

MOM_forcing_type, forcing_SinglePointPrint: heat_content_massout =       4.224E-04
MOM_forcing_type, forcing_SinglePointPrint: heat_content_massin =      -0.000E+00

WARNING: MOM_diabatic_aux.F90, applyBoundaryFluxesInOut(): Mass created. x,y,dh=       5.230E+02      5.000E+00     -1.023E-07

MOM_forcing_type, forcing_SinglePointPrint: Called from applyBoundaryFluxesInOut (grounding)
MOM_forcing_type, forcing_SinglePointPrint: lon,lat =       5.210E+02      7.000E+00
MOM_forcing_type, forcing_SinglePointPrint: ustar =       4.413E-03
MOM_forcing_type, forcing_SinglePointPrint: tau_mag =       2.000E-02
MOM_forcing_type, forcing_SinglePointPrint: buoy is not associated.
MOM_forcing_type, forcing_SinglePointPrint: sw =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: sw_vis_dir is not associated.
MOM_forcing_type, forcing_SinglePointPrint: sw_vis_dif is not associated.
MOM_forcing_type, forcing_SinglePointPrint: sw_nir_dir is not associated.
MOM_forcing_type, forcing_SinglePointPrint: sw_nir_dif is not associated.
MOM_forcing_type, forcing_SinglePointPrint: lw =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: latent =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: latent_evap_diag =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: latent_fprec_diag =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: latent_frunoff_diag =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: latent_frunoff_glc_diag =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: sens =      -3.807E-01
MOM_forcing_type, forcing_SinglePointPrint: evap =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: lprec =       1.140E-06
MOM_forcing_type, forcing_SinglePointPrint: fprec =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: vprec =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: seaice_melt =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: seaice_melt_heat =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: p_surf =       6.645E+05
MOM_forcing_type, forcing_SinglePointPrint: salt_flux is not associated.
MOM_forcing_type, forcing_SinglePointPrint: BBL_tidal_dis is not associated.
MOM_forcing_type, forcing_SinglePointPrint: ustar_tidal is not associated.
MOM_forcing_type, forcing_SinglePointPrint: lrunoff =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: lrunoff_glc =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: frunoff =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: frunoff_glc =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: heat_content_lrunoff =      -0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: heat_content_lrunoff_glc =      -0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: heat_content_frunoff =      -0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: heat_content_frunoff_glc =      -0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: heat_content_lprec =      -8.505E-03
MOM_forcing_type, forcing_SinglePointPrint: heat_content_fprec =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: heat_content_vprec =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: heat_content_cond =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: heat_content_massout =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: heat_content_evap is not associated.
MOM_forcing_type, forcing_SinglePointPrint: heat_content_massout =      -0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: heat_content_massin =      -2.117E-03

WARNING: MOM_diabatic_aux.F90, applyBoundaryFluxesInOut(): Mass created. x,y,dh=       5.210E+02      7.000E+00      2.501E-07

MOM_forcing_type, forcing_SinglePointPrint: Called from applyBoundaryFluxesInOut (grounding)
MOM_forcing_type, forcing_SinglePointPrint: lon,lat =       5.230E+02      7.000E+00
MOM_forcing_type, forcing_SinglePointPrint: ustar =       4.413E-03
MOM_forcing_type, forcing_SinglePointPrint: tau_mag =       2.000E-02
MOM_forcing_type, forcing_SinglePointPrint: buoy is not associated.
MOM_forcing_type, forcing_SinglePointPrint: sw =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: sw_vis_dir is not associated.
MOM_forcing_type, forcing_SinglePointPrint: sw_vis_dif is not associated.
MOM_forcing_type, forcing_SinglePointPrint: sw_nir_dir is not associated.
MOM_forcing_type, forcing_SinglePointPrint: sw_nir_dif is not associated.
MOM_forcing_type, forcing_SinglePointPrint: lw =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: latent =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: latent_evap_diag =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: latent_fprec_diag =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: latent_frunoff_diag =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: latent_frunoff_glc_diag =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: sens =      -2.707E-01
MOM_forcing_type, forcing_SinglePointPrint: evap =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: lprec =       8.106E-07
MOM_forcing_type, forcing_SinglePointPrint: fprec =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: vprec =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: seaice_melt =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: seaice_melt_heat =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: p_surf =       6.273E+05
MOM_forcing_type, forcing_SinglePointPrint: salt_flux is not associated.
MOM_forcing_type, forcing_SinglePointPrint: BBL_tidal_dis is not associated.
MOM_forcing_type, forcing_SinglePointPrint: ustar_tidal is not associated.
MOM_forcing_type, forcing_SinglePointPrint: lrunoff =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: lrunoff_glc =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: frunoff =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: frunoff_glc =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: heat_content_lrunoff =      -0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: heat_content_lrunoff_glc =      -0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: heat_content_frunoff =      -0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: heat_content_frunoff_glc =      -0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: heat_content_lprec =      -6.047E-03
MOM_forcing_type, forcing_SinglePointPrint: heat_content_fprec =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: heat_content_vprec =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: heat_content_cond =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: heat_content_massout =       0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: heat_content_evap is not associated.
MOM_forcing_type, forcing_SinglePointPrint: heat_content_massout =      -0.000E+00
MOM_forcing_type, forcing_SinglePointPrint: heat_content_massin =      -6.360E-04

WARNING: MOM_diabatic_aux.F90, applyBoundaryFluxesInOut(): Mass created. x,y,dh=       5.230E+02      7.000E+00      2.119E-07


WARNING: MOM_diabatic_aux:F90, applyBoundaryFluxesInOut():   54 groundings remaining


FATAL: MOM_regridding: adjust_interface_motion() - implied h<0 is larger than roundoff!

 h<0 at k=           1 h_old=   4.6434487024642807E-014 wup=   0.0000000000000000      wdn=   5.6843418860808015E-014 dw_dz=  -5.6843418860808015E-014 h_new=  -1.0408931836165208E-014 h_err=   1.2621774483536189E-029

FATAL: MOM_regridding: adjust_interface_motion() - implied h<0 is larger than roundoff!
```

# add drag params
```
#override LINEAR_DRAG = True
#override DRAG_BG_VEL = 0.05
```
similar result except after 3.75 days.
