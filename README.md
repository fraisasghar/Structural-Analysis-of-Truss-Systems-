


<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1e3c72,100:0f9b8e&height=200&section=header&text=Truss%20Analysis&fontSize=48&fontAlign=50&fontAlignY=55&animation=fadeIn&fontColor=ffffff&desc=Method%20of%20Joints%20|%20Static%20Equilibrium%20|%20ANSYS%20Verification&descAlign=50&descAlignY=88&descSize=18&descColor=dbe9ff&shadow=true" alt="Header" />
</div>

<h3 align="center">Design, Analysis, and Simulation Verification of a Statically Determinate Planar Truss</h3>

<div align="center">
  <img src="https://img.shields.io/badge/Subject-Engineering%20Statics-8B0000?style=for-the-badge&logo=bookstack&logoColor=white" />
  <img src="https://img.shields.io/badge/Method-Method%20of%20Joints-1E3A8A?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Verification-ANSYS%20Workbench-FF8C00?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Load-300N%20Horizontal-006400?style=for-the-badge" />
</div>



<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:1e3c72,100:0f9b8e&height=2">

<div align="center">

[![Intro](https://img.shields.io/badge/-Introduction-12141a?style=flat-square)](#introduction)
[![Stats](https://img.shields.io/badge/-Snapshot-12141a?style=flat-square)](#project-snapshot)
[![Geometry](https://img.shields.io/badge/-Geometry-12141a?style=flat-square)](#geometry--loading)
[![Equations](https://img.shields.io/badge/-Equations-12141a?style=flat-square)](#governing-equations)
[![FBD](https://img.shields.io/badge/-Free_Body_Diagrams-12141a?style=flat-square)](#joint-by-joint-free-body-diagrams)
[![Results](https://img.shields.io/badge/-Results-12141a?style=flat-square)](#support-reactions)
[![Validation](https://img.shields.io/badge/-Validation-12141a?style=flat-square)](#manual--ansys-validation)
[![Timeline](https://img.shields.io/badge/-Timeline-12141a?style=flat-square)](#project-timeline)
[![Repo](https://img.shields.io/badge/-Repository-12141a?style=flat-square)](#repository)

</div>

<br>

## <img src="https://api.iconify.design/mdi/information-slab-circle-outline.svg?color=%234fc3f7" width="24" height="24" valign="middle"/> Introduction

<p align="center" style="max-width: 800px; margin: 0 auto; text-align: center;">
This project presents the static analysis of a five-member, four-joint planar truss, solved analytically using the method of joints and independently verified through finite-element simulation in ANSYS Workbench. The truss is supported by a roller at joint A and a pin at joint C, with a 300 N horizontal load applied at the apex joint D, its magnitude derived directly from a team member's CMS registration number. Working through equilibrium of the whole structure and then joint-by-joint, the reactions and all five internal member forces were calculated by hand, identifying members AD and CD as the critical tension and compression members at 212.13 N, members AB and BC carrying 150 N each, and BD as a true zero-force member. The same geometry and loading were then rebuilt in ANSYS Static Structural, and the simulated axial force distribution matched the hand calculations almost exactly, with a maximum of 212.13 N and a minimum of -212.13 N. This close agreement between the manual and simulated results confirms both the correctness of the equilibrium approach and the reliability of the finite-element model, illustrating how classical hand analysis and modern simulation tools reinforce one another in real structural engineering practice.
</p>

<br>


<div align="center">
<img width="700" alt="Screenshot 2026-08-10 183852" src="https://github.com/user-attachments/assets/7d465ddd-81c6-4072-b77f-0f4f812e0990" />
</div>
<br>


![Architecture](assets/architecture.svg)



## <img src="https://api.iconify.design/mdi/ruler-square-compass.svg?color=%234fc3f7" width="22" height="22" valign="middle"/> Geometry & Loading

![Truss Geometry](assets/geometry.svg)

<br>

## <img src="https://api.iconify.design/mdi/function-variant.svg?color=%232dd4bf" width="22" height="22" valign="middle"/> Governing Equations

![Equations](assets/equations.svg)

<br>

## <img src="https://api.iconify.design/mdi/vector-polyline.svg?color=%23ffb84d" width="22" height="22" valign="middle"/> Joint-by-Joint Free-Body Diagrams

![Free Body Diagrams](assets/free_body.svg)

<br>



## <img src="https://api.iconify.design/mdi/vector-line.svg?color=%23ff8a3d" width="22" height="22" valign="middle"/> Internal Member Forces

![Internal Forces](assets/forces.svg)

<br>

## <img src="https://api.iconify.design/mdi/check-decagram-outline.svg?color=%235ee6a0" width="22" height="22" valign="middle"/> Manual &harr; ANSYS Validation

![Verification](assets/verification.svg)

<br>

![Comparison Chart](assets/comparison_chart.svg)

<br>

## <img src="https://api.iconify.design/mdi/clock-time-four-outline.svg?color=%23ff5a5a" width="22" height="22" valign="middle"/> Project Timeline

![Timeline](assets/timeline.svg)

<br>

## <img src="https://api.iconify.design/mdi/map-marker-path.svg?color=%23ffb84d" width="22" height="22" valign="middle"/> Roadmap

![Roadmap](assets/roadmap.svg)

<br>

## <img src="https://api.iconify.design/mdi/folder-open-outline.svg?color=%239aa0a8" width="22" height="22" valign="middle"/> Repository

| File | Description |
|:--|:--|
| `Project_Report.pdf` | Full IEEE-format lab report |
| `Project_Presentation.pptx` | Presentation slides |
| `assets/` | Diagram source files (SVG) |


<div align="center">

</br>

<div align="left">
Autor: Frais Asghar
  <br>
National University of Sciences &amp; Technology (NUST) SMME
</div>

</br>

<div align="center">
If this project was useful to you, consider giving it a star. ⭐
  
<p2 align="center"><sub>Built for the Mechanical & Simulation community &nbsp;&middot;&nbsp; Happy building</sub></p2>
</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:1e3c72,100:0f9b8e&height=2">
