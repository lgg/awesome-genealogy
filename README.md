# Awesome Genealogy [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of genealogy applications, collaborative family trees, archives, transcription tools, visualization tools, data standards, developer resources, and genetic genealogy services.

Genealogy combines historical research, source evaluation, personal data, and long-term preservation. This list focuses on practical tools for building and sharing family trees, working with GEDCOM data, finding and transcribing records, organizing archival research, and developing genealogy software. Treat information about living people and genetic data with particular care, consent, and respect for local law.

## Contents

- [Applications](#applications)
- [Web and Self-Hosted Applications](#web-and-self-hosted-applications)
- [Hosted Trees and Research Services](#hosted-trees-and-research-services)
- [Visualization and Publishing](#visualization-and-publishing)
- [Research and Transcription](#research-and-transcription)
- [Libraries and Developer Tools](#libraries-and-developer-tools)
- [GEDCOM and Data Standards](#gedcom-and-data-standards)
- [APIs and Open Data](#apis-and-open-data)
- [Archives and Records](#archives-and-records)
- [Genetic Genealogy](#genetic-genealogy)
- [Historical Projects](#historical-projects)
- [Related Awesome Lists](#related-awesome-lists)

## Applications

- [Ahnenblatt](https://www.ahnenblatt.com/) - Windows genealogy application with GEDCOM support, source management, plausibility checks, reports, and configurable family-tree charts.
- [Ancestris](https://www.ancestris.org/) - Free cross-platform desktop genealogy application that edits GEDCOM files directly and includes reports, validation, maps, and research tools.
- [Family Gem](https://github.com/michelesalvador/FamilyGem) - Android family-tree editor with GEDCOM import and export, sources, media, collaboration, and chart export.
- [GEDKeeper](https://github.com/Serg-Norseman/GEDKeeper) - Cross-platform personal genealogy database with GEDCOM support, charts, maps, plugins, command-line tools, and an MCP server.
- [Gramps](https://github.com/gramps-project/gramps) - Feature-complete desktop genealogy application with source management, reports, maps, media, relationship analysis, and an extension ecosystem.
- [MacFamilyTree](https://www.syniumsoftware.com/macfamilytree) - Genealogy application for macOS, iPhone, and iPad with GEDCOM, FamilySearch integration, CloudTree collaboration, maps, and interactive charts.
- [Reunion](https://www.leisterpro.com/doc/version14/reunion/welcome.php) - Genealogy application for macOS with source documentation, multimedia, reports, charts, web publishing, and companion mobile apps.
- [RootsMagic](https://www.rootsmagic.com/) - Windows and macOS genealogy application with offline family-tree management, record hints, source tools, reports, charts, books, and web publishing.

## Web and Self-Hosted Applications

- [Genea](https://github.com/genea-app/genea-app) - Local-first browser editor that reads and writes GEDCOM without requiring a server-side component.
- [Genealogy](https://github.com/MGeurts/genealogy) - Laravel family-tree application with teams, roles, relationship management, and a modern web interface.
- [GeneWeb](https://github.com/geneweb/geneweb) - OCaml genealogy engine with a web interface, GEDCOM interoperability, privacy controls, and support for very large databases.
- [Gramps Web](https://github.com/gramps-project/gramps-web) - Collaborative web application that synchronizes with Gramps Desktop and provides charts, maps, search, media, and granular access control.
- [HuMo-genealogy](https://humo-gen.com/) - Self-hosted PHP genealogy program for publishing and managing family trees with multilingual output and GEDCOM import.
- [Liberu Genealogy](https://github.com/liberu-genealogy/genealogy-laravel) - Laravel-based genealogy platform for managing people, families, events, sources, places, and GEDCOM data.
- [Silsilah](https://github.com/nafiesl/silsilah) - Laravel family-tree application designed for recording and sharing extended family relationships.
- [stammgit](https://github.com/kstucki/stammgit) - Git-native family tree application storing data as plain YAML in a Git repository, with local-first browser editing, GEDCOM import and export, and source document management.
- [The Next Generation of Genealogy Sitebuilding](https://www.tngsitebuilding.com/) - Commercial self-hosted PHP and MySQL genealogy platform for publishing trees, media, sources, reports, maps, and DNA test information.
- [webtrees](https://github.com/fisharebest/webtrees) - Mature online collaborative genealogy application with full editing, privacy controls, media management, modules, and GEDCOM support.

## Hosted Trees and Research Services

- [Ancestry](https://www.ancestry.com/) - Commercial family-tree platform with a large collection of historical records, user trees, hints, and DNA matching.
- [BillionGraves](https://billiongraves.com/) - Cemetery database built from GPS-tagged headstone photographs and volunteer transcriptions.
- [FamilySearch](https://www.familysearch.org/) - Free collaborative family tree, digitized record collection, catalog, research wiki, and genealogy learning platform.
- [Find a Grave](https://www.findagrave.com/) - Community-maintained cemetery memorial database with photographs, biographies, and family links.
- [Findmypast](https://www.findmypast.com/) - Commercial research service specializing in British and Irish records, historical newspapers, family trees, and record hints.
- [Genealogy Online](https://www.genealogieonline.nl/en/) - Publishing and matching service for GEDCOM family trees with privacy checks, source analysis, and connections to archival records.
- [Geneanet](https://www.geneanet.org/) - Collaborative genealogy service with member trees, archival collections, indexes, and matching tools.
- [Geni](https://www.geni.com/) - Collaborative world-family-tree platform focused on merging overlapping profiles and relationships.
- [MyHeritage](https://www.myheritage.com/) - Commercial family-tree, historical-record, photo, and DNA matching platform.
- [WikiTree](https://www.wikitree.com/) - Free collaborative single-family-tree community emphasizing sources, profile management, and shared standards.

## Visualization and Publishing

- [Betty](https://github.com/bartfeenstra/betty) - Static-site generator that turns Gramps and GEDCOM family trees into interactive, encyclopedia-style genealogy websites.
- [GEDCOM to Visual Map](https://github.com/D-Jeffrey/gedcom-to-visualmap) - Converts GEDCOM place and event data into an interactive geographic visualization.
- [ged2dot](https://github.com/vmiklos/ged2dot) - Command-line converter that turns GEDCOM data into Graphviz graphs for custom family-tree rendering.
- [KinGraph](https://github.com/rstacruz/kingraph) - Small command-line tool that converts a concise YAML family description into SVG, PNG, or Graphviz output.
- [Topola Genealogy Viewer](https://github.com/PeWu/topola-viewer) - Privacy-friendly interactive GEDCOM and GEDZIP viewer with multiple chart modes and PDF, PNG, and SVG export.
- [WebTreePrint](https://webtreeprint.com/) - Browser service for generating large printable family-tree charts from GEDCOM files.

## Research and Transcription

- [eScriptorium](https://gitlab.com/scripta/escriptorium) - Open-source platform for segmenting, transcribing, and training handwriting-recognition models on historical documents.
- [FromThePage](https://github.com/benwbrum/fromthepage) - Open-source collaborative platform for transcribing handwritten documents with version history, subject indexing, and Internet Archive integration.
- [OCR4all](https://www.ocr4all.org/) - Open-source OCR workflow designed for historical printed documents, including layout analysis, model training, recognition, and correction.
- [Transkribus](https://www.transkribus.org/) - Platform for handwriting recognition, OCR, layout analysis, transcription, and searching of historical documents.
- [Tropy](https://github.com/tropy/tropy) - Desktop research tool for organizing, describing, annotating, and citing photographs of archival materials.
- [Zotero](https://www.zotero.org/) - Open-source reference manager for collecting, organizing, annotating, citing, and sharing genealogical sources and research notes.

## Libraries and Developer Tools

- [ged4py](https://github.com/andy-z/ged4py) - Python library for parsing and querying GEDCOM files with a structured object model.
- [GEDCOM](https://github.com/tmcw/gedcom) - JavaScript parser and command-line toolkit for transforming GEDCOM into easier-to-process data.
- [GEDCOM 5 Java](https://github.com/FamilySearch/gedcom5-java) - Java object model, parser, and writer for GEDCOM 5 data.
- [Gramps Web API](https://github.com/gramps-project/gramps-web-api) - REST API and backend used by Gramps Web for genealogy data, media, authentication, search, and synchronization.
- [Laravel GEDCOM](https://github.com/liberu-genealogy/laravel-gedcom) - Laravel package for importing, exporting, and working with GEDCOM data in PHP applications.
- [Open Archives MCP Server](https://github.com/coret/openarchieven-mcp-server) - MCP, HTTP, and streaming server that exposes Open Archives records, statistics, census data, historical weather, and document transcriptions to AI clients.
- [python-gedcom7](https://github.com/DavidMStraub/python-gedcom7) - Python parser and serializer focused on the FamilySearch GEDCOM 7 specification.
- [read-gedcom](https://github.com/arbre-app/read-gedcom) - TypeScript GEDCOM parser designed for browser and Node.js applications.

## GEDCOM and Data Standards

- [FamilySearch GEDCOM](https://gedcom.io/) - Current specification, guides, schemas, sample files, and migration material for the widely used genealogy exchange format.
- [FHISO](https://fhiso.org/) - Community organization developing open interoperability standards for family-history information.
- [GEDCOM X](https://github.com/FamilySearch/gedcomx) - Extensible data model and serialization formats for exchanging genealogical conclusions, evidence, sources, and records.
- [GEDZIP](https://gedcom.io/specifications/FamilySearchGEDCOMv7.html#the-gedzip-file-format) - GEDCOM 7 container format for packaging a tree together with referenced media files.

## APIs and Open Data

- [Europeana APIs](https://pro.europeana.eu/page/apis) - APIs for searching and reusing digitized cultural-heritage metadata and media from European libraries, archives, and museums.
- [FamilySearch API](https://www.familysearch.org/developers/) - Developer platform for working with the FamilySearch Family Tree, person records, relationships, sources, memories, and place data.
- [Open Archives API](https://www.openarch.nl/api/) - Open API for searching Dutch and Belgian genealogical records and retrieving archive, source, event, place, and statistics data.
- [WikiTree API](https://github.com/wikitree/wikitree-api) - API documentation and examples for accessing public WikiTree profiles, relationships, ancestors, descendants, and application data.

## Archives and Records

- [Arolsen Archives](https://arolsen-archives.org/en/search-explore/search-online-archive/) - International online archive documenting victims and survivors of Nazi persecution, forced labor, displacement, and the Holocaust.
- [British Newspaper Archive](https://www.britishnewspaperarchive.co.uk/) - Commercial searchable collection of digitized British and Irish newspapers created with the British Library.
- [Chronicling America](https://chroniclingamerica.loc.gov/) - Library of Congress collection of digitized historic United States newspapers and searchable newspaper metadata.
- [Cyndi's List](https://www.cyndislist.com/) - Long-running categorized directory of genealogy websites, archives, societies, records, and research guides.
- [Europeana](https://www.europeana.eu/) - Search portal for digitized cultural heritage from European libraries, archives, and museums.
- [FamilySearch Research Wiki](https://www.familysearch.org/en/wiki/Main_Page) - Research guides organized by locality, record type, language, and methodology.
- [FreeBMD](https://www.freebmd.org.uk/) - Volunteer-transcribed civil registration index of births, marriages, and deaths for England and Wales.
- [Geneteka](https://geneteka.genealodzy.pl/) - Volunteer-built index of parish and civil birth, marriage, and death records, primarily covering Poland and neighboring regions.
- [GENUKI](https://www.genuki.org.uk/) - Genealogy reference library and locality guide for the United Kingdom and Ireland.
- [Internet Archive Genealogy](https://archive.org/details/genealogy) - Digitized family histories, local histories, directories, registers, and genealogy periodicals.
- [Irish Genealogy](https://www.irishgenealogy.ie/) - Official Irish government portal providing civil registers, church records, research guidance, and access to digitized record images.
- [JewishGen](https://www.jewishgen.org/) - Nonprofit collection of Jewish genealogy databases, family trees, burial records, Holocaust resources, gazetteers, and research communities.
- [Matricula Online](https://data.matricula-online.eu/) - Free portal for digitized church registers and ecclesiastical records from archives across several European countries.
- [National Archives: Resources for Genealogists](https://www.archives.gov/research/genealogy) - United States federal census, military, immigration, land, naturalization, and other research guidance.
- [Open Archives](https://www.openarch.nl/) - Search engine for genealogical records published by archives in the Netherlands and Belgium.
- [Portale Antenati](https://antenati.cultura.gov.it/) - Italian State Archives portal for digitized civil-registration records, archival inventories, and name-based searching.
- [Reclaim The Records](https://www.reclaimtherecords.org/) - Nonprofit project obtaining public genealogical and archival records and publishing them freely online.
- [The National Archives: Family History](https://www.nationalarchives.gov.uk/help-with-your-research/research-guides/family-history/) - United Kingdom research guides for censuses, military service, migration, occupations, courts, and other family-history records.
- [Trove](https://trove.nla.gov.au/) - National Library of Australia discovery service for digitized newspapers, books, photographs, archives, maps, and people records.
- [WieWasWie](https://www.wiewaswie.nl/en/) - Dutch genealogy portal aggregating civil registration, population registers, church records, and other archival indexes.

## Genetic Genealogy

- [DNA Painter](https://dnapainter.com/) - Chromosome mapping, relationship probability, shared-centimorgan, and hypothesis tools for genetic genealogy.
- [DNAGedcom](https://www.dnagedcom.com/) - Utilities for downloading, combining, and analyzing DNA match data from supported testing services.
- [FamilyTreeDNA](https://www.familytreedna.com/) - Commercial genetic-genealogy service offering autosomal, Y-DNA, and mitochondrial DNA tests with matching and project tools.
- [GEDmatch](https://www.gedmatch.com/) - Third-party autosomal DNA comparison and analysis service for uploaded test data.
- [Genetic Affairs](https://www.geneticaffairs.com/) - DNA match clustering, tree-building, and research automation tools across supported testing platforms.
- [ISOGG Wiki](https://isogg.org/wiki/) - Community reference for genetic genealogy concepts, testing, haplogroups, tools, and ethical considerations.
- [mitoYDNA](https://www.mitoydna.org/) - Volunteer-run open database for mitochondrial and Y-DNA sequences, haplogroups, matching, and collaborative research.
- [YFull](https://www.yfull.com/) - Independent Y-DNA and mitochondrial DNA analysis service providing phylogenetic trees, age estimates, matches, and variant interpretation.

## Historical Projects

- [dTree](https://github.com/ErikGartner/dTree) - D3-based library for family trees and other multi-parent graphs, built around an older JavaScript stack.
- [GenealogyJ](https://github.com/gedcom4j/genealogyj) - Discontinued Java desktop genealogy editor preserved as a reference for GEDCOM-based application design.
- [Liberu Genealogy Old](https://github.com/liberu-genealogy/genealogy-old) - Archived predecessor of Liberu Genealogy, formerly published as `modularsoftware/genealogy`.
- [LifeLines](https://github.com/lifelines/lifelines) - Long-running text-mode genealogy program and report language centered on GEDCOM data.
- [PhpGedView](https://sourceforge.net/projects/phpgedview/) - Historical PHP web genealogy application that influenced later projects such as webtrees.

## Related Awesome Lists

- [Awesome Digital History](https://github.com/maehr/awesome-digital-history) - Tools, methods, datasets, and learning resources for computational and digital historical research.
- [Awesome GEDCOM](https://github.com/todrobbins/awesome-gedcom) - Specifications, parsers, applications, and utilities centered specifically on GEDCOM.
- [Awesome Public Datasets](https://github.com/awesomedata/awesome-public-datasets) - Public datasets across many fields, including historical and demographic material useful for contextual research.
- [Awesome Selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted) - Free and open-source services that can be hosted on private infrastructure.
