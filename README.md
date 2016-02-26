# FreesurferSurfacePlotting

This ipython notebook is supposed to act as a basic tutorial for using freesurfer for surface extraction. As I do not own any rights regarding any of the functions nor data, please relate to the provided links and instructions which you can find there. 
Please refer to https://github.com/juhuntenburg

## Introduction
This was created during the 2016 Brainhack in Paris, where I run into some issues with projecting statistical volume maps from fMRI analysis onto brain surfaces. The initial goal was to provide an example for the nilearn plot_surf_stat_map function using simple statistical maps in MNI space. This was more complex than expected, so this tutorial was created for those who just want to plot their brain analysis results onto a pretty surface. 

## Scope of the tutorial
* Register your T1 map onto fsaverage
* Create a mesh file of the surface and import it into freesurfer
* Plot the mesh 
* Extract different fsaverage surfaces for visualization
* Small example of nilearns plotting functions
