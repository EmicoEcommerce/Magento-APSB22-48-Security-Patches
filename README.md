# Security patches for APSB22-48

This repository contains Magento 2 Patch Files for the recently found security issues on 12-10-2022.
The patch files aim to fix the CVE-2022-35698 and CVE-2022-35689 vulnerabilities.

There is not much information about the exact fix which has been released in the newly released patch versions of Magento. 
To create these patch files we've tried our best to inspect the [2.4.4-p1...2.4.4-p2 diff](https://github.com/magento/magento2/compare/2.4.4-p1...2.4.4-p2.diff) and extract the possible security fixes which seems to be in the Magento template directives.

**We're still analyzing the released patch and are in no means sure that these patches cover the entire solution for the newly found security vulnerabilities, use at your own risk.**

## Installation

Use a package such as [Composer Patches](https://github.com/cweagans/composer-patches) to apply the correct patch file to your Magento shop.
The patches are to be applied to the `magento/framework` package.
The correct patch file can be found within the folder corresponding to your Magento 2 version.