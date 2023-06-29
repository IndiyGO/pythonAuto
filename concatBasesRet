import pandas as pd
import openpyxl
import matplotlib.pyplot as plt
import numpy as np

WS = pd.read_excel('RETENÇÃO POWER BI.xlsx', sheet_name="WS")
ABO = pd.read_excel('RETENÇÃO POWER BI.xlsx', sheet_name="ABO")
KEN = pd.read_excel('RETENÇÃO POWER BI.xlsx', sheet_name="KEN")
SOB = pd.read_excel('RETENÇÃO POWER BI.xlsx', sheet_name="SOB")
JUA = pd.read_excel('RETENÇÃO POWER BI.xlsx', sheet_name="JUA")
THE = pd.read_excel('RETENÇÃO POWER BI.xlsx', sheet_name="THE")
THESUL = pd.read_excel('RETENÇÃO POWER BI.xlsx', sheet_name="THESUL")
PICOS = pd.read_excel('RETENÇÃO POWER BI.xlsx', sheet_name="PICOS")
PNB = pd.read_excel('RETENÇÃO POWER BI.xlsx', sheet_name="PNB")
JP = pd.read_excel('RETENÇÃO POWER BI.xlsx', sheet_name="JP")
CBD = pd.read_excel('RETENÇÃO POWER BI.xlsx', sheet_name="CBD")

df = pd.concat([WS, ABO, KEN, SOB, JUA,THE, THESUL, PICOS, PNB, JP, CBD])
df.to_excel('RetConsolidado.xlsx', index=False)
