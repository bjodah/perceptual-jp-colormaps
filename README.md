
# perceptual-jp-colormaps  
  
A perceptually uniform colormap generator for Matplotlib equipped with traditional-ish Japanese colors to serve as a fixed color palette.   
(Culture appropriation at its finest.) Additions are welcomed.  

Why perceptually uniform colormaps? Can you not just use default Matplotlib colormaps?   
- non-perceptually uniform colormaps induce dangerous artifacts, as seen in the below image: ![top-view of pyramid](https://i.stack.imgur.com/JcTDb.png).
The left colormap introduces new features to the data.
- Matplotlib perceptually uniform colormaps are not visually appealing and sometimes lack enough contrast.
With this package, anyone can design colormaps to fit their visual style.

dependencies:  
	Python3:  
		colour-science  
		numpy  
		logging  
		scipy  
		json  
		pynverse  
		matplotlib  
  
tested on:  
	Windows 10  
  
expected to work on:  
	Linux  
	MacOS  
  
run generator:   
    `python3 gen.py` or `python3 gen.py --readme`

load colormaps:
    add load.py and the maps/cmaps.txt to your code.
    load.jpcm_load() will return a dictonary containing all the colormaps

## gallery  

![](https://github.com/akhilsadam/perceptual-jp-colormaps/blob/master//maps/def.png?raw=true) ![](https://github.com/akhilsadam/perceptual-jp-colormaps/blob/master//maps/def_segmented.png?raw=true)  
![](https://github.com/akhilsadam/perceptual-jp-colormaps/blob/master//maps/ice.png?raw=true) ![](https://github.com/akhilsadam/perceptual-jp-colormaps/blob/master//maps/ice_segmented.png?raw=true)  
![](https://github.com/akhilsadam/perceptual-jp-colormaps/blob/master//maps/iron-ice.png?raw=true) ![](https://github.com/akhilsadam/perceptual-jp-colormaps/blob/master//maps/iron-ice_segmented.png?raw=true)  
![](https://github.com/akhilsadam/perceptual-jp-colormaps/blob/master//maps/water.png?raw=true) ![](https://github.com/akhilsadam/perceptual-jp-colormaps/blob/master//maps/water_segmented.png?raw=true)  
![](https://github.com/akhilsadam/perceptual-jp-colormaps/blob/master//maps/momiji.png?raw=true) ![](https://github.com/akhilsadam/perceptual-jp-colormaps/blob/master//maps/momiji_segmented.png?raw=true)  
![](https://github.com/akhilsadam/perceptual-jp-colormaps/blob/master//maps/sky.png?raw=true) ![](https://github.com/akhilsadam/perceptual-jp-colormaps/blob/master//maps/sky_segmented.png?raw=true)  
![](https://github.com/akhilsadam/perceptual-jp-colormaps/blob/master//maps/sunburst.png?raw=true) ![](https://github.com/akhilsadam/perceptual-jp-colormaps/blob/master//maps/sunburst_segmented.png?raw=true)  
![](https://github.com/akhilsadam/perceptual-jp-colormaps/blob/master//maps/flamingo.png?raw=true) ![](https://github.com/akhilsadam/perceptual-jp-colormaps/blob/master//maps/flamingo_segmented.png?raw=true)  
![](https://github.com/akhilsadam/perceptual-jp-colormaps/blob/master//maps/tree.png?raw=true) ![](https://github.com/akhilsadam/perceptual-jp-colormaps/blob/master//maps/tree_segmented.png?raw=true)