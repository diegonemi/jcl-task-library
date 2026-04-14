# JCL Special Cases Repository

## Overview
This repository contains a curated collection of special JCL routines designed for specific tasks in mainframe environments. It showcases dataset manipulation, GDG management, VSAM cluster operations, and compilation processes for COBOL, CICS, DB2, and BMS maps. The goal is to provide practical examples and reusable scripts for exceptional scenarios.

## Routines Included
JCLMOD01 - Copies a dataset and modifies a decimal field to COMP-3 format  
JCLMOD02 - Creates a GDG (Generation Data Group) dataset  
JCLMOD03 - Generates a VSAM cluster and copies data from the source to the new cluster  
JCLMOD04 - Renames a VSAM dataset  
JCLMOD05 - Deletes a GDG dataset  
JCLMOD06 - Creates a complete VSAM cluster with indexes  
COMPICOB - Compiles COBOL programs  
COMPIDB2 - Precompiles and compiles COBOL programs with DB2  
BINDESTU - Performs bind between COBOL program and DB2 database  
COMPCICS - Compiles COBOL programs with CICS  
COMPMAPA - Compiles BMS maps  

## Usage
Each routine is provided as a standalone JCL script. They can be adapted to specific environments by modifying dataset names, job cards, and system parameters. Documentation in the `docs/` folder explains prerequisites and execution notes.

## Purpose
This repository serves as a reference library for mainframe professionals, offering ready-to-use JCL examples for uncommon or specialized tasks. It is part of Diego Nemirovsky’s portfolio of mainframe and COBOL projects.
