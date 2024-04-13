# DL-Midterm
Team: Tappu Sena

This rep contains 2 files.
1. Mid-Term (Tappu Sena).ipynb: This is the final python notebook which contains the model which was submitted to the competetion.
2. best_model_full.pth: This is the saved model for refrence. This model can be used to reproduce our results.

To use the saved model the following code can be used by you:

model = torch.load('best_model_full.pth')  # To load the full model
model.eval()                               # Don't forget to set the model to evaluation mode
