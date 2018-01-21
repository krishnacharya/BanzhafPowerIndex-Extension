# About
Code for the extension of the Banzhaf power index to include associations
among players in a weighted voting game.

# Dependencies
* [numpy](http://www.numpy.org/)
* [pandas](https://pandas.pydata.org/)
* [matplotlib](https://matplotlib.org/index.html)


# Plot of the classical index v/s with association
Note that in the European Union, countries may have the same weight, so the classical index
for all such similar weighted countries coincide(single red circle) whereas after introducing 
the association matrix the values deviate above or below this(multiple blue sqaures).

![](plots/newvsold_weightx.png?raw=true)

![](plots/newvsold_poplx.png?raw=true)