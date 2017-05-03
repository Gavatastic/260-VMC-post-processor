Fusion 360 post-processor for use with 260 VMC mill

Based on Generic Boxford post-processor created by Autodesk. Modifications made by Reading Hackspace.
Use at own risk after you have ascertained that it will not hamr you or your machine

The modifications:
- create a 260 VMC specific header with stock dimensions taken from Fusion, and Z offset for tool from user
- adds options to suppress generation of the following G-code commands - G28, G43, G54, G91, G94, M8 and M9
- errors out when asked to create xz or yz arc movements (G02, G03) as not supported by mill
- forces zeroes for I and J for G02 and G03 arc commands


