# Curved-Surface Pattern Defect Inspection: Ten Lectures on an Industrial-Grade System

A technical series on curved-surface pattern defect inspection, written from the perspective of geometric structure, defect measurement, and deployable industrial system design.

**Website:** https://monge-ampere.github.io/curved-surface-pattern-inspection/

## About

This repository hosts a multi-part technical series on curved-surface pattern defect inspection.

Rather than treating the subject as ordinary character recognition, simple template matching, or generic defect classification, the series approaches it as an industrial vision problem involving:

- geometric deformation,
- structural normalization,
- template organization,
- registration and measurement,
- configuration-driven reuse,
- multithreaded execution,
- plugin-based extension,
- and deployment under real production constraints.

The discussion is based on a core inspection system developed in 2020 and deployed at scale on Apple AirPods-related production lines from 2021 to 2023.

## What this series aims to do

The goal of this site is not to present scattered project notes, but to reconstruct a real industrial inspection system as a coherent technical object. In particular, the series tries to make explicit:

- what problem the system actually solves,
- how templates, XML, blocks, and geometric anchors are organized,
- how registration and measurement are coupled,
- how defect decisions are produced from aligned measurement sets,
- how routing, multithreading, plugins, and AI modules are integrated,
- and why industrial productization depends on more than algorithms alone.

## Topics covered

The series includes topics such as:

1. why this system is worth explaining systematically,
2. why curved-surface pattern inspection is not ordinary OCR,
3. how XML organizes templates, topology, tolerance, and structural roles,
4. how the two-layer registration mechanism works,
5. how defects are measured after template alignment,
6. how configuration routing, multithreading, and implementation support industrial deployment,
7. why template creation is itself a production chain,
8. why some ROI regions must be explicitly excluded from detection,
9. how plugins and AI modules extend the main inspection pipeline,
10. why an almost productized industrial algorithm system can still fall short at the organizational level.

## Language

Most articles are written in Chinese.  
English titles and abstracts are provided for many posts.

## Author

**Wei Feng**  
Geometric Algorithm Engineer

Email: weifeng@stu.ouc.edu.cn
