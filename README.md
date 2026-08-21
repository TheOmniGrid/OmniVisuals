<p align="center">
  <img src="media/banner-animated.gif" width="100%" alt="OmniVisuals — a coherent visual suite for OmniShade">
</p>

<h1 align="center">OmniVisuals</h1>

<p align="center"><strong>A coherent visual suite for OmniShade — 4K-focused lighting, reflections, atmosphere, reconstruction, color and HDR with clear performance paths.</strong></p>
<p align="center">Part of the <a href="#the-omnivex-suite">OmniVex</a> suite.</p>

<p align="center">
  <a href="https://www.patreon.com/TheOmniGrid"><img src="media/support-patreon.svg" height="58" alt="Support OmniVisuals on Patreon"></a>
  &nbsp;&nbsp;
  <a href="https://ko-fi.com/theomnigrid"><img src="media/support-kofi.svg" height="58" alt="Support OmniVisuals on Ko-fi"></a>
</p>

<p align="center">
  <img alt="Version 1.0.0" src="https://img.shields.io/badge/version-1.0.0-8468FF?style=flat-square">
  <img alt="Windows 10 and 11" src="https://img.shields.io/badge/platform-Windows%2010%20%2F%2011-0078D4?style=flat-square&logo=windows&logoColor=white">
  <img alt="Requires OmniShade" src="https://img.shields.io/badge/requires-OmniShade%201.0.0%2B-54D6FF?style=flat-square">
  <img alt="Shader-only" src="https://img.shields.io/badge/package-shader--only-8468FF?style=flat-square">
  <img alt="Five languages" src="https://img.shields.io/badge/languages-EN%20%C2%B7%20DE%20%C2%B7%20ES%20%C2%B7%20FR%20%C2%B7%20RO-6A5BDB?style=flat-square">
  <img alt="No telemetry" src="https://img.shields.io/badge/telemetry-none-2EA043?style=flat-square">
</p>

<!-- Quick navigation. These chips jump to a README section or maintained
     document. Keep fragment links aligned with GitHub's heading slugs. -->
<p align="center">
  <a href="#getting-omnivisuals"><img alt="Get OmniVisuals" src="https://img.shields.io/badge/%E2%86%93%20Get%20OmniVisuals-8468FF?style=for-the-badge"></a>
  <a href="#highlights"><img alt="Features" src="https://img.shields.io/badge/Features-25213B?style=for-the-badge"></a>
  <a href="SHADERS.md"><img alt="Shaders" src="https://img.shields.io/badge/Shaders-25213B?style=for-the-badge"></a>
  <a href="#requirements"><img alt="Requirements" src="https://img.shields.io/badge/Requirements-25213B?style=for-the-badge"></a>
  <a href="#honest-rendering-boundary"><img alt="Limitations" src="https://img.shields.io/badge/Limitations-25213B?style=for-the-badge"></a>
  <a href="FAQ.md"><img alt="FAQ" src="https://img.shields.io/badge/FAQ-25213B?style=for-the-badge"></a>
  <a href="SUPPORT.md"><img alt="Support" src="https://img.shields.io/badge/Support-25213B?style=for-the-badge"></a>
  <a href="CHANGELOG.md"><img alt="Changelog" src="https://img.shields.io/badge/Changelog-25213B?style=for-the-badge"></a>
</p>

> **Documentation repository.** OmniVisuals shader source, textures, presets, installer and release archives are not hosted on GitHub. Official distribution remains outside GitHub; the OmniVex donation links are below.

![OmniVisuals installer verifying OmniShade](media/omnivisuals-installer-target.jpg)

## One suite, one rendering language

OmniVisuals is an original clean-room shader suite designed specifically for OmniShade. Its effects share depth, motion, scene-cut, HDR and temporal conventions so the stack behaves as one pipeline instead of a folder of unrelated filters.

### Highlights

- **SingularityRT** — fused diffuse GI, visibility/contact AO, bent normals and roughness-aware reflections with Efficient and Quality paths.
- **NebulaGI + QuasarSSR** — separate high-control GI/AO and stochastic screen-space reflection route.
- **VectorNova + TemporalNexus** — motion estimation fallback, scene-cut state, reactive masks and HUD protection.
- **AstralVolume, SingularityDOF and CoronaBloom** — volumetrics, cinematic depth of field and controlled bloom/halation.
- **Photon AA/reconstruction family** — spatial or temporal anti-aliasing, clarity and chroma-preserving sharpening.
- **SpectraPilot, ChromaticOrbit and PrismLUT** — adaptive looks and managed LUT workflows.
- **NovaHDR** — SDR, scRGB, PQ and HLG-oriented output handling with conservative gamut protection.
- **SupernovaFinish** — fused finishing path that reduces separate 4K passes.
- Performance, Balanced 4K, Ultra 4K, Singularity and Fused profiles.
- Shader-only installation: no DLLs, hooks, APIs or add-ons.
- English, German, Spanish, French and Romanian installer UI.

## Requirements

OmniVisuals requires OmniShade 1.0.0 or newer in the target game. Setup verifies the configuration and runtime before installation. Results and cost depend on resolution, GPU, game buffers, HDR mode and selected effects.

## Honest rendering boundary

Screen-space effects cannot see hidden/off-screen geometry or reconstruct data the game never exposes. AutoLook cannot know monitor calibration or artistic intent from pixels alone. OmniVisuals supplies robust starting points, not a universal one-click guarantee.

## Getting OmniVisuals

OmniVisuals 1.0.0 is **free donationware**: payment is not required, there are no ads, and support is entirely optional. If it is useful to you and you want to fund continued work, use either official page:

<p align="center">
  <a href="https://www.patreon.com/TheOmniGrid"><img src="media/support-patreon.svg" height="64" alt="Support OmniVisuals on Patreon"></a>
  &nbsp;&nbsp;
  <a href="https://ko-fi.com/theomnigrid"><img src="media/support-kofi.svg" height="64" alt="Support OmniVisuals on Ko-fi"></a>
</p>

GitHub contains no source, installer release or download mirror.

## Documentation

- [Feature overview](FEATURES.md)
- [Shader guide](SHADERS.md)
- [Frequently asked questions](FAQ.md)
- [Support](SUPPORT.md)
- [1.0.0 highlights](CHANGELOG.md)
- [Documentation license](LICENSE.md)
- [Repository and licensing notice](REPOSITORY_NOTICE.md)

## The OmniVex suite

OmniVisuals is one of a family of tools sharing a design language and a philosophy —
modern, fast, no telemetry:

**OmniTheme** · **OmniBlock** · **OmniCleaner** · **OmniAPO** · **OmniEQ** · **OmniPlay** · **OmniScale** · **OmniShade** · **OmniVisuals** · **OmniGPU** · **OmniWrappers**

<sub>**OmniWrappers** is four Direct3D compatibility installers — OmniDXVK, OmniDxWrapper, OmniVKD3D and OmniVoodoo2.</sub>
