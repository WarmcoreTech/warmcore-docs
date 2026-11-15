# Warmcore Tech Documentation

Public developer documentation for the two independent Xiaoling SDK previews.

- **Xiaoling X3 SDK** — RDK X3 Head 2.0 V1.0.2, Python package `warmcore-xiaoling-sdk` (`warmcore_xiaoling`), currently `0.6.0a1`.
- **Xiaoling S100 SDK** — RDK S100 / ROS 2 Humble technical baseline, Python package `xiaoling-s100-sdk` (`xiaoling_s100`), currently `0.1.0a1`. Pro / Ultra hardware assignments require device-specific confirmation.

These are separate SDKs with separate private source repositories. This public repository contains approved developer-facing documentation only—not private SDK source, vendor handbooks, firmware, vendor message definitions, secrets, or calibration files.

## Documentation

- [X3 overview](en/xiaoling-x3/v1/overview.mdx)
- [S100 overview](en/xiaoling-s100/v1/overview.mdx)

The documentation is built using [Mintlify](https://mintlify.com). See `docs.json` for navigation and configuration.

English is the first published language. Traditional Chinese, Simplified Chinese, Japanese, Korean, and French are planned. Translation work must preserve technical identifiers and be reviewed before publishing.

## Engineering status

SDK implementations and offline/loopback tests **do not** demonstrate runtime or physical compatibility with any robot. Both SDKs remain developer previews with device-specific ROS and hardware verification pending. Physical head, eye, and mouth control is not enabled through the preview SDKs.

The `v1` URL folder represents a documentation generation, not a stable 1.0 SDK release.
