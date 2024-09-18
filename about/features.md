# Features

## General

- Cross-Platform! Windows, Linux & Mac!
- Unity-like Editor & Scripting API
- C# Scripting
- GameObject & Component structure
- A Powerful Custom UI Library
  - Same Library for In-game and Editor UI
  - 3D Drawing in UI used for Gizmo's
  - Immediate Mode with retained properties
- .NET 8
- Editor with support for Editor Scripts and Custom Editors
- Physics ([Bepu Physics 2](https://github.com/bepu/bepuphysics2))
  - Colliders: Box, Sphere, Capsule, Cylinder, ~~Mesh Collider~~ - Needs to be re-implemented
  - Triggers
  - Raycasts and Sweeps
  - Non-Kinematic Character Controller (Just a fancy rigidbody)
    - Supports Moving Platforms
  - A ton of physical constraints (All of Bepu's constraints)
- Unity-like Coroutines
- Playtest directly in Editor
- ScriptableObjects
- Projects & Project Settings
- Unity-like Serializer to create In-Memory Graphs
  - Graph -> Custom Text Format
  - Graph -> Binary
- Fully 64-bit using Doubles
- Large World Coordinates Support
  - Camera Relative Rendering
- Scene System
- Modular Audio Backend
  - OpenAL
  - Currently only supports .wav files
- Prefabs
- Build System - Build to Standalone Application
  - Packed Asset files
  - Less than 15mb builds - currently working on removing 10mb, Almost done!
  - Only exports used assets
  - Supports Windows, Mac & Linux
- Navmesh and AI Agents (Recast & Detour)

## Graphics Rendering

- Modular Graphics Backend
  - OpenGL
  - OpenGL ES
  - Vulkan
  - Metal
- Powerful Customizable Node-Graph based Render Pipeline
- PBR (Physically Based Rendering) using Cook-Torrance BRDF
  - Albedo Map
  - Normal Map
  - Roughness Map
  - Metallic Map
  - Ambient Occclusion Map
  - Emission Map
- Forward Renderer
- Multiple Shader Passes
- Point, Spot, and Directional Lights
  - Spot & Directional Light Shadows - Point shadows is not implemented
  - Shadow Atlas
  - Dynamic Shadow Resolutions
- Post Processing
  - HDR with Tonemapping (Melon, Aces, Reinhard, Uncharted, Filmic)
- Transparency
- Procedural Super Performant Skybox

## Asset Pipeline

- A Powerful Asset Pipeline with a very similar structure to unity
- Meta Files & Reference by GUID
- Import Caching
- Support for Custom Importers
- Supports many major file formats via ImageMagick, Assimp, etc
- Sub-Assets, Assets stored inside other assets
- Dependency Tracking
