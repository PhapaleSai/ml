# Machine_learning
Machine_learning_sai

# IMP CODE
Save all slips to .txt extension beacuse our code only reads txt
import requests

url = "https://raw.githubusercontent.com/PhapaleSai/ml/main/mla/Slip3.txt"
response = requests.get(url)
print(response.text)
