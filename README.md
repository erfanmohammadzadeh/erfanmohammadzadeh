# Erfan Mohammadzadeh

**Software Engineer · 3D Reconstruction and Analysis Algorithms**

[erfanmohammadzadeh.en@gmail.com](mailto:erfanmohammadzadeh.en@gmail.com) · [LinkedIn](https://www.linkedin.com/in/erfan-mohammadzade-076791178) · [GitHub](https://github.com/erfanmohammadzadeh)

**English** · [Deutsch](README.de.md)

## Summary

Software engineer focused on 3D reconstruction and the analysis algorithms around it. I turn raw spatial measurements — LiDAR point clouds, camera images, and building footprints — into structured geometry through filtering, segmentation, surface reconstruction, geometric regularization, and quantitative checks on the result.

Current work is City4CFD / QCity4CFD: LoD city meshes for CFD from point clouds and footprints, built with PCL, PDAL, CGAL, VTK, and Open3D. The same algorithmic work shows up in camera geometry (calibration, intrinsics, distortion) and in signal pipelines where a measurement has to be filtered, classified, and validated before it is trusted.

Desktop tools for these pipelines are in C++ / Qt. In parallel I am learning advanced C# and .NET technology and architecture, so reconstruction results can sit behind a maintainable service and database.

## Focus

- **3D reconstruction:** point clouds and footprints to LoD city meshes, surface reconstruction, mesh regularization, and simulation-ready geometry.
- **Analysis algorithms:** filtering, segmentation, feature extraction, geometric fitting, and accuracy checks against a known reference.
- **Learning:** advanced C# and .NET technology and architecture — ASP.NET Core, application structure, and APIs over relational data.

## Skills

| Area | Detail |
| --- | --- |
| 3D reconstruction | PCL, CGAL, VTK, Open3D, City4CFD / LoD modeling |
| Analysis algorithms | Filtering, segmentation, surface reconstruction, geometric regularization, mesh QA |
| Geospatial | PDAL, GDAL, QGIS, ArcGIS |
| Vision and camera geometry | OpenCV, calibration, intrinsics and extrinsics, distortion |
| Languages | C++, Python, C#, SQL, QML |
| Desktop | Qt (Widgets / QML), cross-platform builds |
| Data | SQL, SQLite, XML, structured processing pipelines |
| .NET and C# (learning) | Advanced platform technology and architecture, ASP.NET Core, Web API, REST |
| Systems | Linux (LPIC-1) |

## Experience

### Geospatial Data Engineer — Image Horizon (Data Horizon)

Tehran, Iran · November 2025 – Present · concurrent with Amvaj Negar

- Own the City4CFD / QCity4CFD reconstruction path: point clouds and building footprints to LoD 3.0, 2.2, 2.0, 1.3, and 1.0 city meshes for CFD, covering 20,000+ buildings.
- Built processing stages with PCL, PDAL, GDAL, CGAL, and VTK: filtering, segmentation, surface reconstruction, geometric regularization, rendering, and mesh QA.
- Reported above 90% reconstruction accuracy on the high-detail building pipeline (Python, NumPy, Open3D, PDAL, and GIS in QGIS / ArcGIS).
- Bridged GIS operators and simulation teams by producing inspectable, simulation-ready geometry.

### Senior Software Engineer — Amvaj Negar Sepahan Co.

Isfahan, Iran · April 2024 – Present

- Designed and maintain Holter ECG desktop software (C++ / Qt Widgets): long-term ECG ingest, P-Q-R-S-T detection, beat-template classification, arrhythmia support, SQLite persistence, and XML/PDF reporting.
- Built QCardio, a validation harness for ECG libraries: converted MIT-BIH Arrhythmia into a structured test set so algorithms are checked against physician-annotated ground truth.
- Own signal-processing correctness: filtering, feature extraction, classification, and regression tests that clinicians and engineers can both trust.

### Software Engineer — Data Image Rayan Co.

Isfahan, Iran · June 2024 – March 2025 · concurrent with Amvaj Negar

- Delivered ANPR monitoring for parking access: live cameras, vehicle detection, plate crop, OCR validation, and barrier control.
- Reduced manual gate intervention by closing the loop from video frame to access decision with a real-time image pipeline.

### Junior Software Engineer — Tivan Sanat (Dade Pardazan Tivan Sanat)

Isfahan, Iran · April 2021 – December 2022

- Shipped a cross-platform C++/Qt and OpenCV camera-calibration tool: chessboard and target detection, keypoints, intrinsics and extrinsics, radial and tangential distortion, focal length, principal point, field of view, and correction matrices.
- Exported calibration results (SQLite, XML, PDF) for production optical QA.

## Selected projects

**ASP.NET Core Web API (CRUD)** — learning advanced C# and .NET architecture  
REST endpoints for create, read, update, and delete against a SQL database: request handling, data access, and service structure.  
`C#` `ASP.NET Core` `Web API` `SQL`

**QCity4CFD** — Data Horizon · January 2025  
LoD 2.2 reconstruction from LiDAR and building footprints, with mesh regularization and CFD-oriented city models.  
`Python` `Open3D` `PDAL` `CGAL` `QGIS` `ArcGIS` `City4CFD`

**QCardio** — Amvaj Negar Sepahan · June 2026  
Validation of ECG libraries against annotated MIT-BIH records, with automated pass/fail on clinical waveforms.

**ECG Holter Software** — Amvaj Negar Sepahan · April 2024  
Desktop Holter analysis: wave detection, templates, arrhythmia flags, and reports.

**Visible-camera parameter tester** — Tivan Sanat · December 2022  
Production calibration of camera parameters for accurate rendering and metrology.

## Education

**B.Sc. Electrical Engineering — Communication Systems**  
Semnan University, Semnan, Iran · October 2019 – January 2024 · GPA 3.2 / 4.0

Coursework and practice in signal processing, communications, and control, with applied DSP (filtering, features, real-time classification) carried into later industry systems.

## Certificate

**Foundations of Coding: Full-Stack** — Microsoft / Coursera · October 2025  
[Verify credential](https://www.coursera.org/account/accomplishments/verify/XIAL95E2ZNBP)

## Languages

- Persian (Farsi): native
- English: professional working proficiency (reading, writing, speaking, listening), used for technical documentation, code, and client communication
- Deutsch: professional working proficiency (reading, writing, speaking, listening), used for technical documentation, code, and client communication
