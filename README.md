Overlay Management Package
===================
This is the overlay repository for all common overlays within
CypherOS. Here, we can change system components without
touching the core framework.

How to use
===================
Both AOSCP and Google overlays are enabled by default. In order to exclude one or both, you should use:

    TARGET_USES_AOSCP_OVERLAY := false

or

    TARGET_USES_GOOGLE_OVERLAY := false

in your devices BoardConfig.mk, or export them before building with:

    export TARGET_USES_AOSCP_OVERLAY=false