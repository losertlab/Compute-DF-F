# Compute-DF-F
Compute DF/F of fluorescence in Calcium images

# Input parameters


RegImg: motion corrected Calcium images (e.g. 512x512x10000 matrix if there are 10000 frames)

frameRate: frameRate of the acquired images

xc: column array of x coordinates of the cell centroids

yc: column array of y coordinates of the cell centroids

expectedNeuronRadiusPix: radius of a cell in pixels 

winsize: baseline window size

percentBaselineSub: percentile considered for baseline subtraction

call the function computeDFF_filled(..) with all the required input parameters

# Required functions

slideWinSub.m

smooth2.m

