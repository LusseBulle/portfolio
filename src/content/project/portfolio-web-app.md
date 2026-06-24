---
title: "Portfolio Web App (Python/Flask)"
description: "Built a dynamic portfolio system from scratch using Python, Flask, and a custom JSON-backed data layer."
pubDate: Oct 13 2023
role: "Co-Developer (Pair Project)"
tags:
  - python
  - flask
  - html-css
  - university
---

## Overview
As my [initial project](https://www.ida.liu.se/~TDP003/2023/index.sv.shtml) at Linköping University, we developed a custom, dynamic portfolio website from the ground up. The goal was to build a complete system to document and display future academic projects, focusing on separation between data management and presentation.

### Architecture & Implementation
To build the application, we implemented a two-layer architecture:
* **Data Layer:** Rather than using a traditional database, we built an API in Python that interfaced with a local JSON datastore. This module handled data retrieval, searching, and complex multi-field filtering without requiring server restarts.
* **Presentation Layer:** We utilized Python's Flask framework alongside Jinja2 templating to dynamically generate HTML5 and CSS3 views. 

### Key Features
* **Dynamic Routing:** Implemented dynamic endpoints to handle the main gallery, individual project detail pages, and a dedicated "techniques" aggregator.
* **Advanced Search & Filtering:** Built a search engine capable of querying arbitrary project data. It supports concurrent multi-field searching, technique-based filtering, and bidirectional sorting.
* **Error Handling:** Designed user-friendly error catching and routing.

### Results
Building this system provided a practical understanding of core web mechanics, RESTful API design, and the importance of separating backend logic from frontend views.