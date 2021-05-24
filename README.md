# Awesome Janelia Software

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome software actively maintained at Janelia. Inspired by various [awesome](https://github.com/sindresorhus/awesome) lists.

### Contributing

Please read the [contribution guidelines](CONTRIBUTING.md).

### GitHub Organizations

* [Branson Lab](https://github.com/kristinbranson)
* [FlyEM](https://github.com/janelia-flyem)
* [FlyEM NeuPrint](https://github.com/connectome-neuprint)
* [Funkey Lab](https://github.com/funkey)
* [Preibisch Lab](https://github.com/PreibischLab)
* [Saalfeld Lab](https://github.com/saalfeldlab)
* [Scientific Computing Software](https://github.com/JaneliaSciComp)
* [Stringer Lab](https://github.com/MouseLand)
* [Turaga Lab](https://github.com/TuragaLab)


## Behavior Tracking

*Computer vision tools for animal behavior*

* [APT](https://github.com/kristinbranson/APT) - Animal Part Tracker
* [JAABA](https://github.com/kristinbranson/JAABA) - Janelia Animal Behavior Detector 


## Containerization

*Tools for containerization and running containers (e.g. using Docker and Singularity)*

* [Entrypoints](https://github.com/JaneliaSciComp/entrypoints) - add multiple entrypoints into a Docker container
* [Maru](https://github.com/JaneliaSciComp/maru) - command-line tool for containerizing scientific applications


## Dask Ecosystem

*Image processing in the Dask/Python ecosystem*

* [dask-janelia](https://github.com/JaneliaSciComp/dask-janelia) - Library for running Dask on the Janelia cluster
* [xarray-multiscale](https://github.com/JaneliaSciComp/xarray-multiscale) - Library for generating multiscale pyramids with Dask

## Data Services

*Systems for handling scientific data on the web or through APIs*

* [DVID](https://dvid.io) - A Connectomics data service that supports branched versioning of data and a variety of storage backends
* [Clio](https://github.com/clio-janelia) - Software for a Connectomics website with a serverless data API service

## End-User Applications

*Scientific applications with GUIs and user manuals*

* [HippoSeq](https://hipposeq.janelia.org) - Interactive analysis tool for RNA-seq data in the mouse hippocampus
* [Janelia Workstation](https://github.com/JaneliaSciComp/workstation) - Discovery platform supporting the FlyLight and MouseLight projects
* [neuPrint+](https://neuprint.janelia.org) - Analysis tools for connectomics
* [NeuronBridge](https://neuronbridge.janelia.org) - EM/LM correspondence searches
* [NeuroSeq](https://neuroseq.janelia.org) - Interactive analysis tool for RNA-seq data in the mouse
* [NeuTu](https://janelia-flyem.gitbook.io/neutu) - Software package for neuron reconstruction and visualization 
* [RAISIN](https://raisin.janelia.org) - Web site for *Rabies-Assisted Interrogation of Synaptic Infralimbic Networks*
* [VVD Viewer](https://github.com/JaneliaSciComp/VVDViewer) - Interactive 3D volume viewer for large microscopy data


## Fiji Plugins

*Plugins for [Fiji](https://fiji.sc)*

* [BigStitcher](https://github.com/PreibischLab/BigStitcher) - ImgLib2/BDV implementation of Stitching for large datasets
* [ColorMIP Mask Search](https://github.com/JaneliaSciComp/ColorMIP_Mask_Search) - Fiji plugin for color depth search
* [H5J Loader](https://github.com/JaneliaSciComp/H5J_Loader_Plugin) - Fiji plugin for loading images in lossy H5J format
* [n5-ij](https://github.com/saalfeldlab/n5-ij) - Fiji plugin for loading and saving image data as N5 data sets


## High Performance Computing 

*Libraries and APIs for high-performance scientific computing on clusters and clouds.*

* [Burst Compute](https://github.com/JaneliaSciComp/burst-compute) - AWS service for highly parallel Lambda processing
* [Daisy](https://github.com/funkelab/daisy) - Block-size task scheduling for large volumes
* [JACS](https://github.com/JaneliaSciComp/jacs-compute) - RESTful services for running jobs at scale
* [Java LSF](https://github.com/JaneliaSciComp/java-lsf) - Java library for interacting with an HPC compute cluster running IBM Platform LSF


## Machine Learning

*Libraries for training and applying machine learning models*

* [Cellpose](https://github.com/MouseLand/cellpose) - Deep learning tool for cell segmentation 
* [DECODE](https://github.com/TuragaLab/DECODE) - Deep learning tool for single molecule localization microscopy (SMLM)
* [Gunpowder](https://github.com/funkey/gunpowder) - Library for machine learning on multi-dimensional images


## N5 Ecosystem 

*Image processing tools in the N5/[Imglib2](https://github.com/imglib/imglib2) ecosystem*

* [N5](https://github.com/saalfeldlab/n5) - n5 file format
* [N5 Spark](https://github.com/saalfeldlab/n5-spark) - Tools for working with N5 on a Spark cluster
* [N5 Viewer](https://github.com/saalfeldlab/n5-viewer) - Viewer for visualizing N5 data sets
* [Render](https://github.com/saalfeldlab/render) - RESTful services for large image transformation and rendering
* [Stitching Spark](https://github.com/saalfeldlab/stitching-spark) - Reconstruct large images from overlapping tiles on a Spark cluster


## Nextflow Pipelines

*Containerized analysis pipelines that run anywhere.*

* [EASI-FISH Pipeline](https://github.com/JaneliaSciComp/multifish) - for spatial transcriptomics using EASI-FISH
* [ExM Pipeline](https://github.com/JaneliaSciComp/expansion-microscopy-pipeline) - Pipeline for analyzing ExM data with neuron/synapse segmentation
* [Nextflow Spark](https://github.com/JaneliaSciComp/nextflow-spark) - library for including Spark clusters as part of a Nextflow pipeline


## 3D Visualization

*Tools and libraries for 3D visualizations*

* [Blender Spherical Video](https://github.com/JaneliaSciComp/blender-spherical-video) - Scripts for rendering 360-degree spherical videos in Blender
* [Janelia Unity Toolkit](https://github.com/JaneliaSciComp/janelia-unity-toolkit) - Unity game engine packages enabling animal studies in VR
* [neuVid](https://github.com/connectome-neuprint/neuVid) - Generate connectome videos from high-level descriptions using Blender


## License

[![CC0 1.0 Universal (CC0 1.0) Public Domain Dedication ](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
This work is licensed under a [CC0 1.0 Universal (CC0 1.0) Public Domain Dedication](https://creativecommons.org/publicdomain/zero/1.0/).

