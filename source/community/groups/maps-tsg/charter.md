---
title: "IIIF Maps Technical Specification Group Charter"
layout: page
breadcrumbs:
 - label: "Get Involved"
   link: /get-involved/
 - label: "Community"
   link: /community/
 - label: "Groups"
   link: /community/groups/
---


## Introduction
Digitized maps and geo-located images are some of the best resources for connecting people with critical context about history and the changing face of the physical world. Given the fact that maps represent a large and important facet of digitized materials made available via IIIF, there is a growing need for better interoperability with existing tools and for connecting these assets to the broader geospatial world. The same is true of geo-located images which are being generated in various ways including via crowdsourcing and more manual methods of associating an image with a geographic location.

During discussions in the Maps Community group it has become clear that to add Geo support to version 3.0 of the IIIF Presentation API will require extending the existing specification and this is best done as a Technical Specification Group. In an early in-person gathering of the Maps Community Group, a number of Use Cases were developed which can be split into two main themes; geolocating IIIF Content (images, video or Manifests) and specific georeferencing functionality around historical maps. Below you will find how these themes are expressed through existing, separate extensions, and what use cases have been accommodated by the extensions. 

## Scope
It is the intention of this group to create a number of [IIIF Extensions]({{ site.api_url | absolute_url }}/extension/) and avoid changing the core IIIF specifications. If after a period of time and if there is wide implementation of these extensions there may be a case made to import them into the Presentation API.  

During the course of its work, IIIF Maps TSG has has encoutered wider Geo and IIIF issues. We anticpate this trend will continue, and we will do all we can to ensure a seamless operation between web resources and geospatial data on the web.

## Initial Deliverables
The following items were completed in its inaugural years.

#### An interoperable method to link IIIF content to a Geo Location for the purposes of presentation and/or navigation.
IIIF had already incorporated Web Annotation which allows for the linking of external data to internal resources.  In order for that external data to be geospatial, an ontology for geospatial descriptors was required.  IIIF Maps TSG focused on GeoJSON, and in particular GeoJSON-LD, for the existing Linked Data vocabulary.  GeoJSON is widely used used throughout spatial web practices and software and combines well with IIIF data and philosophies.  The Cookbook recipe "Represent Canvas Fragment as a Geographic Area in a Web Mapping Client" was produced in Aprial 2021 and laid the foundation for how IIIF Maps could begin to intertwine the technologies.
* [Link a IIIF resource to a point on a map](https://github.com/IIIF/iiif-stories/issues/135)
* [Linking a geo bounding box for a map](https://github.com/IIIF/iiif-stories/issues/133)
* [Geo-coding a page of an atlas](https://github.com/IIIF/iiif-stories/issues/132)
* [Presenting Aerial Surveys in IIIF](https://github.com/IIIF/iiif-stories/issues/117)

#### Create an extension which would allow the storage and presentation of Georeferencing information for a historical map.
Once GeoJSON was proven effective, IIIF Maps TSG got to work on its first extension to add a new technical property called "navPlace".  The navPlace Extension sought to make geospatial data a primary data point of IIIF resources instead of treating it as supplementary or second class data.  It came to fruition in October 2021.

The previously mentioned output focused on "geolocation", which is only a minor branch of what researchers and technologists do in the geospatial realm.  It was made clear that another popular mechanic called "georeferencing" was practiced for old and modern maps.  IIIF Maps TSG shifted focus to this usage of geospatial data and began developing an Annotation pattern by which IIIF resources could be georeferenced.  

The Georeference Extension was produced and challenged the capabilities of the IIIF APIs in relation to Linked Data.  After careful study, the IIIF API proved extendable for this technology as well and the Georeference Extension was released in May 2023.
* [Georeferencing a IIIF Map](https://github.com/IIIF/iiif-stories/issues/129)
* [Masking or identifying the region of a page which contains a map](https://github.com/IIIF/iiif-stories/issues/127)
* [Using IIIF Maps in a GIS System](https://github.com/IIIF/iiif-stories/issues/126)

### New Work Around Geolocating (that would require a new spec or extension or at a mimimum a recipe)
* [Expressing Viewcones using navPlace]()
* [Using navDate and navPlace Together]()
* [Timelapses of Entities Within a Specific Area]()
* [Geolocating in 3D]()
* [Geolocating within a Video or Soundtrack]()
* [Keyword Search for Areas on a Map]()
* [Annotate a Text Word with Geometry]()
* [Miscroscopy within Maps]()
* [Scale Dependent Rendering]()
* []()

### New Work around Georeferecing (that would require a new spec)
* [Georeferencing in 3D]()
* [Georeferencing with multiple Coordinate Reference Systems]()
* []()

## Roadmap
There is more work to do.  There are more use cases to accomodate, improvements upon delivered materials to achieve, and new geospatial possibilites to discover.  Below are some details about what IIIF Maps TSG looks to accomplish next.

__This needs to be updated to represent some kind of timeline for work delivered and when new work will be delivered__
* TODO
* TODO
* TODO

## Communication channels
* Github Repository: maps
* Slack: #maps
* Email: iiif-discuss; subject line: \[Maps-TSG\]
* Calls: monthly on off weeks to the Maps community group call  

## Community support
Please add your institution below to show your support to the formation of the group:  
* OCLC
* Stanford University Libraries (Stace Maples & Jack Reed)
* Saint Louis University (Bryan Haberberger & Patrick Cuba)
* British Library (Gethin Rees)
* Yale University (Michael Appleby)
* Moravian Library (Petr Žabička)
* Leiden University Libraries (Ben Companjen)

## Technical editors
* Rob Sanderson (Yale University)
* Michael Appleby (Yale University)
* Simeon Warner (Cornell University)
* Tom Crane (Digirati)

### ChangeLog

| Date       | Description |
|------------|-------------|
| 2023-05-?? | Update for completed goals and new goals
| 2020-11-18 | Initial page

[discovery-slack]: https://iiif.slack.com/messages/discovery/details/
[iiif-discuss]: https://groups.google.com/forum/#!forum/iiif-discuss
[events]: {{ site.root_url | absolute_url }}/event
