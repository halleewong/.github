# Dalcalab Projects and Libraries

## Research Projects
Sometimes these double as a general toolbox, like `voxelmorph`.

 - [VoxelMorph](http://voxelmorph.net/)  
We introduced learning-based image registration/alignment, including VoxelMorph, [SynthMorph](https://martinos.org/malte/synthmorph/), AtlasMorph, [HyperMorph](https://hypermorph.voxelmorph.net/), etc, and general utilities.  
- **Synth***  
In our Synth* line of work we develop a procedural data generation engine to produce synthetic training data that yields methods generalizing reliably across scanners, contrasts, populations, and even modalities.
This includes [SynthMorph](https://synthmorph.io/), [SynthSeg](https://surfer.nmr.mgh.harvard.edu/fswiki/SynthSeg), [SynthStrip](https://surfer.nmr.mgh.harvard.edu/docs/synthstrip/), [BabySeg](http://babyseg.io/), [Anatomix](https://www.neeldey.com/anatomix/)
- Automatic segmentation of new data at scale  
We've spearheaded methods for automatic segmentation of new domains/images/regions in new datasets. These include [ScribblePrompt](https://github.com/halleewong/ScribblePrompt)  
Interactive medical image segmentation with bounding boxes, clicks and scribbles, [UniverSeg](https://github.com/JJGO/UniverSeg) -- Universal Medical Image Segmentation from new examples without re-training,  - [MultiverSeg](https://github.com/halleewong/MultiverSeg)  -- Scalable interactive segmentation of biomedical imaging datasets with in-context guidance, [tyche](https://tyche.csail.mit.edu/) -- multi-rater segmentation at scale, etc  
 - [Topofit](https://github.com/ahoopes/topofit)  
Learning-basedfitting of surfaces to cerebral cortex in brain MRI
 - [Thunderpack](https://github.com/JJGO/thunderpack)  
Blazingly fast multi-modal data format
 - [Hyperlight](https://github.com/JJGO/hyperlight)  
Hypernetworks in Pytorch made easy

## Useful libraries
Libraries with tools offering support to the sort of research we do

### Pytorch

 - [voxel](https://github.com/dalcalab/voxel)  
`torch`-focused general purpose medical volume processing
 - [neurite](https://github.com/adalca/neurite)  
medical image analysis, mostly in `tensorflow`/`keras` for now.  
Related more experimental library: [neurite-sandbox](https://github.com/adalca/neurite-sandbox) 
 - [voxynth](https://github.com/dalcalab/voxynth)  
Synthesizing voxel data, based on the generative modeling in SynthSeg, SynthMorph, SynthStrip, etc
 - [BatchAug](https://github.com/halleewong/batchaug)  
Batched GPU augmentations for 3D medical images, replacing MONAI's per-sample transforms with fused Triton kernels
 
### Data 
 - [teramedical](https://github.com/teramedical/teramedical)  
large-scale medical data processing library, with dataset-specific processing [in conjunction with [Sabuncu Lab at Cornell](https://sabuncu.engineering.cornell.edu/research/)]
 - [daldata](https://github.com/teramedical/teramedical)
internal library for quickly loading/handling data for torch-based ML projects

### Other public 
 - [surfa](https://github.com/freesurfer/surfa)  
General purpose medical image handling and volume processing (general/non-DL)


## Non-Python libraries

 - [matlib](https://github.com/adalca/matlib)  
extensive `matlab` general purpose libraries

# Internal resources

 - [resources](https://github.com/dalcalab/resources)
lab resources (internal datasets, etc)
 - [idealab](https://github.com/dalcalab/idealab)
light jupyters on ideas and tutorials
 - [dalcalab_resources](https://github.com/dalcalab/resources)  
[name TBD?] internal easy-access resources, including `data` and `model` supporting utilities, for the dalcalab
