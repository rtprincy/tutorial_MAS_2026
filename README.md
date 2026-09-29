# Visualising complex data in Astronomy
The notebook is an unsupervised machine-learning workflow. It uses PCA, t-SNE, correlation-based feature reduction, UMAP, Gaussian-mixture clustering, cluster-separation metrics, and a later comparison with SIMBAD classifications.

# Follow the steps below to run the notebook 

git clone https://github.com/rtprincy/tutorial_MAS_2026.git

cd tutorial_MAS_2026

python3 -m venv .venv

source .venv/bin/activate

python -m pip install --upgrade pip
python -m pip install -r requirements.txt

jupyter lab
