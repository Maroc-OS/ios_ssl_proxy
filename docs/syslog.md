From syslog:

Mar  7 17:04:38 Scotts-iPhone Preferences(Security)[487] <Notice>: could not disable pinning: not an internal release
Mar  7 17:04:38 Scotts-iPhone Preferences(Security)[487] <Notice>: could not enable test cert: not an internal release
Mar  7 17:04:38 Scotts-iPhone Preferences(Security)[487] <Notice>: could not enable test hierarchy: ApplePinningAllowTestCertsGS not true
Mar  7 17:04:38 Scotts-iPhone Preferences(Security)[487] <Notice>: could not enable test hierarchy: AppleServerAuthenticationAllowUAT not true
Mar 16 10:25:15 scottgls-iPhone SpringBoard(Security)[57] <Notice>: could not enable test hierarchy: ApplePinningAllowTestCertsiPhoneApplicationSigning not true
AppleServerAuthenticationAllowUATFMiP

Idea: modify using proxy to indicate that this in fact an internal release.