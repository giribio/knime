WorkflowID: NRF18002

Name : VEGAQSARModels

Created by: Girinath Pillai

Created on: Jul 23,n18

KNIME ver: 3.5.3

Citation: KNIME Workflows, ID NRF18002, www.nyroindia.org, Kerala, India.

Nodes : RDKit, VEGA, KNIME Chemistry

Description:
Predict mutagenicity, carcinogenecity, developmental toxicity, skin sensitization, fish acute toxicity, ALogP, fathead minnow, daphnia magna, BCF Model, ready biodegradability.

Input:
You could load 1 SDF file or multiple SDF files.
And choose which field or property to be considered.
2D SDF or if you want to merge multiple SDF files to 1 SDF you could use this node as a reader.

Models:
Users have the option to choose different models apart from the models mentioned under the nodes. 'Configure' one of the VEGA node and user could change the model to be predicted.

Output:
Save as CSV file - assign the output file/folder in 'CSV Writer' node and Interactive Table Viewer

Options:
You could consider MOL2, MOL or other chemical formats and update the I/O node accordingly.

www.nyroindia.org
