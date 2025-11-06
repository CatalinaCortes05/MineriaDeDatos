# MineriaDeDatos
Grupo 4: Boston Housing Dataset⏰
# PASO 1: Importar librerías
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn.preprocessing import LabelEncoder, MinMaxScaler, StandardScaler
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression, LogisticRegression
from sklearn.metrics import mean_squared_error, r2_score, accuracy_score, classification_report, confusion_matrix
from scipy.stats import shapiro
import warnings
warnings.filterwarnings('ignore')
sns.set(style='whitegrid')
