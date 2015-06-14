# Neurotools
A couple of Matlab scripts for SPM5 / SPM8. This code is not maintained anymore by the author.

## Project Website

- [Neurotools](http://aimfeld.ch/neurotools/neurotools.html)

## spmbatch v3.3

spmbatch (former spm5batch) creates and runs SPM-jobs for multiple subjects by replacing paths in a given template-job. 
Jobs on the first level (single subject) are supported, e.g. preprocessing of fMRI data, first-level statistics, 
image calculator, check registration, jobs with external SPM toolboxes.

## dicom2nifti v3.1

dicom2nifti converts DICOM-files (.dcm) to NIfTI-files (.nii or .img/.hdr). A specified directory and its subdirectories 
are searched for DICOM-files. These files will then be converted to NIfTI format using SPM functions. The NIfTI-files will 
be properly named, moved to a target-directory and sorted in subdirectories according to their type (anatomical, functional, 
or DTI).

 ## log_roi_batch v2.0

log_roi_batch creates tables of mean or standard deviation for regions of interest (ROIs) or counts voxels with values within 
a given range. Voxel exclusion criteria can be specified, which can also be used to count the number of included or excluded 
voxels within a given value range.
