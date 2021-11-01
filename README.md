# CS301-103-Group10-Project
Space weather detection model

Proposal

With the exponentially expanding technological focus towards global communications, there has been an increasing focus to study and understand the environment in which these communications propagate. These communications can be adversely affected by a multitude of phenomena like solar flares and electromagnetic storms, which we are currently unable to predict accurately. The few instruments worldwide that can detect and study these phenomena don’t have the necessary coverage to help further our understanding.

One new potential instrument that has been proposed by Dr. Nathaniel Frissell of the University of Scranton is using Amateur ham radios. Case studies have shown that ham radio data can accurately detect one such phenomena called Traveling Ionospheric Disturbances(TID), which are wave structured variations in ionospheric electron content. Communications from GPS, radio and satellite are affected by the electron content and therefore any variation will change propagation. TIDs are perceived visually as a fading in ham radio usage over time as a quasi-periodic wave structure when  the data is plotted in 2D histogram form. With existing data going back over 10 years, there is a treasure trove of data just waiting to be used.

There are a multitude of published scientific papers on the topic that will be used to provide context and background.

The data comes from two sources: The weak signal propagation reporting network or WSPRNet and the reverse beacon network or RBN. 

Reverse beacon network is a network of radio stations that report on the stations that they hear and the WSPRNet is a group of amateur radio operators that use digital radio modes to probe radio frequency propagation conditions. 

Due to the nature of the data, we will be using algorithms based on classification. Our goal is to detect if there is a TID occurring within a specific time period within the data. We plan to apply pattern recognition and logistic regression to determine the presence of TIDs. This will enable us to create a detection model which will acquire the current data and compare it with the past data models to verify our results. The result will state the presence of TIDs in the ionosphere. 
