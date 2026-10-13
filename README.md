# WoVR+

Project website for **WoVR+: World Model as Reliable Simulator for Versatile VLA Policy Optimization with RL**.

This repository contains the named project website, including authors and affiliations, real-robot demonstrations, the WoVR and WoVR+ frameworks, methodology, experimental results, the paper abstract, and same-action world-model replays.

- [Project website](https://youmo445.github.io/WoVR_Plus.github.io/)
- [Repository](https://github.com/youmo445/WoVR_Plus.github.io)

## Preview

Serve the repository root with any static HTTP server. No package installation or build step is required.

All asset paths are relative, so the site supports GitHub Pages project URLs. Videos play at a fixed 2x rate. The six-task success charts and phone-packaging results are rendered natively in the browser.

The same-action GT / WoVR+ world-model replay section follows Abstract. It contains 20 comparison videos: five RoboTwin Random pairs (the default group), five RoboTwin Clean pairs, six real-world task pairs, and four phone-packaging examples. Each pair shows GT on the left and world-model replay on the right, with head, left-wrist, and right-wrist views arranged vertically. The source videos are replayed without added captions.

## GitHub Pages

In **Settings > Pages**, choose **Deploy from a branch**, then select **main** and **/(root)**. The `.nojekyll` file serves the static site without a Jekyll build.

The project URL is:

https://youmo445.github.io/WoVR_Plus.github.io/

## Attribution

Website styling is adapted from [RISE](https://opendrivelab.com/RISE/) by OpenDriveLab. See [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md) for source information. Third-party styling is not relicensed by this repository.

Only the website and its referenced media are included. Raw recordings, source manuscripts, private provenance records, and development workspace files are excluded.
