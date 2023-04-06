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

During discussions in the Maps Community group it has become clear that to add Geo support to version 3.0 of the IIIF Presentation API will require extending the existing specification and this is best done as a Technical Specification Group. In an early in-person gathering of the Maps Community Group, a number of Use Cases were developed which can be split into two main themes; geolocating IIIF Content (images, video or Manifests) and specific georeferencing functionality around historical maps. Both of these themes are expressed through existing, separate extensions. A selection of use cases is connected with each theme:  

### Geolocating IIIF content
These are all possible using Web Annotation or the navPlace Extension.  Some are not specifically addressed, like we couldn't link anyone to a spot with a solution, but navPlace Extension and our Geo Web Annotation suggested format can do this.
* [Link a IIIF resource to a point on a map](https://github.com/IIIF/iiif-stories/issues/135)
* [Linking a geo bounding box for a map](https://github.com/IIIF/iiif-stories/issues/133)
* [Geo-coding a page of an atlas](https://github.com/IIIF/iiif-stories/issues/132)
* [Presenting Aerial Surveys in IIIF](https://github.com/IIIF/iiif-stories/issues/117)


### Georeferencing historical IIIF maps
Directly solved by the Georeference Extension
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



## Scope
It is the intention of this group to create a number of [IIIF Extensions]({{ site.api_url | absolute_url }}/extension/) and avoid changing the core IIIF specifications. If after a period of time and if there is wide implementation of these extensions there may be a case made to import them into the Presentation API.  

This group will initially focus on the areas mentioned above but during the course of its work it may need to discuss wider Geo and IIIF issues.  

## Deliverables
__There needs to be "Delivered" and "TODO" language here.__

The expected deliverables are two extensions to achieve the following objectives:  

* Define an interoperable method to link IIIF content to a Geo Location for the purposes of presentation and/or navigation.
* Create an extension which would allow the storage and presentation of Georeferencing information for a historical map.  

## Roadmap
__This needs to be updated to represent some kind of timeline for work delivered and when new work will be delivered__
* Group formation June 2020
* Delivery of linking extension January 2021
* Delivery of georeferencing extension June 2021

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
| 2020-11-18 | Initial page

[discovery-slack]: https://iiif.slack.com/messages/discovery/details/
[iiif-discuss]: https://groups.google.com/forum/#!forum/iiif-discuss
[events]: {{ site.root_url | absolute_url }}/event
