The idea is to create perceptually correct soft shadows that don't look bad.
This prototype implementation of PCSS works but there are some areas that need improvement.

1. The one bug that I visually notice is the overall colour lighten when PCSS is used.
2. Another thing that can use improvement is the filtering itself. Currently I am using a custom 32 tap Poisson kernel. And the results are moderately good. If I increase the light size, I quickly start seeing ringing artefacts in my penumbra. GTA5's PCSS filtering looks better.
https://international.download.nvidia.com/geforce-com/international/comparisons/grand-theft-auto-v/grand-theft-auto-v-soft-shadows-interactive-comparison-1-nvidia-pcss-vs-amd-chs.html
3. There are other minor things that are mentioned in the comments that need to be changed.
