# bathing_waters_bg
Data from the microbiological monitoring of marine bathing waters in Bulgaria (Black Sea) for the EU Bathing waters directive

## General description
The monitoring is conducted during the bathing season (summer), every 2 weeks (or more often if there is suspected contamination). The current main parameters measured are the concentrations of intestinal enterococci and Escherichia coli; additional, optional parameters include water chemistry, visual observations of contamination, unusual smells, etc. Full description with the corresponding units and methods is included in a separate file here. The distribution of the concentrations of the two types of bacteria throughout the season determine the status of the bathing waters, which is what is reported to the EC and published in their reports (and available for download). 

## The problem
The institutions responsible for the monitoring are the Regional Health Inspectorates of the Bulgarian coastal regions. The data are supposed to be public, so they are published on their websites every year, usually after the end of the bathing season. If you want to check to know where to go during the summer, you're out of luck. There are 3 RHIs involved; each has a separate awful website, with the water monitoring data buried thirty levels deep in the most improbable places.  
To compound this, there is also no standard form or way of storing the data. Each RHI apparently chooses the way in which to present the data. The result is that 2 are in Excel files, while 1 is in pdf (?!?)... On top of that, the files themselves are really, really messy. 

## Purpose
All of the above makes the Bulgarian bathing waters data a wonderful exercise in tidying hopelessly messy data. The purpose of this repository is to document and store the steps in cleaning the raw data, with the end result hopefully somewhat easier to analyze, if I ever need it or feel like it. Also, the idea is to have a script/procedure ready for the next time I inevitably need to repeat this. All the cleaning and processing will be done in R. 
*NOTE I've already compiled and cleaned (manually) a good portion of the available data from previous years. I'm going to follow the structure I decided on then - but I might go back and try to arrive at the same result later, when I finish tinkering.*

## Data usage
This is public data, free to look at, use, make a pretty visualization, etc. Unfortunately, it's in Bulgarian, so I doubt it will be terribly useful to many people. If it ever saves someone the trouble of compiling and cleaning it - you're welcome! 

