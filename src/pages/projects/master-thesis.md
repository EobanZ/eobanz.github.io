---
layout: "../../layouts/MarkdownProjectLayout.astro"
title: Master Thesis
subtitle: Native Co-Location Plugin for Unity
short_description: "As part of this master's thesis (grade: 1.0), a native plugin was developed (C++) that enables the creation of co-located applications for devices with inside-out tracking (e.g., Meta Quest). A new calibration method is used, which utilizes the guardian of an XR device for transformation determination."
project_repo_link: 
preview_image_url: "/project_assets/master/master_transf.png"
files: [ {"title", "path"}]
techstack: ["c++", "CMake", "Unity", "Meta Quest"]
priority: 100
---

# Abstract

Current solutions for creating co-located VR applications typically rely on synchronizing platform-specific spatial anchors or shared SLAM data, which are often tied to cloud services. These solutions require either access to the camera images or the collected SLAM data, which some VR headsets prohibit. Therefore, in this work, two well-known calibration methods are derived and extended in an engine-independent manner, and a completely new method for solving the co-location problem is presented, which is applicable to all XR devices with spatial memory. The work describes how these methods were implemented in a predominantly natively developed toolkit and made available to developers through a Unity package. Additionally, various aspects of the toolkit, such as the usability of the methods, the algorithms used, and the resulting positional error, are evaluated.

Current solutions for creating co-located VR applications typically rely on synchronizing platform-specific spatial anchors or shared SLAM data, which are often tied to cloud services. These solutions require either access to the camera images or the collected SLAM data, which some VR headsets prohibit. Therefore, in this work, two well-known calibration methods are derived and extended in an engine-independent manner, and a completely new method for solving the co-location problem is presented, which is applicable to all XR devices with spatial memory. The work describes how these methods were implemented in a predominantly natively developed toolkit and made available to developers through a Unity package. Additionally, various aspects of the toolkit, such as the usability of the methods, the algorithms used, and the resulting positional error, are evaluated.
