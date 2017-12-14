Distance Depth of Field Notes:

The idea behind the technique is to blur out the regions(pixels) that are not in the camera focus.
The implemented technique is a very simple approach to accomplish that.The major thing to note is that the current implementation is not an apt way to blur foreground while some background is in focus. Doing this will cause ringing/banding artefacts in the foreground objects and hard silhouettes. The other way works though i.e foreground in focus while background blurred.
https://developer.nvidia.com/gpugems/GPUGems3/gpugems3_ch28.html -- article to get the foreground blur working.
