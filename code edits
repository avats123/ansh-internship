import json
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
from datetime import datetime
import os
import warnings
warnings.filterwarnings('ignore')

def load_fhir_files(): # loading the FHIR files from specific file path, and storing them under json files
    bundles = []
    data_dir = 'downloads/fhir'  # or wherever you extracted files
    for filename in os.listdir(data_dir):
        filepath = os.path.join(data_dir, filename)
        with open(filepath, 'r') as f:
            data = json.load(f)
            bundles.append(data)
    return bundles

def extract_fhir_files(bundles):
    resources = {
        'Patient': []
        'Observation': []
        '
            
    }
