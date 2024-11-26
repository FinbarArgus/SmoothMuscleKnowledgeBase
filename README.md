# SmoothMuscleKnowledgeBase
This repo is a place for storing knowledge, models, and data of smooth muscle cells

# Format for directories

- SmoothMuscleKnowledgeBase_dir
  - Data
  - Models

# Format for this Readme

Please include citations as {FirstAuthorLastName}{year}{PaperFirstBigWord}. For example \cite{Davis2023tight} for \newline

Davis, Harvey, and David Attwell. "A tight squeeze: how do we make sense of small changes in microvascular diameter?." The Journal of physiology 601.12 (2023): 2263-2272.\cite{herna}

The citations should be uploaded to this shared Zotero library (https://www.zotero.org/groups/smoothmusclerefs).
\newline
Citation information should be included in the following manner (Please offer improvements below if you think this format could be improved).

{Citation: FirstAuthorLastNameXXXXPaperFirstBigWord  
Type: Choose from [Modelling paper, experimental results, review]  *Include more types if neccesary*
Animal: the animals that the experiments are done on or the animals that the model is replicating.
ModelLanguage: CellML or Matlab or etc.  
SI units: True or False if the units are in SI or not.
CellType: choose from [vascular smooth muscle, airway smooth muscle, uterine smooth muscle, gut smooth muscle, other smooth muscle]  
Location: what organ or location of the body this dataset is from or which location the model is based on.  
ExperimentInfo: (For experimental results) Detail the inputs and outputs of each result (normally each figure) in the paper. For example for an experiment that varied input current and compared baseline to isoproterenol application and measured voltage with whole cell patch-clamp and Calcium with FRET...  
{inputs: current, isoproterenol,  
 output: voltage, Calcium,  
 methods: whole-cell patch clamp, FRET (Calcium)} (Include one bracketed entry for each experiment in the paper.)  
 dataAvailability: choose from [open, request, private]  
 dataLocation: data/FirstAuthorLastNameXXXXPaperFirstBigWord If the data is open, save it in a directory of this format and specify it here.}}  






