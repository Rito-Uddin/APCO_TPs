# APCO practical labs

Regression laboratory by **Nabil Kardad and Rito Uddin**.

- [Current completed regression notebook](01-regression.Kardad_Uddin.ipynb): the current Google Colab version, including executed results, MSE calculations, RBFN and LWR studies, RLS comparisons, and neural-network experiments.
- [Open the working notebook in Google Colab](https://colab.research.google.com/drive/1lR2lfk768VgkeA_St8B2ORkEQ0gK-CUZ).
- [Run the GitHub notebook in Colab](https://colab.research.google.com/github/Rito-Uddin/APCO_TPs/blob/main/01-regression.Kardad_Uddin.ipynb).

The completed notebook replaces the previous submitted implementation. Obsolete checkpoint copies have been removed. `01-regression.student.ipynb` is the original teaching template, not the completed submission.

## Running the lab

Open the completed notebook in Colab and choose **Runtime > Run all**. Its first cell installs `regressionLabs` from the instructor's repository. NumPy, SciPy, Matplotlib, PyTorch and threadpoolctl are also required (available in the Colab environment used for execution).

The comparison studies calculate mean squared error as `residual_norm ** 2 / number_of_observations`. Outputs explicitly labelled residual norm retain the instructor's original metric. Execution times depend on the environment; the initial LLS print timers must not be interpreted as fitting benchmarks.
