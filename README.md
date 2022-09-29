# publicly-available-microscopy-data
Compiling and describing publicly available microscopy datasets

## Statistics
* Alpha Diversity
  * Richness (S)
      * The number of unique entries within an image attribute
  * Shannon Index (H')
      * A measure of diversity in a single community given richness and evenness
      * Ranges [0, $\infty$] where ↑H'= high diversity and ↓H'=low diversity
      * $H'=-\sum\limits_{i=1}^S p_{i}lnp_{i}$
  * Normalized Median Evenness (NME)
      * Normalized estimate of evenness taken from the median $-p_iln(p_i)$ value from Shannon Index calculations
      * $NME = \frac{median(-p_{i}lnp_{i})}{max(-p_{i}lnp_{i})}$
  * Pielou's Evenness (J')
      * Ratio of observed H' to the maximum possible H' given a sample
      * $J'=\frac{H'}{H'_{max}}$
        * Where $H'_{max}=lnS$
  * Simpson's Evennnes (E)
    * Ratio of inverse dominance $D$ to richness
    * $E=\frac{1/D}{S}$
    * Where $D=\sum\limits_{i=1}^S p_{i}^2$
  * Gini Coefficient (GC)
    * Measure of inequality within a community
    * Ranges [0, 1] where 1 is absolute inequality and 0 is perfect equality
    * $GC=\frac{A}{(A+B)}$
      * `A` = Area above Lorenze curve
      * `B` = Area below Lorenze curve

