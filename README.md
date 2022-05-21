# Optimal law enforcement with python
Optimal Law Enforcement with python (deterrence model)\
This project is designed to find the optimal sanction and the optimal probability of arrest and punishment in Nuno Garoupa's (2001) optimal law enforcement model. I use python code to find the optimal points ($S$, and $p$).

I searched several articles to find the explicit demonstration of the resolution of the optimal law enforcement model like Garoupa's but I got tired. Therefore, I tried to find ways to solve this puzzle myself (see file "Solving_Optimal_law_enforcement_Model.pdf").  So, the idea is to compare the solution I found by solving manually the model, and the computation on python. I ended up with the same result. It's amazing.\

My next article is to extend this model by introducing non-monetary gain (reputation) other than the monetary gain that motivates the offender to perform the illegal act. With this, I try to distinguish between the probability of arrest and the probability of conviction. In my new model, we study three states of nature: i) committing a crime, but without arrest, ii) committing a crime with arrest, iii) committing a crime and being arrested and punished) which are associated with respective utility functions and probabilities.\

In order to run the program, the user is asked to follow the instruction below
# 1. Installation required
python 3.6 (or higher)\
pip install sympy\
pip install matplotlib\
pip install jupyter notebook

then write in the command :
python -m notebook

# 2. Download file

You are invited to download the file : "deterr_model.ipynb" 

Write in your browser (chrome for example) : http://localhost:8888/
then, you can search in your download directories (desktop local file) the file "deterr_model.ipynb".

Once you have found the file, you can launch each code step by step in Jupyter notebook.
