# BCI-Data-Analysis
Analysing EEG Brain signals to detect the movements of hands for BCI applications
	
 Objective:
The objective of the experiment was based on a hypothesis which states that the electrodes
placed on the central line of the brain (C) are most efficient for recording EEG signals for
motor movement signal recording by performing several Feature extraction methods (FFT,
Hilbert Huang and Pwelch) and then performing a T-test on the alpha wave frequencies by
grouping electrodes based on their locations

Experimental Protocol:
Subjects performed different motor/imagery tasks while 64-channel EEG were recorded
using the BCI2000 system (http://www.bci2000.org). Each subject performed 14
experimental runs: two one-minute baseline runs (one with eyes open, one with eyes
closed), and three two-minute runs of each of the four following tasks:
A target appears on either the left or the right side of the screen. The subject opens and
closes the corresponding fist until the target disappears. Then the subject relaxes.
A target appears on either the left or the right side of the screen. The subject imagines
opening and closing the corresponding fist until the target disappears. Then the subject
relaxes.
A target appears on either the top or the bottom of the screen. The subject opens and closes
either both fists (if the target is on top) or both feet (if the target is on the bottom) until the
target disappears. Then the subject relaxes.
A target appears on either the top or the bottom of the screen. The subject imagines opening
and closing either both fists (if the target is on top) or both feet (if the target is on the
bottom) until the target disappears. Then the subject relaxes.
2
In summary, the experimental runs were:
Baseline, eyes open
Baseline, eyes closed
Task 1 (open and close left or right fist)
Task 2 (imagine opening and closing left or right fist)
Task 3 (open and close both fists or both feet)
Task 4 (imagine opening and closing both fists or both feet)
And all these 4 Tasks were repeated twice again.
The data are provided here in EDF+ format (containing 64 EEG signals, each sampled at
160 samples per second, and an annotation channel). Each annotation includes one of three
codes (T0, T1, or T2):
T0 corresponds to rest
T1 corresponds to onset of motion (real or imagined) of
the left fist (in runs 3, 4, 7, 8, 11, and 12)
both fists (in runs 5, 6, 9, 10, 13, and 14)
T2 corresponds to onset of motion (real or imagined) of
the right fist (in runs 3, 4, 7, 8, 11, and 12)
both feet (in runs 5, 6, 9, 10, 13, and 14)
In the BCI2000-format versions of these files, which may be available from the contributors
of this data set, these annotations are encoded as values of 0, 1, or 2 in the Target Code state
variable.
Montage:
The EEGs were recorded from 64 electrodes as per the international 10-10 system. The
numbers below each electrode name indicate the order in which they appear in the records;
note that signals in the records are numbered from 0 to 63, while the numbers in the figure
range from 1 to 64.

Acknowledgments
This data set was created and contributed to PhysioBank by Gerwin Schalk (Schalk at wadsworth dot org) and his colleagues at the BCI R&D Program, Wadsworth Center, New York State Department of Health, Albany, NY. W.A. Sarnacki collected the data. Aditya Joshi compiled the dataset and prepared the documentation. D.J. McFarland and J.R. Wolpaw were responsible for experimental design and project oversight, respectively. This work was supported by grants from NIH/NIBIB ((EB006356 (GS) and EB00856 (JRW and GS)).
DataSet URL - " https://physionet.org/content/eegmmidb/1.0.0/ "

References - 	Goldberger, A., Amaral, L., Glass, L., Hausdorff, J., Ivanov, P. C., Mark, R., ... & Stanley, H. E. (2000). PhysioBank, PhysioToolkit, and PhysioNet: Components of a new research resource for complex physiologic signals. Circulation [Online]. 101 (23), pp. e215–e220.

