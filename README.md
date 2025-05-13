In this project, there are the annotations of four poems by Horace, produced by automatic annotation models.
The poems are: Odes I.32, Odes I.11, Odes I.23, and Odes III.30.
The folders contain the annotations, respectively, of:
	•	Horace Perseus: annotated using the Perseus model through the online UDPipe tool
	•	Horace Proiel: annotated using the Proiel model through the online UDPipe tool
	•	Horace Stanza: annotated using the Stanza model via a Google Colab script
	•	Stanza_Usable: files that can be used to calculate the metrics
 	•	File_Gold: manual annotations that represent the gold standard

There are two folders with the Stanza files. Since the output automatically created by Stanza wasn’t working due to syntax errors in the CoNLL file, these errors have been fixed. The Stanza_Usable folder contains the files that can be used to calculate the metrics.

The annotations were performed using the online UDPipe tool for the first two models, and a Google Colab script for Stanza.
The .txt files of the corresponding poems are also included.
