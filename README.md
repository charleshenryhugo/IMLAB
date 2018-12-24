# Introduction
IMLAB is an image processing software based on TNRD algorithm.
I developed this with matlab for my bachelor thesis and stopped maintaining it since graduation.
For the purpose of saving the code, I dragged it to github.

## Instruction
IMLAB was only tested on Windows. In case you want to use the code, follow the instructions below.

(1).Download and decompress all zip files.   
(2).Confirm that you see 'GaussianDenoising', 'JPEGdeblocking' and 'SuperResolution' in 'Testcodes(denoising-deblocking-SR)'.   
(3).Put all the '.mat' files of 'TrainModels4Deblocking' into the 'JPEGdeblocking' folder.   
(4).Put all the '.mat' files of 'TrainingModels4GaussianDenoising5' and 'TrainingModels4GaussianDenoising79' into the 'GaussianDenoising' folder.   
(5).Put all the '.mat' files of 'TrainingModels4SuperResolution' into the 'SuperResolution' folder.   
(6).Put 'Testcodes(denoising-deblocking-SR)' into 'IMLABCodes'.   
(7).Find 'TNRD.m' in 'IMLABCodes' and open it with MATLAB.
(8).Try to run the 'TNRD.m', and you will see a GUI.   
(9).Good luck! 

For complete training-models of TNRD algorithm, please refer to www.GPU4Vision.org.
