
<!-- MarkdownTOC autolink="true" -->

- [Introduction](#introduction)
- [Examples](#examples)
	- [Grayscale](#grayscale)
		- [Example 1](#example-1)
		- [Example 2](#example-2)
	- [Interpreter](#interpreter)
		- [Example 1](#example-1-1)
		- [Example 2](#example-2-1)
	- [FontName](#fontname)
		- [Example 1](#example-1-2)
		- [Example 2](#example-2-2)
	- [FontSize](#fontsize)
		- [Example 1](#example-1-3)
		- [Example 2](#example-2-3)
	- [LineWidth](#linewidth)
		- [Example 1](#example-1-4)
		- [Example 2](#example-2-4)
- [Author](#author)

<!-- /MarkdownTOC -->


# Introduction
With this function it is possible to modify multiple style parameters of MATLAB graphic representations. It is only necessary to include the function call after the graphic representation code, that's all.

It can be used in two ways:

* Name-Value pair arguments: `setfigpaper('Width',[20,0.65],'Interpreter','Latex')`
* Arguments only: `setfigpaper([20,0.65],10,'Helvetica','Latex')` (With explicit order: Width,FontSize,FontName,Interpreter,Grayscale,LineWidth)

The available options are:

| Name        | Description         | 
| ------------- | ------------- |
| `Width`       | Simple: one integer. With aspect ratio: array with two elements, the width and the aspect ratio. |          
| `FontSize`    | The font size in all texts in the figure. |
| `FontName`    | Font family. |
| `Interpreter` | Text interpreter syntax, 'Latex', 'tex' or 'none'. |
| `Grayscale`   | Change all colours to grayscale. [boolean] |
| `LineWidth`   | Set line width only for axes, not for data. |

# Examples

## Grayscale

### Example 1

**Code:** MathWorks Plot Gallery Team (2020). MATLAB Plot Gallery - Wind (https://www.mathworks.com/matlabcentral/fileexchange/35250-matlab-plot-gallery-wind), MATLAB Central File Exchange. Retrieved May 14, 2020.

| Original        | `setfigpaper('GrayScale',true)`          | 
|:-------------:|:-------------:|
| <img src="http://jmrplens.com/GitHub_setfigpaper/plot1a.png" width="100%"></img>      | <img src="http://jmrplens.com/GitHub_setfigpaper/plot1b.png" width="100%"></img>  |

### Example 2

**Code:** MathWorks Plot Gallery Team (2020). MATLAB Plot Gallery - Subplot (2) (https://www.mathworks.com/matlabcentral/fileexchange/35298-matlab-plot-gallery-subplot-2), MATLAB Central File Exchange. Retrieved May 14, 2020.

| Original        | `setfigpaper('GrayScale',true)`          | 
|:-------------:|:-------------:|
| <img src="http://jmrplens.com/GitHub_setfigpaper/plot2a.png" width="100%"></img>      | <img src="http://jmrplens.com/GitHub_setfigpaper/plot2b.png" width="100%"></img>  |


## Interpreter

### Example 1

**Code:** MathWorks Plot Gallery Team (2020). MATLAB Plot Gallery - Heatmap Chart (https://www.mathworks.com/matlabcentral/fileexchange/63457-matlab-plot-gallery-heatmap-chart), MATLAB Central File Exchange. Retrieved May 14, 2020.

| Original        | `setfigpaper('Interpreter','Latex')`          | 
|:-------------:|:-------------:|
| <img src="http://jmrplens.com/GitHub_setfigpaper/plot3a.png" width="100%"></img>      | <img src="http://jmrplens.com/GitHub_setfigpaper/plot3bb.png" width="100%"></img>  |

### Example 2

**Code:** MathWorks Plot Gallery Team (2020). MATLAB Plot Gallery - Line Plot 2D (2) (https://www.mathworks.com/matlabcentral/fileexchange/35256-matlab-plot-gallery-line-plot-2d-2), MATLAB Central File Exchange. Retrieved May 14, 2020.

| Original        | `setfigpaper('Interpreter','Latex')`           | 
|:-------------:|:-------------:|
| <img src="http://jmrplens.com/GitHub_setfigpaper/plot4a.png" width="100%"></img>      | <img src="http://jmrplens.com/GitHub_setfigpaper/plot4b.png" width="100%"></img>  |

## FontName
* *Only work with 'Tex' interpreter*

### Example 1

**Code:** https://www.mathworks.com/help/matlab/ref/wordcloud.html

| Original        | `setfigpaper('FontName','Courier')`          | 
|:-------------:|:-------------:|
| <img src="http://jmrplens.com/GitHub_setfigpaper/plot3aa.png" width="100%"></img>      | <img src="http://jmrplens.com/GitHub_setfigpaper/plot3bc.png" width="100%"></img>  |

### Example 2

**Code:** MathWorks Plot Gallery Team (2020). MATLAB Plot Gallery - Heatmap Chart (https://www.mathworks.com/matlabcentral/fileexchange/63457-matlab-plot-gallery-heatmap-chart), MATLAB Central File Exchange. Retrieved May 14, 2020.

| Original        | `setfigpaper('FontName','Times New Roman')`           | 
|:-------------:|:-------------:|
| <img src="http://jmrplens.com/GitHub_setfigpaper/plot3a.png" width="100%"></img>      | <img src="http://jmrplens.com/GitHub_setfigpaper/plot6b.png" width="100%"></img>  |

## FontSize

### Example 1

**Code:** https://www.mathworks.com/help/matlab/ref/parallelplot.html

| Original        | `setfigpaper('FontSize',6)`          | 
|:-------------:|:-------------:|
| <img src="http://jmrplens.com/GitHub_setfigpaper/plot7a.png" width="100%"></img>      | <img src="http://jmrplens.com/GitHub_setfigpaper/plot7b.png" width="100%"></img>  |

### Example 2

**Code:** MathWorks Plot Gallery Team (2020). MATLAB Plot Gallery - Directed Graph Plot (https://www.mathworks.com/matlabcentral/fileexchange/63456-matlab-plot-gallery-directed-graph-plot), MATLAB Central File Exchange. Retrieved May 14, 2020.

| Original        | `setfigpaper('FontSize',15)`           | 
|:-------------:|:-------------:|
| <img src="http://jmrplens.com/GitHub_setfigpaper/plot8a.png" width="100%"></img>      | <img src="http://jmrplens.com/GitHub_setfigpaper/plot8b.png" width="100%"></img>  |


## LineWidth

### Example 1

**Code:** MathWorks Plot Gallery Team (2020). MATLAB Plot Gallery - Set Axes Positions (https://www.mathworks.com/matlabcentral/fileexchange/63458-matlab-plot-gallery-set-axes-positions), MATLAB Central File Exchange. Retrieved May 14, 2020.

| Original        | `setfigpaper('LineWidth',2)`          | 
|:-------------:|:-------------:|
| <img src="http://jmrplens.com/GitHub_setfigpaper/plot9a.png" width="100%"></img>      | <img src="http://jmrplens.com/GitHub_setfigpaper/plot9b.png" width="100%"></img>  |

### Example 2

**Code:** MathWorks Plot Gallery Team (2020). MATLAB Plot Gallery - Scatter Plot 3D (https://www.mathworks.com/matlabcentral/fileexchange/35288-matlab-plot-gallery-scatter-plot-3d), MATLAB Central File Exchange. Retrieved May 14, 2020.

| Original        | `setfigpaper('LineWidth',1.5)`           | 
|:-------------:|:-------------:|
| <img src="http://jmrplens.com/GitHub_setfigpaper/plot10a.png" width="100%"></img>      | <img src="http://jmrplens.com/GitHub_setfigpaper/plot10b.png" width="100%"></img>  |


# Author
Jose M. Requena Plens, 2020. (info@jmrplens.com   | joreple@upv.es)

Original concept: Noe Jimenez, 2014. (noe.jimenez@csic.es | nojigon@i3m.upv.es)



