# Satellite-Cloud-Detection
Goal
Task: semantic segmentation of clouds and optionally cloud shadow in Landsat imagery
Input: selected Landsat multispectral bands
Target: binary or multiclass mask derived from QA_PIXEL
Challenge: QA_PIXEL is not perfect ground truth; it is a rule-based quality layer, so your model is learning from noisy labels rather than from hand-annotated masks. USGS documents QA_PIXEL as a quality assessment band containing cloud-mask-related information and bit flags.
