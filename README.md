delaIglesiaetal_Data
====================

Corpora and datasets for reproducing the experiments with clinical trial summaries.

Please, when using this work, cite it as follows:
de la Iglesia D, García-Remesal M, Anguita A, Muñoz-Mármol M, Kulikowski C, Maojo V. “A machine learning approach to identify clinical trials involving nanodrugs and nanodevices from ClinicalTrials.gov”. PLoS ONE 2014. DOI:10.1371/journal.pone.0110331.

CONTENT:

/unigrams: Input data, models and results to conduct the CT experiments with unigrams.

/bigrams: Input data, models and results to conduct the CT experiments with bigrams.

Each one of the abovementioned folders contain the following subfolders:

/binary: Data to conduct the experiments using a binary representation of the documents

/frequencies: Data to conduct the experiments using a frequency-based representation of the documents

/idf: Data to conduct the experiments using an Inverse Document Frequency-based epresentation of the documents

/tfidf: Data to conduct the experiments using a Term Frequency*Inverse Document Frequency-based representation

/norm_binary: Data to conduct the experiments using a binary representation of the documents with normalization

/norm_frequencies: Data to conduct the experiments using a frequency-based representation of the documents with normalization

/norm_idf: Data to conduct the experiments using a Inverse Document Frequency-based representation of the documents with normalization

/norm_tfidf: Data to conduct the experiments using a Term Frequency*Inverse Document Frequency-based representation with normalization

Each subfolder contain three parts:

/cv_splits: splits for cross-validation experiments
      
      /10-fold: splits for 10-fold cross-validation
      
      /loo: splits for leave-one-out cross-validation

/models: models generated for the different classifiers used in the experiments

500_vs_500_<subfolder>.arff: input dataset with 500 nano CT and 500 non-nano CTs, using the transformation specified by <subfolder>
