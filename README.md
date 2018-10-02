# Multiclass-Classification-Pytorch-Embeddings-and-Ensembles
Multiclass classification using Embeddings in Pytorch and Ensemble voting approach
Ausgehend vom Verkehrsunfaelle_train Datensatz soll Dein Algorithmus in der Lage sein,
die Unfallschwere (leicht, schwer, tödlich) eines Verkehrsunfalls zu prädizieren. 
Du erhältst auch einen zweiten Datensatz (Verkehrsunfaelle_test.csv), 
der verwendet wird, um die Vorhersage-Performance Ihres Algorithmus zu validieren.
Dazu verwendest Du Deinen Algorithmus und reichst die Prädiktionen im .csv-format ein.
Das file muss exakt 2 Spalten und 1000 Reihen plus eine headerreihe mit Unfall_ID und Unfallschwere besitzen.
Die erste Spalte beinhaltet die ID des Unfalls in aufsteigender Nummerierung,
die zweite die prädizierte Unfallschwere (1 = leicht, 2 = schwer, 3 = tödlich). 

The notebook contains a solutions using Pytorch with Embeddings and a Ensemble Voting approach based on several classical models
such as Support Vector Machines and DecisionTrees, etc.
