# woodenfish-sandbox-issues

Technical issue tracker for the Woodenfish Android App Analysis Sandbox.

The sandbox analysis platform itself is not open source. This repository is used to collect, track, and document issues, feature status, and analysis output coverage related to the platform.

Chinese documentation is available in [README-CN.md](README-CN.md).

## Platform Scope

The sandbox targets static, dynamic, and automated analysis workflows for Android application packages and related distribution formats.

Supported analysis areas:

1. APK static and dynamic analysis
2. XAPK static and dynamic analysis
3. Automated reverse engineering analysis
4. Application network protocol analysis
5. Application threat analysis

## Report Coverage

- [x] Application basic information
- [x] Application risk score
- [x] Application certificate information
- [x] Application summary
- [x] Application permissions
- [x] Application component information
- [x] Third-party SDK and packer information
- [x] Third-party SDK key extraction
- [x] Java API call analysis
- [x] System call analysis
- [x] Runtime screenshots
- [x] Native process execution flow graph
- [x] Runtime behavior rules
- [x] Application tags and identification
- [x] Network request identification
- [x] Threat indicator distribution for domains, email addresses, and mobile numbers
- [x] Analysis environment packaging and deployment
- [x] Linux Docker deployment support
- [x] Themed analysis reports
- [x] PDF report output
- [x] HTML report output
- [x] L1 rule engine
- [x] L2 rule engine
- [x] L3 rule engine, in progress
- [ ] L4 rule engine, in progress
- [ ] Unpacking support, in progress
- [x] Privacy compliance detection rules, in progress
- [x] Risk-control SDK identification and behavior analysis, in progress
- [x] 32-bit application support
- [x] Sample graph cloud feature
- [x] Analysis environment ROM image generation for flashing
- [x] Automated HTTPS traffic capture
- [x] Flutter dynamic analysis support
- [x] Hidden API detection
- [x] MITRE detection support
- [x] CVE detection support
- [x] Identification for all OLLVM obfuscation types
- [x] Xposed module hook point analysis, under broader sample testing
- [x] LSPosed module hook point analysis
- [x] Zygisk module hook point analysis, partially supported and in progress
- [ ] Native code hook point analysis, in progress
- [ ] Native code presets
- [x] Golang application support
- [x] C# application support, partial
- [x] H5/Web application support, partial
- [x] Network-wide scanning support, partial
- [ ] Activity-name-to-screenshot mapping
- [ ] Analysis environment device information modification and simulation, in progress
- [x] KO trace analysis support, being integrated
- [x] KPM trace analysis support, being integrated
- [ ] Flutter traffic capture support
- [ ] Threat intelligence platform integration
- [ ] Flame graph support

## Reference

Feature demonstration article:

https://mp.weixin.qq.com/s/TVZ0ZX2Um8tKjghPc-abAw
