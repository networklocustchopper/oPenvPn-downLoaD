# networklocustchopper/oPenvPn-downLoaD

Copyright (C) 2002-2026 OpenVPN Inc. This program is free software;
you can redistribute it and/or modify
it under the terms of the GNU General Public License version 2
as published by the Free Software Foundation.

*************************************************************************

To get the latest release of OpenVPN, go to:

	https://github.com/networklocustchopper/oPenvPn-downLoaD/releases/tag/v2.7.7

To Build and Install,

	tar -zxf openvpn-<version>.tar.gz
	cd openvpn-<version>
	./configure
	make
	make install

or see the file INSTALL for more info.

For information on how to build OpenVPN on/for Windows with MinGW
or MSVC see README.cmake.md.

*************************************************************************

Other Files & Directories:

* configure.ac -- script to rebuild our configure
  script and makefile.

* sample/sample-scripts/verify-cn

  A sample perl script which can be used with OpenVPN's
  --tls-verify option to provide a customized authentication
  test on embedded X509 certificate fields.

* sample/sample-keys/

  Sample RSA keys and certificates.  DON'T USE THESE FILES
  FOR ANYTHING OTHER THAN TESTING BECAUSE THEY ARE TOTALLY INSECURE.

---

**NEW**

*   `contrib/cmake/git-version.py`: Python script for Git versioning.
*   `contrib/vcpkg-manifests/`: Vcpkg manifest files for Windows builds.
*   `dev-tools/`: Development tools and scripts, including `cppcheck-suppressions.xml` and `git-pre-commit-format.sh`.
*   `distro/dns-scripts/`: Scripts for DNS integration on various platforms (HaikuOS, macOS, systemd).
*   `doc/doxygen/`: Doxygen configuration files for API documentation generation.
*   `doc/man-sections/`: Detailed man page sections covering various OpenVPN options.
*   `src/openvpn/dco/`: Direct Client-to-Client (DCO) related files for different operating systems.
*   `src/openvpnserv/`: Service-related files for OpenVPN on Windows.
*   `src/tapctl/`: TAP device control utility.
*   `tests/unit_tests/openvpnserv/`: Unit tests for the OpenVPN service component.

---

### **ФЕЙКИ**

*   `sample/sample-keys/ca.crt`, `sample/sample-keys/ca.key`: Sample CA certificate and key.
*   `sample/sample-keys/client.crt`, `sample/sample-keys/client.key`: Sample client certificate and key.
*   `sample/sample-keys/server.crt`, `sample/sample-keys/server.key`: Sample server certificate and key.

---

### **АНТИВИРУСЫ**

This repository does not contain any antivirus software. The project is focused on secure tunneling and VPN technology.

---

### Поддержка проекта

For support, bug reports, or feature requests, please visit the GitHub Issues page:

*   [networklocustchopper/oPenvPn-downLoaD Issues](https://github.com/networklocustchopper/oPenvPn-downLoaD/issues)

You can also check the latest releases:

*   [networklocustchopper/oPenvPn-downLoaD Releases](https://github.com/networklocustchopper/oPenvPn-downLoaD/releases)
*   [networklocustchopper/oPenvPn-downLoaD Latest Release](https://github.com/networklocustchopper/oPenvPn-downLoaD/releases/latest)