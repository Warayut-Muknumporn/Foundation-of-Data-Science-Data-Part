# Foundation-of-Data-Science (Data part)
This project is one part of module foundation of data science 

Download the data set fish1.txt about the catch of a hypothetical fishing fleet from

http://edshare.soton.ac.uk/19466/

and import it into Python. The data set records data for a time period of one day during which one fisherman has fished in a lake. The fisherman uses three types of fishing rods, labeled A, B, and C, each using different bait. The fisherman has recorded every catch he has made during this time. The data set consists of three columns with X values giving the times at which the fisherman has made a catch, the Y values indicate the size of that catch (i.e. its weight in kg), and the Z values give a letter A, B, or C which indicates which fishing rod was used to make that catch. Using Python, your task is to analyse this data set.

In a first step, generate a plot that illustrates the distributions of X values (times of catch, the format is hours, fraction of hours on a 24h schedule for the day). Then also plot the distribution of Y values (size of catch), and finally generate a plot which analyses the effectiveness of each type of bait. Characterise and describe these distributions by measures of centrality, spread, and suitable additional measures introduced in the introduction to statistics lectures that you think shed light on the shape of the respective distributions. Assuming that the data are a sample from a larger population, give mean values with 95% confidence intervals for both distributions.

In a second step, it is of interest to analyse the dependence between time of catch (X value) , size of catch (Y value), and the type of bait used (Z). Generate suitable plots to analyze these relationships and characterize them by statistical measures. What is the correlation between X and Y? Analyse the amount of information about Y that is given by knowledge of X.

More generally, address the following questions and give support for your answers:
What is the best time to go fishing at this lake?
Which bait is most effective?
What is the best type of bait to use at 3pm in the afternoon?

#Analysis
![Y_density_100](https://github.com/Warayut-Muknumporn/Foundation-of-Data-Science-Data-Part/assets/116235617/ceebc244-2582-4c9f-869d-fc2acc7e00a8)
![X_fish_24bins](https://github.com/Warayut-Muknumporn/Foundation-of-Data-Science-Data-Part/assets/116235617/64599ab5-6189-4af5-970a-48c12e84f42b)
![Scatter_plot_3](https://github.com/Warayut-Muknumporn/Foundation-of-Data-Science-Data-Part/assets/116235617/29b42d66-ed1c-4158-bdd7-976243cd1190)
![line number if fish caugh in one day](https://github.com/Warayut-Muknumporn/Foundation-of-Data-Science-Data-Part/assets/116235617/f7d8ecb9-ebb9-459e-b274-534d9cb3676c)
![Distribution in each hour](https://github.com/Warayut-Muknumporn/Foundation-of-Data-Science-Data-Part/assets/116235617/c3bce1f9-0627-4c36-adf6-e454e0d7b236)
![95%mean_frequency_X](https://github.com/Warayut-Muknumporn/Foundation-of-Data-Science-Data-Part/assets/116235617/12d35965-ff60-4eb5-b563-624ba090b033)
![95%distribution_frequency_X](https://github.com/Warayut-Muknumporn/Foundation-of-Data-Science-Data-Part/assets/116235617/6abf363c-a590-41c4-a70c-42f5a79390e2)

