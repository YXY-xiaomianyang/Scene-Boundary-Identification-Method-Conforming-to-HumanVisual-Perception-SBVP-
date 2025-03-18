## Scene Boundary Conformed to Visual Perception (SBVP)
Overview  
This repository provides the Python implementation of the Scene Boundary Visual Perception (SBVP) method, a novel approach designed to identify scene boundaries in remote sensing images that conform to human visual perception. SBVP is a simple yet effective solution for delineating clear scene boundaries, offering broad applicability in remote sensing and geographic studies.

Key Features  
Human Visual Perception Alignment: SBVP identifies scene boundaries that comform to human visual perception, rather than being constrained by individual object edges.

Two-Stage Segmentation  
Upscaling Segmentation: Guided by the image's average state, SBVP performs initial scene target segmentation.
Superpixel Segmentation: Refines object-level details for precise boundary delineation.

Broad Applicability  
SBVP has been successfully applied to tasks such as suspicious target detection and the delineation of arid-humid and global biogeographical boundaries.

Performance  
Experimental results demonstrate that SBVP outperforms traditional methods like eCognition and state-of-the-art deep learning models like Segment Anything Model (SAM):
Achieves a mean IoU of 0.90, representing a 20% improvement over eCognition and a 23% improvement over SAM (P < 0.01).
