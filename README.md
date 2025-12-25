# An Investigation of

# Black Hole Mergers

##### Zain Nasir

##### Yorktown Middle School

##### Muncie, Indiana, USA


### Introduction

The objective of this project is to understand black hole mergers and their
characteristics. According to Einstein’s general theory of relativity, when two
black holes collide they produce ripples in space-time that travels as
gravitational waves which are then detected by LIGO (Laser Interferometer
Gravitational Wave Observatory). As the black holes come closer together they
release larger amounts of gravitational waves which are then detected as chirp
frequencies.

#### Research Question

```
Is there a relationship between the black hole masses and their distances that
will account for the strength of the chirping sound?
```

#### Hypothesis

1. According to Newton’s law of gravity, the gravitational _VG_ , at distance _R_
    from the merged black holes with mass _MT_ is:
2. I hypothesized that _SNR_ is proportional to the gravitational potential, _VG_ :
3. Accordingly a linear relationship is expected between _SNR_ and _VG_ :

###### VG = -GMT/R

## SNR ∝ VG

```
SNR = kVG ͢ SNR = kVG + c
```
```
k represents the slope of the line and c is the intercept
```
```
Black hole mergers could be accounted for by Newton’s Laws of Gravity.
```

### Methodology

LIGO data corresponding to black hole mergers is publicly available at GWOSC.
For each merging event, the data tabulates masses of the merging black holes,
time of occurrence and its distance from earth. It also provides the signal
strength evaluated as SNR (Signal to Noise Ratio). There are about 90 black hole
merger events since 2015.

#### Data

#### Preprocessing

The data files were first read using Python’s data analysis library Pandas. The
data was checked for missing values.


#### Analysis and Visualization

(^) The data files were first converted into Pandas’ dataframe objects, which were
then used to plot graphs using Python’s plotting tools such as Matplotlib and
Seaborn.
The regression lines are plotted using Seaborn and Pearson’s correlation

##### coefficients were computed using Scipy (Python’s scientific library).

#### Computation

(^) Google Colab was used to perform all the analysis.

### Methodology


### Conclusion & Discussions

```
● There is a strong relationship between SNR and other characteristics of the
black hole mergers such as total mass and distance.
```
```
● It can also be observed that SNR strongly depends on distance.
```
```
● SNR also has a strong linear relationship with MT/R , which is consistent
with Newton’s laws and the hypothesis posed in this project.
```

### References

1. “Gravitational Waves, as Einstein Predicted.” _LIGO Lab | Caltech_ , [http://www.ligo.caltech.edu/image/ligo20160211a.](http://www.ligo.caltech.edu/image/ligo20160211a.)
2. “Gravitational Waves from a Binary Black Hole Merger Observed by LIGO and Virgo.” _LIGO Lab | Caltech_ , [http://www.ligo.caltech.edu/news/ligo20170927.](http://www.ligo.caltech.edu/news/ligo20170927.)
3. “Gravitational Waves from Supermassive Black Hole Binaries Might Be “Right around the Corner.”” _News.northwestern.edu_ ,
news.northwestern.edu/stories/2023/06/gravitational-waves-from-supermassive-black-hole-binaries-might-be-right-around-the-corner/.
4. “GWTC.” _Gwosc.org_ , gwosc.org/eventapi/html/GWTC/.
5. Hampson, Michelle. “Sensor Could Help Detect Gravity Waves in Orbit.” _IEEE Spectrum_ , July 2024, spectrum.ieee.org/gravitational-wave-detector.
6. Lerner, Louise. “What Is a Black Hole?” _News.uchicago.edu_ , 13 Oct. 2022, news.uchicago.edu/explainer/black-holes-explained.
7. LIGO Caltech. “What Is an Interferometer?” _LIGO Lab | Caltech_ , 2019, [http://www.ligo.caltech.edu/page/what-is-interferometer.](http://www.ligo.caltech.edu/page/what-is-interferometer.)
8. “LIGO Lab | Caltech | MIT.” _LIGO Lab | Caltech_ , 2019, [http://www.ligo.caltech.edu/.](http://www.ligo.caltech.edu/.)
9. “Nobel Prize-Winning Discovery on Gravitational Waves Came about with Contributions from USC Scientists.” _USC Today_ , 6 Oct. 2017,
today.usc.edu/nobel-prize-winning-discovery-on-gravitational-waves-came-about-with-contributions-from-usc-scientists/. Accessed 17 Feb. 2025.
10. Sutter, Paul. “What Happens When Black Holes Merge?” _Space.com_ , Space, 21 Oct. 2024, [http://www.space.com/what-happens-when-black-holes-merge.](http://www.space.com/what-happens-when-black-holes-merge.)
11. Wikipedia Contributors. “Binary Black Hole.” _Wikipedia_ , Wikimedia Foundation, 16 June 2019, en.wikipedia.org/wiki/Binary_black_hole.
12. “Binary Black Hole.” _Wikipedia_ , Wikimedia Foundation, 16 June 2019, en.wikipedia.org/wiki/Binary_black_hole.
13. “Black Hole.” _Wikipedia_ , Wikimedia Foundation, 22 Jan. 2019, en.wikipedia.org/wiki/Black_hole.
14. “Spacetime.” _Wikipedia_ , Wikimedia Foundation, 6 Jan. 2020, en.wikipedia.org/wiki/Spacetime.

(^)
