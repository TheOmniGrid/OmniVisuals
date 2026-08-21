# Shader guide

| Shader | Purpose |
|---|---|
| EventHorizon | Shared depth/surface data and hierarchy |
| VectorNova | Optical-flow motion fallback |
| TemporalNexus | Scene cuts, reactive masks and HUD protection |
| SingularityRT | Fused GI, AO, bent normals and reflections |
| NebulaGI | Separate diffuse GI and ambient occlusion |
| QuasarSSR | Separate roughness-aware screen-space reflections |
| AstralVolume | Fog and volumetric shafts |
| SingularityDOF | Cinematic depth of field |
| CoronaBloom | Bloom, streaks, diffraction and halation |
| PhotonAA | Spatial anti-aliasing |
| PhotonTemporalAA | Temporal anti-aliasing |
| PhotonEdge | Reconstruction sharpening |
| IonClarity | Local contrast and clarity |
| NebulaDeband | Debanding and controlled dithering |
| QuantumGrain | Resolution-aware film grain |
| PulsarRelight | Artistic appearance relighting |
| SpectraHistogram | Exposure statistics |
| SpectraPilot | Adaptive AutoLook profiles |
| CelestialClassifier | Bounded scene-style guidance |
| ChromaticOrbit | Managed cube-LUT application |
| PrismLUT | Technical shaper and tetrahedral LUT path |
| NovaHDR | SDR/HDR output mapping and gamut protection |
| SupernovaFinish | Fused finishing pass |
| SpectralFilm | Film response and halation |
| GravitonLens | Lens distortion, aberration and vignette |
| RiftRadiance | Trusted native-radiance compositor when a compatible adapter exists |

Use SingularityRT **or** NebulaGI + QuasarSSR as the principal lighting path. Use one motion provider, one AA path and one main LUT/finish path.

