# Knowledge-Graph-for-Methane-Selective-Conversion
The neural network model can maintain a consistent trend, with the maximum error of conversion rate and selectivity within 5%.

This code is based on jupternotebook and uses the python language. 
The necessary libraries are installed using the following commands:
pip install ipykernel
pip install -r requirements.txt
or
pip install scikit-learn pandas neo4j numpy python-dotenv openai torch openpyxl 

cuda is necessary.

The runtime environment for this code is packaged as an environment.tar.gz file. 
Additionally, retrain_set.csv is the retraining dataset used to obtain the results presented in the article, you will need to replace this with your own dataset. 
You also need to configure the relevant keys in the KEY.env file.
