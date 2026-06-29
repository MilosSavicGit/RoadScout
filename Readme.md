RoadScout



Part of ScoutPlatform



RoadScout is a browser-based geospatial application for discovering cultural, historical, artistic and natural places along driving routes or near the user's current location.



RoadScout is one of the first applications built on ScoutPlatform, a family of lightweight exploration tools designed to discover, document and share knowledge about places around the world using open geographic resources.



Overview



Unlike a conventional map, RoadScout scans a driving route or a nearby search area and identifies places that may be worth stopping for.



The application combines routing, geographic search, Wikipedia summaries and interactive maps into a lightweight browser application requiring no installation.



RoadScout focuses on discovering:



Historic sites

Heritage places

Museums

Viewpoints

Public art

Attractions

Notable parks and nature

Peaks

Waterfalls

Caves

What it does



RoadScout currently supports:



Route-based cultural exploration

Nearby exploration using current location

Multiple alternative routes

Numbered attraction markers

Interactive attraction list

Wikipedia descriptions

Translation to English

Community ratings

Google Maps integration

Multiple map styles

Supabase analytics

Technology Stack



RoadScout is implemented as a single self-contained browser application using open technologies.



Front End

HTML5

CSS3

Vanilla JavaScript (ES6)



No React, Angular or Vue frameworks are required.



Mapping

MapLibre GL JS

MapTiler vector tiles

OpenStreetMap

Search and Routing

OSRM routing engine

Nominatim geocoding

Overpass API

Turf.js

Data Sources

OpenStreetMap

Wikipedia

Wikidata

Supabase

How it works



RoadScout follows a simple workflow:



Select a start and destination, or use your current location.

Calculate one or more driving routes.

Scan the selected route (or nearby area) for attractions.

Display attractions in travel order.

Show Wikipedia summaries and community information.

Allow visitors to rate places and contribute future community content.

Design Philosophy



RoadScout intentionally avoids downloading large regional datasets.



Instead it performs live searches directly against OpenStreetMap services.



Benefits include:



Current geographic information

Low bandwidth usage

Small application size

Worldwide coverage

No local database maintenance

Relationship to ScoutPlatform



RoadScout is one of the first production applications within the ScoutPlatform ecosystem.



ScoutPlatform shares a common technology foundation across multiple specialised exploration applications.



Current applications



BeachScout

RoadScout



Planned applications



MountainScout

HeritageScout

LakeScout

CaveScout

BirdScout

RoadScout 2.0



RoadScout is currently being upgraded to use the shared ScoutPlatform engine already developed for BeachScout.



Planned additions include:



Community photo uploads

Community descriptions

Moderation workflow

Improved translation

Improved mobile interface

Shared ScoutPlatform architecture

Reusable platform components

Open Technologies



RoadScout is built using open technologies and open geographic resources including:



OpenStreetMap

Overpass API

Nominatim

OSRM

MapLibre

MapTiler

Wikipedia

Wikidata

Supabase

Current Status



Version: Early stable release



RoadScout is operational as a browser application and forms the basis for the next generation RoadScout 2.0 implementation within ScoutPlatform.



About



Created by Milos Savic



Belgrade, Serbia



RoadScout is developed as part of the ScoutPlatform initiative whose goal is to build lightweight, community-powered applications for discovering, documenting and preserving knowledge about places around the world.

