# Lab 2 student package

Open Lab2\_Text\_Classification\_and\_Word\_Vectors.ipynb. This 90-minute lab has five computational checkpoints and accompanies the two conceptual Quiz 2 questions.

## Google Colab

1. Download and unzip this package to obtain the notebook.
2. Open https://colab.research.google.com/ and upload the .ipynb file.
3. Select a CPU runtime and run the first code cell.
4. If asked for data, upload the original Lab2\_Student\_Package.zip.
5. Complete the TODO functions and submit CP1-CP5 in Moodle as instructed.

No GPU, API key, model download or dataset download is needed. NumPy is the only non-standard numerical dependency. Fresh Colab runtimes may require uploading the ZIP again.

## Local Jupyter

Unzip the package and keep data/ beside the notebook. Use Python 3.9+ and NumPy. If NumPy is missing, run `python -m pip install -r requirements.txt` in your chosen environment. Jupyter must already be available as the notebook application; requirements.txt covers the lab code dependency only.

## Fixed inputs

The data folder contains train.tsv (360 labelled reviews), test.tsv (72 labelled reviews), settings.json, fixed_logistic_weights.json, similarity_audit.json and manifest.json. All are supplied. The reviews are original artificial teaching examples, not a real-world benchmark. Labels are 0 = negative and 1 = positive. Logistic weights are illustrative supplied parameters, not fitted weights. The vector audit is a diagnostic fixture.

Do not edit data files, preprocessing, labels or checkpoint parameters. The manifest detects accidental input changes. There is no development split because no hyperparameters are selected in this lab. Gradient-descent updates and neural-network training are reserved for a later lab.

The starter notebook intentionally stops at unfinished TODOs. Its small tests give hand-checkable examples without revealing checkpoint answers. Submit CP3 as an integer and other checkpoints to six decimal places; keep full precision in code.
