PDS_VERSION_ID           = PDS3                                               
                                                                              
RECORD_TYPE              = STREAM                                             
INSTRUMENT_HOST_NAME     = "ROSETTA-ORBITER"                                  
                                                                              
OBJECT                   = TEXT                                               
 PUBLICATION_DATE         = 2019-07-18                                        
 INTERCHANGE_FORMAT       = ASCII                                             
 NOTE                     = "ASCII description of the SREM Archive"           
END_OBJECT               = TEXT                                               
END                                                                           
                                                                              
***************************   File AAREADME.TXT   ****************************
                                                                              
                                                                              
                                                                              
Acronyms:                                                                     
==============================================================================
                                                                              
EAICD:     Experimenter to (Science) Archive Interface Control Document       
ESA:       European Space Agency                                              
ESAC:      European Space Astronomy Centre                                    
ftp:       file transfer protocol                                             
PDS:       Planetary Data System                                              
PSA:       Planetary Science Archive                                          
PSA-DH:    Planetary Science Archive Data Handler                             
RMOC:      Rosetta Mission Operations Centre                                  
RO:        Rosetta Orbiter                                                    
S/C:       Spacecraft                                                         
SCIOPS:    Science Operations Department                                      
SGS:       Science Ground Segment                                             
SREM       Standard Radiometry Environment Monitoring                         
TM:        Telemetry                                                          
UTC:       Coordinated Universal Time                                         
                                                                              
==============================================================================
Overview:                                                                     
==============================================================================
The Standard Radiation Environment Monitor (SREM) performs a wide range of    
radiation monitoring functions in orbit. It is designed as standard           
equipment compatible with all common spacecraft interfaces and mission        
constraints.                                                                  
                                                                              
The level 5 SREM data sets contain derived electron and proton flux           
energies in MeV from the Standard Radiation Environment Monitor (SREM)        
instrument on the Rosetta spacecraft, which had the primary target of         
comet 67P/Churyumov-Gerasimenko. These data provide a measure of the          
radiation in the spacecraft environment.  The archive content and             
structure is summarised below.                                                
                                                                              
==============================================================================
SREM Data Archive:                                                            
==============================================================================
                                                                              
a) S/C Data                                                                   
=========================                                                     
                                                                              
CODMAC Level / Type             Data Type       Data Content                  
                                                                              
           5 / DERIVED Data     ASCII table     Proton and Electron flux Data 
                                                                              
The data can be found in the following directory:                             
   */DATA/                                                                    
                                                                              
b) Supporting Files                                                           
=========================                                                     
                                                                              
Supporting files for the Archive end user include PDS documentation,          
descriptions and searchable indices.  These are organised into three sub-     
directories immediately below the root directory:                             
     - CATALOG                                                                
     - DOCUMENT                                                               
     - INDEX                                                                  
                                                                              
==============================================================================
Structure of the Volume:                                                      
==============================================================================
                                                                              
Root Directory                                                                
   |                                                                          
   |--- AAREADME.TXT   (PDS required introduction to the data set )           
   |                                                                          
   |                                                                          
   |../CATALOG/                                                               
   |     |                                                                    
   |     |--- CATINFO.TXT   (List of the CATALOG folder contents)             
   |     |--- DATASET.CAT   (Description of the data set)                     
   |     |--- INST_SREM.CAT (Description of the SREM instrument)              
   |     |--- INSTHOST.CAT  (Description of the Rosetta spacecraft)           
   |     |--- MISSION.CAT   (Description of the Rosetta mission)              
   |     |--- PERS_SREM.CAT (List of relevant personnel for SREM)             
   |     |--- REF.CAT       (List of references for the Rosetta data sets)    
   |     |--- SOFTWARE.CAT  (Information regarding any software for SREM)     
   |                                                                          
   |                                                                          
   |../DATA/                                                                  
   |     |                                                                    
   |     |--- *.TAB Files  (Data products in ASCII table format)              
   |     |--- *.LBL Files  (Detached label files for each data product)       
   |                                                                          
   |                                                                          
   |../DOCUMENT/                                                              
   |     |                                                                    
   |     |--- DOCINFO.TXT                  (List of the DOCUMENT folder       
   |     |                                 contents)                          
   |     |--- EAICD_SREM.PDF Files         (PDF version of EAICD)             
   |     |--- EAICD_SREM.LBL Files         (EAICD label)                      
   |     |--- SREMDC_FINAL_REPORT_V1.0.PDF (PDF version of Final SREM         
   |     |                                 Data Consolidation Report)         
   |     |--- SREMDC_FINAL_REPORT_V1.0.LBL (Detached label for the SREM       
   |     |                                 Data Consolidation Report)         
   |                                                                          
   |                                                                          
   |../EXTRAS                                                                 
   |     |                                                                    
   |     |---*.cdf Files  (CDF format files of the DATA products)             
   |     |                                                                    
   |     |                                                                    
   |../INDEX                                                                  
   |     |                                                                    
   |     |--- INDXINFO.TXT (List of the INDEX folder contents)                
   |     |--- INDEX.LBL    (Detached label file for INDEX.TAB)                
   |     |--- INDEX.TAB    (Index of the data set in tabular format)          
   |                                                                          
   |                                                                          
   |---VOLDESC.CAT   (Volume description file for the SREM data)              
                                                                              
The ROSETTA project decided that the data would be archived in the PDS Version
3 format and, consequently, the layout of this volume and all associated label
files for each file conform to the PDS / PSA guidelines.                      
                                                                              
==============================================================================
Contact Information:                                                          
==============================================================================
                                                                              
Data generated by:                                                            
                                                                              
Francisco Vallejo                                                             
ESA/ESAC                                                                      
Villanueva de la Canada,                                                      
Madrid, 28692,                                                                
Spain.                                                                        
                                                                              
fvallejo@sciops.esa.int                                                       
                                                                              
==============================================================================
