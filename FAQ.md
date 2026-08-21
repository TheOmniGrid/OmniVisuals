# Frequently asked questions

## Which Windows version is targeted?

Windows 11 is OmniVisuals' primary supported, development and release-
qualification target. Windows 10 may continue to run, but new compatibility
claims and release testing no longer target it, so it is best-effort and not
guaranteed.

## Does OmniVisuals include OmniShade?

No. Install OmniShade 1.0.0 or newer in the game first. OmniVisuals Setup refuses to continue without a valid OmniShade configuration and runtime.

## Is OmniVisuals a DLL or injector?

No. It is a shader, texture and preset suite. Setup installs no DLL, hook, graphics API wrapper or add-on.

## Is the shader source on GitHub?

No. This repository is a documentation and support surface. The suite is provided only through authorized OmniVex distribution channels.

## Is SingularityRT real path tracing?

It is a screen-space lighting/reflection system, not engine-integrated world-space path tracing. It can only use visible frame data and trusted metadata supplied by the game/OmniShade.

## Is it automatically perfect for every game and monitor?

No. Profiles and AutoLook provide controlled starting points. Monitor calibration, game grading, HDR behavior and artistic preference still vary.

## Which profile should I start with?

Use Balanced 4K on a high-end 4K system, Performance for the lowest cost, Singularity Efficient 4K for lower-cost fused lighting, and Ultra only after measuring adequate headroom.

## Can I redistribute individual shaders?

No. The suite is licensed for personal use and may not be mirrored, repackaged or resold. Share the official OmniVisuals page.

## Does it collect telemetry?

No OmniVex cloud telemetry or advertising service is built into the shaders or installer. Local setup data stays on the device unless the user chooses to share it.
