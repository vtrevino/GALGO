# GALGO

GALGO IS NOW ON CRAN.


Thanks for all galgo users. We have considered all e-mails and requests to provide a version of Galgo for R 3. The new version of R 3 is a major revision, so galgo was also revised to be able to run smoothely in R 3.

Changes in Galgo 1.4:
- Small fixes to run on R 3.3.3

Changes in Galgo 1.3:
- Small fix of compiling sources

Changes in Galgo 1.2:
- No major changes to original functionality.
- Minor Bugs corrected.
- Adaptations for R 3 was needed. All internal classifiers are now using "_R_" or "_C_", for example, knn_R_predict or mlhd_C_predict and so on for svm, nascent, knit, repeat, random forest (rainforest), etc. This has no effect on most users.
- Galgo 1.2 should be now available in CRAN soon (it was submitted on 25/March/2014). This will allow installations using the standard install.packages("galgo") in the command line. We still provide sources here.

Galgo source is available on the links below.

#MANUAL INSTALLATION OF THE SOURCE PACKAGE (updated to 1.3)
===========================================================
On Windows:
- You may need Rtools for this. see http://cran.r-project.org/bin/windows/
- Install needed packages in R. Open R and type: install.packages(c("R.oo", "MASS", "class", "e1071", "rpart", "nnet", "randomForest"))
- Download galgo_1.x.tar.gz file.
- Open the CMD terminal program.
- cd to the folder where your compressed galgo file is.
- Make sure R is under your PATH. Type: echo %PATH%. If yes, jump to 8.
- Add R to your path (adapt your version and location), type: SET PATH=%PATH%;C:\Program Files\R\R-3.0.2\bin;
- type: R CMD INSTALL galgo_1.x.tar.gz
- Run R and type "library(galgo)". It should now work.

On Mac OS X:
- Install needed packages in R. Open R and type: install.packages(c("R.oo", "MASS", "class", "e1071", "rpart", "nnet", "randomForest"))
- Download galgo_1.x.tar.gz file.
- In R, Select option "Package Installer" from "Packages & Data" menu.
- Select "local source package" in the "Packages Repository"
- Click on "Install" button.
- Select galgo_1.x.tar.gz from the download location.
- type "library(galgo)". It should now work.

On Linux:
- Install needed packages in R. Open R and type: install.packages(c("R.oo", "MASS", "class", "e1071", "rpart", "nnet", "randomForest"))
- Download galgo_1.3.tar.gz file.
- Open a terminal.
- cd to the folder where your compressed galgo file is.
- type: R CMD INSTALL galgo_1.3.tar.gz
- Run R and type "library(galgo)". It should now work.
