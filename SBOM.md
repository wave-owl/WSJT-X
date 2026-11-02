# Source SBOM

**Initial source snapshot, not a release report.** Source commit `b4f9a431bcf6449df8f37b56de79d48b665b044c` predates the tooling commit. Future release reports use exact published tags.

Source repository inventory only; completeness is UNKNOWN. Syft inventories tracked source/package manifests. Gitlinks and declared vendored/model evidence are inspected at immutable pins. CMake declarations are conditional requirements, not resolved installations. This is NOT proof of operating-system packages, static-link closure, build-time resolution, or the contents of release binaries.

Generation: **success**

## Source identity

wave-owl/WSJT-X `b4f9a431bcf6449df8f37b56de79d48b665b044c`

- sbom:role: source-root
- sbom:git-commit: b4f9a431bcf6449df8f37b56de79d48b665b044c
- sbom:git-tree: 3f01398eb467ad5db990c1927df2d15d2ea5589e
- sbom:source-repository: https://github.com/wave-owl/WSJT-X
- sbom:release-tags: []
- sbom:license-evidence: [{"path": "COPYING", "sha256": "b4bbff835ca86b6051284a77138b7b31db215fb3e8aa70221464126cc9ad60fa"}]
- sbom:license-resolution: unresolved; manual review required

## Generation errors

None.

## Components and unresolved licenses

| Component | Version | Role | License |
| --- | --- | --- | --- |
| wave-owl/WSJT-X | b4f9a431bcf6449df8f37b56de79d48b665b044c | source-root | unresolved; manual review required |
| Git | unresolved | conditional-build-requirement | unresolved |
| Git | unresolved | conditional-build-requirement | unresolved |
| Git | unresolved | conditional-build-requirement | unresolved |
| ${${PREFIX}_args} | unresolved | conditional-build-requirement | unresolved |
| PkgConfig | unresolved | conditional-build-requirement | unresolved |
| Subversion | unresolved | conditional-build-requirement | unresolved |
| Boost | unresolved | conditional-build-requirement | unresolved |
| OpenMP | unresolved | conditional-build-requirement | unresolved |
| FFTW3 | unresolved | conditional-build-requirement | unresolved |
| Hamlib | unresolved | conditional-build-requirement | unresolved |
| Usb | unresolved | conditional-build-requirement | unresolved |
| Qt5 | unresolved | conditional-build-requirement | unresolved |
| Qt5AxContainer | unresolved | conditional-build-requirement | unresolved |
| Portaudio | unresolved | conditional-build-requirement | unresolved |
| Subversion | unresolved | conditional-build-requirement | unresolved |
| Subversion | unresolved | conditional-build-requirement | unresolved |
| Qt5Test | unresolved | conditional-build-requirement | unresolved |
| contrib | unresolved | declared-vendored-source | unresolved; manual review required |
| lib | unresolved | declared-vendored-source | unresolved; manual review required |
| Conditional source requirements declared by CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by bundle_fixup/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by contrib/QDarkStyleSheet/setup.py | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by debian/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by doc/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by lib/ftrsd/Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by lib/ftrsd/ftrsd_paper/Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by lib/wsprd/Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by manpages/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by map65/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by map65/libm65/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by map65/libm65/Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by map65/map65.pro | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by plots/refspec.pro | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by qmap/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by qmap/libqmap/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by qmap/qmap.pro | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by samples/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by tests/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by wsjtx.pro | unresolved | conditional-build-runtime-requirement | unresolved |
| Boost (1.62 at default HEAD) | unresolved | conditional-build-runtime-requirement | unresolved |
| FFTW3 single/threads | unresolved | conditional-build-runtime-requirement | unresolved |
| Hamlib | unresolved | conditional-build-runtime-requirement | unresolved |
| libusb | unresolved | conditional-build-runtime-requirement | unresolved |
| Qt5 GUI/multimedia/serial/SQL/Linguist | unresolved | conditional-build-runtime-requirement | unresolved |
| OpenMP optional | unresolved | conditional-build-runtime-requirement | unresolved |
| PortAudio optional | unresolved | conditional-build-runtime-requirement | unresolved |
| Qt4 | 4.7.0.0 | Syft source/package discovery | unresolved |
| Qt4 | 4.7.0.0 | Syft source/package discovery | unresolved |
| fftwf-wisdom | UNKNOWN | Syft source/package discovery | unresolved |
| libgcc_s_dw2-1 | UNKNOWN | Syft source/package discovery | unresolved |
| mingwm10 | UNKNOWN | Syft source/package discovery | unresolved |
| qthid | UNKNOWN | Syft source/package discovery | unresolved |
| qthid-4.0.exe | UNKNOWN | Syft source/package discovery | unresolved |
| qthid-4.1.exe | UNKNOWN | Syft source/package discovery | unresolved |
| rigctl-wsjtx | UNKNOWN | Syft source/package discovery | unresolved |
| map65/resources/fftwf-wisdom.exe | unresolved | Syft source/package discovery | unresolved |
| map65/resources/qthid.exe | unresolved | Syft source/package discovery | unresolved |
| map65/resources/qthid/QtCore4.dll | unresolved | Syft source/package discovery | unresolved |
| map65/resources/qthid/QtGui4.dll | unresolved | Syft source/package discovery | unresolved |
| map65/resources/qthid/libgcc_s_dw2-1.dll | unresolved | Syft source/package discovery | unresolved |
| map65/resources/qthid/mingwm10.dll | unresolved | Syft source/package discovery | unresolved |
| map65/resources/qthid/qthid-4.0.exe.exe | unresolved | Syft source/package discovery | unresolved |
| map65/resources/qthid/qthid-4.1.exe.exe | unresolved | Syft source/package discovery | unresolved |
| map65/resources/rigctl-wsjtx.exe | unresolved | Syft source/package discovery | unresolved |

License evidence paths/hashes, source manifests, model hashes and conditional
CMake declarations are recorded in SBOM.cdx.json. Declared upstream pins do not
prove vendored equivalence. No dependency installation or build was performed.
