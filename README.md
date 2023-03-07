# Linked Open Data Management System Comparison

## Introduction
This comparison was developed in the Linked Open Data Working Group of the [NFDI4Culture consortia ](https://nfdi4culture.de/) and resulted from collaboration with users and developers of the respective software solutions.  
The information is intended to show the possibilities, limitations, strengths and weaknesses of each tool and to help researchers choose the right tool for their particular project.  
If you have any questions or suggestions, please contact the [Lozana Rossenova](lozana.rossenovatibeu) or [Robert Nasarek](r.nasarek@gnm.de).

## Comparison Categories

### 1 Official website
The official website of the tool. Free text, e.g. https://example.com.
##### Values
* **Free text**

### 2 License
Which license is applied to the software? Free text, i. e.  MIT, Apache, GNU, BSD.
##### Values
* **Free text**
 
### 3 Source code availability
Is the code available online (in GIT etc.)?
##### Values
* **Available**: Code base is open.
* **Closed**: Code base is not open.

### 4 Community maturity
What is the level of maturity of the open source community around this tool?
##### Values
* **Mature**: Open repositories on open Git platforms, active and constantly contributions from many different contributors, wide / international variety of community forums and events.
* **Fledgling**: Open repositories on open Git platforms, regulary contributions from few contributors, limited number of community forums and events.
* **Emerging**: This product does not yet have a contributor community or is not open source software.

### 5 Statistics (with time stamp)
How many contributors / forks / stars on the project page in Git? Add relevant stats for larger underlying software projects in the extended answers (e.g. Drupal or MediaWiki). Add a time stamp.
##### Values
* **Free text**, i. e. 80 public sites, >22K Commits, 16 Stars (29.04.2022)

### 6 Payment models
Is this a service you pay for?
##### Values
* **Free**: Can be run entirely in-house
* **SaaS**: Paid-services-only model
* ***Hybrid model***:Free to self-host; Paid model with extras.

### 7 Maintainer
The organization/ institution/ person who currently works on the RDMS. Offers the possibility to support.
##### Values
* **Free text**, i. e. Wikimedia Deutschland

### 8 Documentation
Is there a reachable and up-to-date documentation, which explains the installation and usage of features of the program?
##### Values
* **Full**: Everything is documented
* **Sufficient**: Installation and main features
* **Little or outdated**: Not sufficient to install the program successfully or to use the main features

### 9 Infrastructure stack
Which environment / software components are needed to set up the tool (not exhaustive)? Which particular stack configuration works well?

#### 9.1 Framework
Parent infrastructure, i. e. Drupal, MediaWiki with programming language like PHP, Javascript etc.
##### Values
* **Free text**

#### 9.2 Webserver
The server software, i. e. Apache, Nginx...
##### Values
* **Free text**

#### 9.3 Database
Relational database providers, like MySQL or Postgres or NoSQL Providers like MongoDB or eXist-DB.
##### Values
* **Free text**

#### 9.4 Triplestore
Triplestore providers like graphDB or Blazegraph.
##### Values
* **Free text**

#### 9.5 Search
Additional server for searching, i. e. Solr or ElasticSearch.
##### Values
* **Free text**

#### 9.6 Image Server
Image server for IIP or IIIF ready Images, i.e. IIPImage Server, Mirador, DFG Image Viewer.
##### Values
* **Free text**

#### 9.7 3D Viewer
Viewer for 3D Images, i. e. Sketchfab or Kompakkt.
##### Values
* **Free text**

#### 9.8 Containerization
For which providers exists  containers or container-images, i. e. docker.
##### Values
* **Free text**

#### 9.10 Other (please add)
Any other stack parts used with the LODMS? Please provide as list.
##### Values
* **Free text**

### 10 APIs
What endpoints, interfaces, connectors are available?

#### 10.1 RESTful
##### Values
* **True/ False**

#### 10.2 SPARQL
##### Values
* **True/ False**
  
#### 10.3 MediaWiki HTTP
##### Values
* **True/ False**

#### 10.4 GraphQL
##### Values
* **True/ False**

#### 10.5 SQL
##### Values
* **True/ False**
#### 10.6 Other (please add)
Any additional API, please provide as list.
##### Values
* **Free text**
  
### 11 API usability level
How well is the API documented?
##### Values
* **Well documented**: This means that there are examples & definitions for requests; it is also possible to understand the API without being a developer. Explicit documentation of routes and vocabulary exists outside the program code.
* **Little or self documentation**: Gaining information works only implicitly over requests etc.

### 12 SPARQL Endpoint usability level
Are there own interfaces for the usage of the endpoints, like query consoles etc.? Do they have documentations or a high level of usability?
##### Values
* **Availability of graphical user interfaces, examples and documentation**: Query Consoles, API-functions, explainations etc. are available within the RDMS.
* **Depends on third party triple store**:
Usability level depens on the third party provider of the endpoint or triple store.
* **Little or self documentation and no GUIs**: RDMS just providing the endpoint.

### 13 Reification
Can you add statements about statements on-the-fly - like 'annotations' - be it time, provenance, or others without changing the ontology or datamodel?
##### Values
* **yes/ no**

### 14 Reasoning operations via the triplestore endpoint
Can you do reasoning on the triplestore?
##### Values
* **yes/ no**

### 15 Method for ontology definition
How can you define the properties and classes of an ontology?
##### Values
* **Within the LODMS**: There is an interface, formular or similar, which allows you to design the ontology structure and/or constraints.
* **Through import**: You have to develop the ontology with a third party tool (i.e. Protègè) and then import the rdf/owl file.
* **Hybrid**: Both import of existing schemas plus manual edits are allowed.

### 16 Ontology constraints
Are there any formal constraints in the data model, i. e. domains and ranges of properties reflected in the data model? 
##### Values
* **Based on semantically defined rules**: Domains and ranges of properties, hierarchie of classes etc. of a given ontology are reflecting in the options of connecting or arranging fields in the RDMS data model.
* **None**: You can use the semantics of a given ontology, but you are not bind to the property or hierarchical constraints.

### 17 Data validation
Can entities be validated (e.g. a person must have name, address and phone number). Can fields be validated (e.g. it must be an integer/string/URL etc.)?

#### 17.1 Ontology level
It is possible to check if an entity is "correct", i.e. if an entity for a person has the required fields like name, adress or age.
##### Values
* **True/ False**

#### 17.2
You can validate the field type, like if it has to be an integer or string, url etc.
##### Values
* **True/ False**

### 18 Standardization and interoperability for data mapping / harvesting
Can you easily perform standard-compliant data mapping/harvesting? Harvesting in this regard means that data from external repositories can either be easily transferred to one's own repository or displayed in one's own context in the sense of LOD, for example, alternative names of a person from the DNB/GND repository.
##### Values
* **Yes, out of the box**: There are adapters or mapping aids within the RDMS.
* **Yes, via plugins or third-party tools**: You have to install and configure additional modules, add-ons etc, use third-party tools (e.g. OpenRefine) or run custom scripts.
* **No**: It is not possible to map or harvest data from external sources.

### 18 PID generation
Can you auto-generate persistent identifiers for items?
##### Values
* **yes/ no**

### 20 PID reuse
Can you reuse of existing PIDs?
##### Values
* **yes/ no**

### 21 Import/ export function
Can you use common formats to import/ export data (ODBS, CSV, JSON)?
##### Values
* **Yes, out of the box**: Import/ Export function is (GUI-)provided within the RDMS.
* **Yes, via plugins or third-party tools**: You have to install addons or extensions to import/export data.
* **No**: No possibility to import/ export data via the RDMS.

### 22 Data type input support
What formats can be entered into a data field?

#### 22.1 Text
Strings of any kind.
##### Values
* **True/ False**

#### 22.2 Numeric
Integer and floats of any kind.
##### Values
* **True/ False**

#### 22.3 Boolean
Like FALSE/TRUE or 0/1.
##### Values
* **True/ False**

#### 22.4 Date and time
Including different kinds of formats (dd.mm.yyyy, mm.dd.yyyy:hh:mm:ss etc.)
##### Values
* **True/ False**

#### 22.5 IRI/URI/URL
Normaly in format like http://example-iri/my-ontology/
http://example-website.com
##### Values
* **True/ False**

#### 22.6 Identifiers
Both internal and external ids of any kind.
##### Values
* **True/ False**

#### 22.7 Media files
Complex files in any format, audio (WAV, MP3, OGG, WMA...), Video (MP4, MOV, AVI...), 3D (BLEND, OBJ, FBX...) etc. More detailed integration options at #30.
##### Values
* **True/ False**
  
#### 22.8 Geospatial
WKP, LAT/LON ...
##### Values
* **True/ False**
  
#### 22.9 Other (please add)
##### Values
* **Free text**

### 23 Multiple value entries per field
Can you add multiple distinct values for a particular metadata field? Can the order of the entries be changed later? Can different data types be used in multiple entries?
#### 23.1 Allowed
##### Values
* **True/ False**
  
#### 23.2 Changable order
##### Values
* **True/ False**

#### 23.3 Mixed data types
##### Values
* **True/ False**

### 24 Content templating
Is it possible to customize the frontend framework based on content and/or data type? For example, can the items for people, locations, and e.g. cultural artefacts look differently to end-users (i.e. have a different structure of statements and statement groupings, different placement of images and media on the screen, etc.).

#### 24.1 Data entry
##### Values
* **True/ False**
 
#### 24.2 Data presentation
##### Values
* **True/ False**
#### 24.3 Customisable per entity type
##### Values
* **True/ False**
#### 24.4 Via user interface
##### Values
* **True/ False**
#### 24.5 Requires additional configuration or coding
##### Values
* **True/ False**

### 25 Front-end design	
The front-/backend, buttons, basic interfaces "what comes from a fresh installation".
##### Values
* **Fully customizable themes**: Customize color, fonts, style formatting, animations, content regions etc.
* **Fixed themes**: Reuse existing themes for styling.
* **Hard-coded design**: Have to hard code hmtl, css, javascript etc. to change appearance.

### 26 Translatable/ multilingual Interface 
What's the granularity for multilingual support?
#### 26.1 Interface
The front-/backend, buttons, basic interfaces "what comes from a fresh installation".
##### Values
* **True/ False**
 
#### 26.2 Data model
Terminologies and semantics.
##### Values
* **True/ False**

#### 26.3 Data values
Actual data values.
##### Values
* **True/ False**

### 27 Version control
Is it possible to track revisions of the data set on individual data statement level within the RDMS? As well as on ontology level?

#### 27.1 Entity level
Build revisions on distinct entities and their values.
##### Values
* **True/ False**

#### 27.2 Ontology level
Build revisions of the whole database/ ontology.
##### Values
* **True/ False**

### 28 User access control on the entity/fact level
Can you edit (create, read, update or delete) the triplestore on the entity/statement level? Is editing done only via the GUI or can it also be done bi-directionally (from the triplestore endpoint to the GUI)?
#### Values
* **One-directional**: You can only alter content in the CMS or the triplestore.
* **Bi-directional**: Altering data in CMS/triplestore and reflecting vice versa.

### 29 Access rights settings
Possibility to set granular access (read and/or write) level rights for different user groups?
##### Values
* **Full granularity of access**:
* **Limited number of access tiers**:
* **None**: fully open or fully closed system:

### 30 Media integrations
Which media types can be integrated?

#### 30.1 Audio
MP3, WAV...
##### Values
* **True/ False**

#### 30.2 Image
TIFF, JPG, PNG, WEBM...
##### Values
* **True/ False**

#### 30.3 Video
MKV, AVI, MP4....
##### Values
* **True/ False**

#### 30.4 3D
BLEND, OBJ, FBX...
##### Values
* **True/ False**

#### 30.5 Remote
Youtube, Vimeo...
##### Values
* **True/ False**

#### 30.6 Maps
GoogleMaps, Leaflet, Open Street Map...
##### Values
* **True/ False**

#### 30.7 Other (please add)
Additional media types, please provide as list.
##### Values
* **Free text**

### 31 Data visualization
What forms of visualization does the tool offer?
##### Values
* **Build-in**: Visualisation tools ships with the RDMS.
* **Via extensions**: You have to install third party addons or extension to perform special visualisations.
* **None**: No data visualisations within the RDMS possible.

### 32 Data analysis
What forms of data analysis does the tool offer?
##### Values
* **Built-in**: Analysis tools ships with the RDMS.
* **Via extensions**: You have to install third party addons or extension to perform special analysis.
* **None**: No data analyses within the RDMS possible.

### 33 Third-party tools and libraries
What third party tools and libaries exist for this tool?
##### Values
* **Mature**: Many active maintained tools for several purposes.
* **Fledgling**: Tools for the important tasks.
* **Few or outdated**: Few tools or not actively maintained.

### 34 Scalability
Can this tool scale well to millions of items?
##### Values
* **yes/ no**