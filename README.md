# From Rattle to Roar: Optimizer Showdown for MambaStock on S&P 500
## Maria Garmonina, Alena Chan
mkg2169@columbia.edu, ac5477@columbia.edu

We evaluate the performance of several optimizers on the task of forecasting S&P 500 Index returns with the MambaStock model. Among the most widely used algorithms, gradient-smoothing and adaptive-rate optimizers (for example, Adam and RMSProp) yield the lowest test errors. In contrast, the Lion optimizer offers notably faster training. To combine these advantages, we introduce a novel family of optimizers, Roaree, that dampens the oscillatory loss behavior often seen with Lion while preserving its training speed.

arXiv: 

Please see `Roaree_and_optimizer_comparison.ipynb` for the all the code and details of the project.
