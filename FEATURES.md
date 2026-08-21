# OmniVisuals feature overview

## Shared rendering foundation

- EventHorizon depth/surface provider and conservative depth hierarchy.
- VectorNova optical-flow fallback for games without a better motion source.
- TemporalNexus scene-cut, reactive, disocclusion and HUD-protection state.
- Shared color, depth, normal, motion and temporal conventions across effects.

## Lighting and reflections

- SingularityRT fused Efficient/Quality GI, visibility AO, bent-normal and reflection paths.
- NebulaGI diffuse screen-space GI, GTAO/contact AO and bounded multi-bounce appearance.
- QuasarSSR roughness-aware stochastic screen-space reflections with temporal reconstruction and fallback.
- PulsarRelight appearance relighting for artistic control.

## Atmosphere and lens

- AstralVolume fog and shafts with depth-aware temporal reconstruction.
- SingularityDOF near/far cinematic depth of field, aperture, autofocus and anamorphic controls.
- CoronaBloom bloom, streaks, diffraction and halation.
- SpectralFilm film response and bounded red halation.
- GravitonLens distortion, chromatic aberration and cosine-fourth vignette.

## Reconstruction and finish

- PhotonAA spatial anti-aliasing.
- PhotonTemporalAA motion/depth/reactive temporal anti-aliasing.
- PhotonEdge chroma-preserving sharpening.
- IonClarity local contrast with anti-ringing and temporal/HUD protection.
- NebulaDeband edge/chroma-protected debanding and temporal dither.
- QuantumGrain resolution-aware zero-mean grain.
- SupernovaFinish fused LUT, sharpen, contrast, grain and vignette path.

## Color and HDR

- SpectraHistogram robust exposure percentiles.
- SpectraPilot adaptive AutoLook profiles.
- CelestialClassifier bounded scene-style guidance.
- ChromaticOrbit managed 33³ `.cube` LUT application.
- PrismLUT deterministic tetrahedral LUT processing.
- NovaHDR SDR/scRGB/PQ/HLG-oriented mapping and gamut protection.

## Player profiles

- Performance.
- Balanced 4K.
- Ultra 4K.
- Singularity Efficient 4K.
- Singularity 4K and higher-quality variants.
- Fused 4K finishing path.

No single profile can be optimal for every game, monitor and GPU. Use the closest starting point and tune only the effects the title needs.

