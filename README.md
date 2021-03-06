{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# Machine Learning"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "In today's business environment, more and more people obtain mortgages, auto loans, and debt consolidation from online services. Machine learning algorithms are designed to predict credit risks.\n",
    "\n",
    "In this assignment I utilized the imbalanced-learn, Scikit-learn and other tools and libraries to build and evaluate the models using the following techniques: \n"
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
    "- In terms of recall, again, oversampling had the highest scores.\n"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "- Oversampling was also highest for geometric mean, with naive oversampling resulted the highest score.\n"
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
    "- Of the two models, the Easy Ensemble Classifier had the higher balanced accuracy score.\n"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "- The Easy Ensemble Classifier also had the better recall with the weighed average score.\n"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "- Geometric mean was not reported in the classification report, but the Easy Ensemble Classifier had the higher F1 score (weighted average).\n"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "- For the balanced random forest model, the top three features were:\n",
    "    Total Received Principal\n",
    "    Last Payment Amount\n",
    "    Total Received Interest\n",
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
