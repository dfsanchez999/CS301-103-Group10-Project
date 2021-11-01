# CS301-103-Group10-Project
Space weather detection model

Proposal

- What is the problem that you will be investigating? Why is it interesting?

With the exponentially expanding technological focus towards global communications, there has been an increasing focus to study and understand the environment in which these communications propagate. These communications can be adversely affected by a multitude of phenomena like solar flares and electromagnetic storms, which we are currently unable to predict accurately. The few instruments worldwide that can detect and study these phenomena don’t have the necessary coverage to help further our understanding.

One new potential instrument that has been proposed by Dr. Nathaniel Frissell of the University of Scranton is using Amateur ham radios. Case studies have shown that ham radio data can accurately detect one such phenomena called Traveling Ionospheric Disturbances(TID), which are wave structured variations in ionospheric electron content. Communications from GPS, radio and satellite are affected by the electron content and therefore any variation will change propagation. 

- What reading will you examine to provide context and background?

There are a multitude of published scientific papers on the topic that will be used to provide context and background.

- What data will you use? If you are collecting new data, how will you do it?

The data comes from two sources: The weak signal propagation reporting network or WSPRNet and the reverse beacon network or RBN. 

Reverse beacon network is a network of radio stations that report on the stations that they hear and the WSPRNet is a group of amateur radio operators that use digital radio modes to probe radio frequency propagation conditions. 

- What method or algorithm are you proposing? If there are existing implementations, will you use them and how? How do you plan to improve or modify such implementations? You don’t have to have an exact answer at this point, but you should have a general sense of how you will approach the problem you are working on. How will you evaluate your results? Qualitatively, what kind of results do you expect (e.g. plots or figures)? Quantitatively, what kind of analysis will you use to evaluate and/or compare your results (e.g. what performance metrics or statistical tests)?

Due to the nature of the data, we will be using algorithms based on classification. Our goal is to detect if there is a TID occurring within a specific time period within the data.  TIDs are perceived visually as a fading in ham radio usage over time as a quasi-periodic wave structure when the data is plotted in 2D histogram form. These histograms can be visually combed for those structures. We plan to apply pattern recognition and logistic regression to determine the presence of TIDs. This will enable us to create a detection model which will acquire the current data and compare it with the past data models to verify our results. The result will state the presence of TIDs in the ionosphere. 


