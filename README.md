# Graph_GAN
Code for the paper "Generative Adversarial Graph Convolutional Networks to Synthesize Human Actions"


---
### GAN
Original GAN adapted with NTU-RGB+D as input

#### Train
```
python gan_graph.py --data_path path_train_data --label_path path_train_labels
```

#
### dc-GAN
Deep Convolutional GAN adapted with NTU-RGB+D as input

#### Train
```
python dcgan-graph.py --data_path path_train_data --label_path path_train_labels
```

#
### cGAN
Conditional-GAN adapted with NTU-RGB+D as input

#### Train
```
python cgan_graph.py --data_path path_train_data --label_path path_train_labels
```

#
### StarGAN
StarGAN adapted with NTU-RGB+D as input

#### Train
```
python stargan_graph.py --train_path path_train_data --train_label_path path_train_labels --val_path path_val_data --val_label_path path_val_labels
```


#
### Graph-Autoencoder
Graph-Autoencoder adapted with NTU-RGB+D as input

#### Train
```
python graph-ae.py      # Train
python graph-ae-eval.py # Evaluate
```
---
