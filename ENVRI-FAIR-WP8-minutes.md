WP8 kick-off session
----------------------

## Introduction to WP8

 Cathrine presents the main objectives:
 * Data FAIR for EOSC put also make data FAIR for all users.
 * 5 sub objectives
   * Seek common solutions together with WP5 and WP7
 * 55 % of resources related to task 8.4 (implementation)
 * Goal: Clarify open issues and expectation of the group
 * How to do work on the tasks
 * how we involve the WP8 group with other RIs
 * How we will make use of the reosource in wp5 and wp7
 * Each RI will present their main motivation for ENVRI FAIR, what are the various RIs main interst and work in WP8
 * Sanna: how we are communicating and with whom in relation to the different workpackage activitites, as well as with the other domains

### Cathrine presents the ACTRIS RI
 
 * ACTRIS RI goal to have new DMP by October this year
 * Strongly linked to GAW and EMEP, NDACC and Aeronet
 * Structure of ACTRIS different data centre units and many contributing national facilities providing data to often multiple data centre units.
 * Presents ACTRIS roadmap to fairness -> work in ENVRI-FAIR
 * Maturity matrix as a basis for discussion internally at the data centre, providing kind of a whish list for what ACTRIS wants and needs to focus on during the project
 * Task 8.3 we have to work on 8.3 while working on 8.2, so we now already have to know where we are going

## Ander Tjulin, EISCAT 3D

 * In implementation phase since 2017
 * Working on building hardware for their system
 * First data expected 2021
 * Goal of having centralised data storage and access
 * Main users:
   * campaign based observations -> scientists in member countries
 * Link to other initiatives:
   * URSI 
 * Notable missing links: copernicus, GEO, GEOSS, WMO
   * EISCAT observation volume outside their coverage
 * Possible use for EISCAT high level data: Met and climate models,
   * Atmospheric chemistry
   * Space debris tracking (ESA)
   * Ionospheric status (Galileo)
 * What they do in envri fair
   * Ensure FAIR-ness of EISCAT_3D data
   * increase interaction with other RIs (e.g. SIOS is interesting)
 * Motivation: increase usability and demand for the data, make potential users aware of the data
 * Develop and make use of metadata standards, currently interface is based on ingenering type of thinking
 * User friendly user interface to data
 * Implementation of PIDS
 * USser support in general
 * Q: If legacy should be included, size of old data is not so big, so it should be possible to include old data as well
 * Q: If they have pilot, currently builindg 
 * Sanna: on user support, standarization of this was raised by ACTRIS, and also relevant for EISCAT 3D
 * Level 3 physical parameters will make available
 * Markus: If they will provide NRT data. Likely they will provide some realtime, already now do that related to rocket launches and could also be other data products. Argument to increase the use for the metrological models etc addressed by Markus

## IAGOS, Damien Boulanger

 * Operational since july 2011
 * 8 aircrafts
 * NRT data (less than 3 days) for copernicus for data assimilaton, model evaluation
 * RRT in progress (less than 3 hours), only vertical profiles for now
 * Services:
   * Data portal: netcdf and ascii
   * REST services: machine readable access to data and metadata
   * OGC services work in progress: CSW, WCS and OpenDap through thredds 
 * Links to internation projects:
   * CAMS, COPERNICUS ...
 * Main motivation: 
   * complete improve data centre, contribute to french envrionmental cluster (common technical solutions)
   * Provenance, QAQC
   * Write the DMP
   * Vocabulary and ontology for data discovery
   * Authentication
   * common interfaces for data
   * Use PIDs for data workflows
   * Currently use DOI for L2,3,4
   * Semantic search
 
## ICOS Atmosphere

 * Distributed infrastructure
 * ERIC
 * 12 participanting countries
 * multi domain infrastructure
 * 18 stations -> 30
 * Presents high resolution CO2 forecas example using icos data in copernicus service
 * Carbon portal develop products, transport models, 4d models 
 * 609 user acocunts, 54 500 data object downloads?
 * presents ICOS data flow, presents EUDAT services B2STAGE, B2SAFE, B2SHARE, VRE (EGI), Datacite
 * Motivation:
   * Metadata standards; WMO, NEON
   * Web semantic, Data statistics, DMP, SMP
   * Traceable workflows
   * Web semantic
   * PID, DOIs for open ended data, timeserise, dynamic DOIs

## SIOS
 
 * Consortium of institutions of institutions in and around Svalbard
 * Operational last year (2018)
 * Svalbard is importan: Large temperature gradient, major currents, high arctic but well developed infrastructure
 * SIOS work towards: 
   * systematic observations, coordinate exsisitng observations, give tools etc.
   * help give access to infrastructure
 * SIOS data mangement service:
   * Data centres are owners of the data
   * use discovery metadata to get the data and index them and make them available through the portal.
   * They offer visualization and transformation of SIOS relevant data sets
   * Development of data collection templates
   * Relise heavily on NetCDF/CF and OPeNDAP, in order to establish services on top of the data, working on subsets of data etc.
 * Linked to MWO GBIF activities
 * Motivation:
   * Harmonize data, documentation and encoding
   * Tools to users so that they can access data in a certain way and use
   * connecting data from different resources
 Gaps:
   * Non standarized interface to data at contributing data centres
   * Non standards documentation of data at contributing data centres
   * Make data more available and known
   * Comment: Different ways of data levels among RIs, idea to harmonize this, our data would be used in a integrated way, this could confuse users. Probably we should look at this to be more usable from the outside.
   * Markus suggest ontology, common set of terms to describe our data

## Task 8.2 Analyse the capabilities for FAIRness of the atmospheric RIs

 * GOAL: Determine the level of FAIRness of the atmospheric RIs.
   * Increase the use of data
 * Needs to happen during this year
 * FAIR for different set of digital objects
 * FAIRness of (hierarchy):
   1. Environmental variables
   2. services 
   3. algorithms
   4. workflows/processing
   5. Data centre/storage  
 * Proposses a design framework for FAIR (use Wilkinson et al., GO FAIR, March 2018)
   * Use this as background to assess FAIRness?
 * In order to provide good services - need to meet the user, target end users to be identified to ensure applicability
   * organize a user meeting
 * Need to come up with a milestone that shows existing policies and licences in the atmospheric subdomain
 * Alex: also think of possible new user groups, we should use our fantasy
 * From Gelsomina: Not only about the number of users, but also about the impact of the use of data
   * Possible big market for air quality etc.
   * Through wp5 we need to be consistent with the others and not diverge completely
