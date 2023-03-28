# PS-OCT Vessel Graphing
Suite of tools for segmenting vessels from PS-OCT images and then converting the segments to a graph.

To Do:
nodeGrps_vesSegment.m function
- Bugfix: there is a zero indexing issue in function nodeGrps_vesSegment.m This occurs when running "verification > get segment info > update"
- This function has hard-codd the pixel size to be 2um (hxy = 2; hz = 2;). This script sets the variable "segLen_um" in the Graph.segInfo struct based upon this hard-coded pixel size. This function needs to take pixel size as an input.
