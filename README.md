```bash
python3 -m venv .venv
pip install -r requirements.txt
# Donwload the model.
python3 model_dl.py
# Run the inference from the notebook.
python3 -m ipykernel install --user --name=phi_2
jupyter notebook
```
Source: https://cobusgreyling.medium.com/run-a-small-language-model-slm-local-offline-1f62a6cbdaef

Fine tuning: https://medium.com/@mohamedahmedkrichen/a-comprehensive-guide-to-fine-tuning-the-microsoft-phi-2-model-free-notebook-52a4b5e486aa
