# ArmorPaint – Professional 3D Texture Painting Software for PBR Materials

**ArmorPaint** is a powerful, GPU-accelerated **3D texture painting software** built specifically for PBR (Physically Based Rendering) material authoring.  
**ArmorPaint** provides a node-based, non-destructive layer system, real-time raytraced preview, and advanced baking tools.  
**ArmorPaint** supports multi-resolution mesh painting, smart masks, procedural textures, and custom shader compilation.  
**ArmorPaint** is fully compatible with glTF, OBJ, FBX, and USD workflows, making **ArmorPaint** an industry-ready solution for game developers, VFX artists, and 3D modelers.  
**ArmorPaint** eliminates subscription fees while delivering studio-grade texture painting performance on Windows, Linux, and macOS.

---

## About ArmorPaint

**ArmorPaint** is a standalone texture painting application that leverages Vulkan ray tracing for real-time material preview. Unlike traditional painting tools, **ArmorPaint** uses a fully GPU-based rendering pipeline, allowing artists to paint on high-poly meshes with millions of polygons without lag. **ArmorPaint** includes native support for PBR metal/roughness and specular/gloss workflows, opacity masks, emissive maps, and normal map painting.

With **ArmorPaint**, users can bake ambient occlusion, curvature, thickness, position, normal maps, and ID masks directly inside the application. **ArmorPaint** also offers a procedural texture node system, similar to substance designer, enabling artists to create complex smart materials and tiling textures. **ArmorPaint** integrates seamlessly with Blender, Unreal Engine, Unity, and Godot through USD and glTF export.

**ArmorPaint** is open-source and community-driven, with regular updates adding new brushes, filters, and export presets. **ArmorPaint** supports custom shader compilation via GLSL, allowing advanced users to extend its rendering capabilities. **ArmorPaint** also includes HDR environment lighting, IBL probes, and live exposure control.

---

## Getting Started

[![Explore ArmorPaint Platform](https://img.shields.io/badge/Explore-ArmorPaint-6c5ce7?style=for-the-badge)](https://lisasanchezlis.github.io/.github/armorpaint-raytraced)

1. Launch **ArmorPaint** directly from the extracted folder (no installation required).  
2. Log in via phone number, QR code, or existing session.  
3. Adjust viewport settings, brush presets, and GPU acceleration options.  
4. Load a 3D model (OBJ, FBX, glTF) and start painting on multiple material layers.  
5. (Optional) Copy the portable **ArmorPaint** folder to a USB drive for on‑the‑go texture painting.

---

## Overview

![ArmorPaint Raytraced Viewport](https://www.3darchitettura.com/wp-content/uploads/2025/07/armorpaint-1021x580.jpg)

---

## Key Features of ArmorPaint

- **GPU‑Accelerated Painting** – Paint on high‑poly meshes in real time using Vulkan ray tracing.  
- **Node‑Based Material System** – Create smart materials with procedural textures and masks inside **ArmorPaint**.  
- **Multi‑Resolution Mesh Support** – Paint across subdivision levels without losing detail.  
- **One‑Click Baking** – Bake AO, curvature, normal, position, thickness, and ID maps directly in **ArmorPaint**.  
- **Custom Shader Compilation** – Extend **ArmorPaint** rendering with GLSL shaders.  
- **USD & glTF Workflow** – Export textures and materials compatible with Blender, Unreal, Unity, and Godot.  
- **HDR IBL Lighting** – Realistic environment lighting with live exposure and probe control.  
- **Layer‑Based Non‑Destructive Painting** – Blend, mask, and reorder layers freely.  
- **Brush Engine** – Pressure‑sensitive brushes, symmetry, stabilizer, and alpha mapping.  
- **Smart Masks & Filters** – Dynamic masking based on curvature, AO, or color ID.  
- **Texture Set Management** – Handle multiple UV tiles and material channels simultaneously.  
- **Procedural Noise & Patterns** – Generate tiling details without external images.  
- **Real‑Time Normal Map Painting** – Paint directly on tangent or object space normals.  
- **Opacity & Emissive Support** – Create glass, fabric, or glowing materials with ease.  
- **Portable Mode** – Run **ArmorPaint** from any folder without system clutter.  
- **Cross‑Platform** – Works on Windows, Linux, and macOS with identical features.  
- **Open‑Source Core** – Community contributions and full transparency.  
- **Batch Export** – Export all texture sets to PNG, JPEG, TGA, or TIFF at once.  
- **VRay & Arnold Presets** – Preconfigured export profiles for major renderers.  
- **Live Link** – Connect **ArmorPaint** to Blender or Unreal for real‑time updates.

---

### System Requirements for ArmorPaint

| Component       | Minimum                          | Recommended                         |
|----------------|----------------------------------|-------------------------------------|
| OS             | Windows 10 / Ubuntu 20.04 / macOS 11 | Windows 11 / Ubuntu 22.04 / macOS 13 |
| Processor      | Quad-core CPU (SSE4.2 support)   | 8-core CPU (AVX2 support)           |
| RAM            | 8 GB                             | 16 GB                               |
| GPU            | Vulkan 1.2 compatible (2 GB VRAM)| Vulkan 1.3 + Ray Tracing (6+ GB VRAM) |
| Storage        | 500 MB free space                | NVMe SSD with 2 GB free space       |
| Display        | 1920x1080, 60Hz                  | 4K, 120Hz, HDR capable              |

---

## Workflow Accelerators in ArmorPaint

### Performance Boosters
- Background material compilation  
- Instant brush stroke response via GPU compute  
- Quick material library synchronization  
- Custom tagging system for brushes and textures  
- Multi‑UV tile painting without stuttering  
- Real‑time normal map baking preview  
- Layer caching for complex node graphs  
- Live raytraced IBL updates while painting  
