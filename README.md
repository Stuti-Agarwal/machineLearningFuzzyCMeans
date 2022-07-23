# machineLearningFuzzyCMeans
Developing a Fuzzy C Means model to implement on the given datasets 


1.  The mentioned data set is basically 2-D data implicitly arranged as clusters (in some sense) and also plotted for visualization. 2-D implies n = 2. Refer to the terminology of the attached power-point slides. The total number of points is 1000.
2.	You are first to extract every 4 out of 5 data in a consistent interspersed manner (i.e. frequency of 4 out of 5 will be maintained for every block of 5 consistently) and save it in another file which will serve as your mining data file. Thus N = 800. The balance 1 out of 5 data you will save in a second file which you can call the classification data file. 
3.	Use the algorithm defined below of the power-point file (use the current version and not those provided previously) to generate your own program (in any language – Python preferable due to the need for downstream graphics) for generating clusters using the data contained in the mining data file. In the codification process, take m = 2, A = I (Identity matrix which then makes A redundant in all calculations),  = 0.001 (you may change this with one less or more zero).
