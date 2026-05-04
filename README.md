**EMS Protocol Generation — T5-base

Fine-tuned T5-base model that generates prehospital EMS protocol responses from emergency scenarios. Trained on 5,000 NEMSIS-derived scenario-response pairs.

How to run

1. Open the notebook in Google Colab
Upload `EMS_T5base_Colab.ipynb` to [colab.research.google.com](https://colab.research.google.com)
2. Set runtime to A100
3. The notebook requires an A100. It will run out of memory on a T4.
4. In the left sidebar file browser, upload `ems_scenarios_5000.csv`
5. Run all cells


Training takes approximately 2 hours. The best model checkpoint saves automatically.

Dataset: Derived from the 2024 NEMSIS Public-Release Research Dataset. Request access at [nemsis.org](https://nemsis.org/using-ems-data/request-research-data/)


Authors: Kasvi Singh and Sahil Chhabra — Yale University
