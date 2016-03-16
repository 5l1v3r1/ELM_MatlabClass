ELM_MatlabClass is a fast MATLAB OOP implementation of Extreme Learning Machines
as proposed by Huang et al., 

	Huang, Guang-Bin, Qin-Yu Zhu, and Chee-Kheong Siew.
	"Extreme learning machine: theory and applications." 
	Neurocomputing 70.1 (2006): 489-501.
	
	Huang, Guang-Bin, et al. "Extreme learning machine for regression and 
	multiclass classification." Systems, Man, and Cybernetics, Part B: Cybernetics, 
	IEEE Transactions on 42.2 (2012): 513-529.

If you want to use this package please cite 

	Taormina, Riccardo, and Kwok-Wing Chau. 
	"Data-driven input variable selection for rainfall–runoff modeling using 
	binary-coded particle swarm optimization and Extreme Learning Machines." 
	Journal of Hydrology 529 (2015): 1617-1632.

for which it was initially developed.	


This package contains:

1) ELM_MatlabClass.m, 		which is the class implementing the ELM;

2) example_CLASSIFICATION.m, 	which shows how to use ELM for binary classification;

3) example_REGRESSION.m, 	which shows how to use ELM for regression problems;

4) computeAccuracy.m, 		which computes classification accuracy of ELM;

5) computeR2.m, 		which computes the coefficient of determination(R^2);

6) README.MD, 			this file;

7) license.txt,			the GNU GPL license.

The UCI datasets breast-cancer-wisconsin.data and data_akbilgic.csv are also 
included as they are used in the examples for CLASSIFICATION and REGRESSION, 
respectively. The datasets are available at http://archive.ics.uci.edu/ml/.
Please refer to the UCI website for further information on the datasets.



Copyright 2015 Riccardo Taormina 
riccardo.taormina@gmail.com 

This software is under the GNU General Public License. 
Please read the text version of the license included with the package (gpl.txt).


This file is part of ELM_MatlabClass.

    ELM_MatlabClass is free software: you can redistribute 
    it and/or modify it under the terms of the GNU General Public License 
    as published by the Free Software Foundation, either version 3 of the 
    License, or (at your option) any later version.     

    ELM_MatlabClass is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with  Matlab-Multi-objective-Feature-Selection.  
    If not, see <http://www.gnu.org/licenses/>.
