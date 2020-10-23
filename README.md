# Cell_Migration_Analysis
This project was inspired but a previous work in collaboration with Maciej Dobrzynski (https://github.com/dmattek)

The R notebook was conceived to analyze single cell migration. The data, is collected via ImageJ tracking of single cells. The results contain information about the experimental condition (clone) and the ID represent a single cell. For every cell and every timepoint X and Y location are given.
The analysis and plots show total traveled distance, mean speed, persistence(directionality) and instantaneous velocity of all the single cells. Moreover the full tracks are shown as centered in the origin.

Required libraries:
- dplyr
- ggplot2
- data.table
- tcltk
- gganimate

