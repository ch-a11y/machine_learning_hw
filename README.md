{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# Machine_Learning"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## Credit Risk Resampling"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "- In comparison, the oversampling models had the highest balanced accuracy scores.\n"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "- In terms of recall, again, oversampling had the highest scores - this time SMOTE the highest with 0.67.\n"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "- Oversampling was also highest for geometric mean, with naive oversampling the highest with a score of 0.63.\n"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## Credit Risk Ensemble"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "- Of the two models, the Easy Ensemble AdaBoost Classifier had the higher balanced accuracy score of 0.945.\n"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "- The Easy Ensemble Classifier also had the better recall, with a weighed average score of 0.94.\n"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "- Geometric mean was not reported in the classification report, but the Easy Ensemble Classifier had the higher F1 score of 0.97 (weighted average)\n"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "- For the balanced random forest model, the top three features were:\n",
    "    Total Received Principal (0.08)\n",
    "    Last Payment Amount (0.068)\n",
    "    Total Received Interest (0.064)\n",
    "    "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.7.9"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 4
}
