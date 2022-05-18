# PCPD

## Research Paper

We present the findings of this work in the following research paper:

**Package Cache Poisoning: A Covert Supply Chain Attack Targeting the Python Community**

### Introduction

As large software development processes shift from writing code from scratch to building with reusable packages, the package management ecosystem for each development language is maturing. Python is the most popular language among developers today, and the security of its package repository PyPI is relevant to the security of many software ecosystems. PyPI allows any registered member to publish their packages easily within the open-source spirit. However, Attackers target this convenient feature and disguise themselves as developers to distribute malicious packages. Aiming to estimate the current situation of packages in the whole PyPI and the overall security of the Python community, we propose a set of package behavior judgment rules to judge the maliciousness of packages after analyzing the PyPI packages' life cycle and attackers' intentions. We present a framework for package cache poisoning detection (named PCPD), which combines static anomaly detection and dynamic running analysis to detect lurking packages with malicious behavior based on the rules. After manual reviewing, PCPD found 101 packages with malicious behavior and 523 packages with suspicious behavior. We made these malicious package samples publicly available for security researchers to use to help improve the security of the Python community. Besides, we provide appropriate security recommendations for each role that appears in the PyPI packages' life cycle to help improve their security awareness and defend against software supply chain attacks.

### Directory

* IIExtractor: complete Installation&Import code slicing method for PyPI packages.
* Packages: packages with malicious and suspicious behavior.

### Reference

When the paper is published, you can use the reference.

### Notice

If you would like to use IIExtractor or the packages we found, please contact us using your institutional email to get the password.
