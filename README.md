# URDHVA — 3D ULPIN Vertical Property Mapping & Spatial Intelligence

> **From 2D Land Records to a 3D Digital Property World.**

URDHVA is a proposed 3D ULPIN-based vertical property mapping and spatial intelligence platform developed for **Smart India Hackathon 2026 — SIH26011: 3D ULPIN Generation and Vertical Property Mapping System**.

Traditional land records primarily represent property in 2D (X-Y). URDHVA introduces the **Z dimension**, enabling structured representation of multi-storey buildings, individual floors and units, basements, underground structures, utilities, infrastructure corridors and spatial relationships between them.

## Problem

Conventional 2D land records are not sufficient for increasingly complex urban environments where property and infrastructure exist vertically.

A single X-Y footprint can contain multiple apartments, commercial floors, parking levels, basements, underground utilities and infrastructure corridors. URDHVA addresses this limitation by creating a 3D representation of property and infrastructure.

## Solution

URDHVA converts heterogeneous geospatial inputs into structured 3D property volumes and associates them with a 3D ULPIN concept.

Drone, LiDAR, GIS and planning data are processed through a pipeline that generates 3D geometry, extracts floors and volumes, validates topology and assigns spatial identities.

```text
Drone / LiDAR / GIS Data
          ↓
    3D Model Generation
          ↓
 AI Floor & Volume Extraction
          ↓
    Topology Validation
          ↓
    3D ULPIN Assignment
          ↓
 LADM-based Property Registry
          ↓
   Spatial Conflict Engine
          ↓
   Web / Mobile Dashboard
