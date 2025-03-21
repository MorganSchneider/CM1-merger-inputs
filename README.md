Six total simulations were run for this work:\n
-MERGER full simulation, 5 h integration, model output every 15 min
-QLCS full simulation, 5 h integration, model output every 15 min
-SUPERCELL full simulation, 5 h integration, model output every 15 min
-MERGER restart simulation starting from 10800 s, 1 h integration, model output every 1 min, parcel output every 15 s
-QLCS restart simulation starting from 10800 s, 1 h integration, model output every 1 min, parcel output every 15 s
-SUPERCELL restart simulation starting from 10800 s, 1 h integration, model output every 1 min, parcel output every 15 s

SIM_INFO: Contains details on model and parcel configurations
namelist.input: namelist.input files for all 6 simulations
toy.input: Parameters for tendency nudging convection initialization (Flournoy and Rasmussen 2023)
parcel.input: Parameters for parcel initialization in restart simulations
onefiles.tar.gz: Contains CM1 onefile.F source code - modified to read toy.input for tendency nudging initiation and parcel.input for parcel initialization
input_sounding: Formatted input base state sounding (NSSL LIDAR observed sounding from PERiLS 2022 IOP2, 30 March 2022, 1959 UTC)
