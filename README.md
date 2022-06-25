# Fashion-Recommender-System

- fashiom recommender system used deep learning algorithm dengan CNN sebuah layer untuk extraction dari input layers sehingga mudah di olah pada hidden 
layers computational recommendation system

- Transfer learning dengan menggunakan module Resnet algorithm untuk image net

- import model
  import sebuah resnet dengan cnn performing
- extract features
  menggunakan sebuah renet model dengan extract features
  44k sbuah image yang di compare untuk rekomendasi 
  sehingga memiliki sebuah matriks (h x w x d) -> (224,224,3)
  
  CNN used resnect module:
  0->[100] -> [50] -> [25]->10
  Feature by feature by comparing
  
  2048-> feauture
  44k -> instances
  1 [ vectors ], 2048 vectors => (1,2048)
  2 [ ...... ] => (1,2048)
  
  
  (44k, 2048)
  
  => sehingga menghasilkan setiap vectors untuk setiap dimensi
  
- export model
  export dengan pickle untuk bisa di ambil dengan backend system, 1 instance terdiri dari 2048 vectors. setiap instances value di compare 
  instances by instances

- compute recommendations
  make the function to stimulation the system with model AI menggunakan NB (Nearest neighbor) 
  setiap instances (2048 dimensi of vecotr) di compare untuk instances lainnya.
  https://medium.com/swlh/k-nearest-neighbor-ca2593d7a3c4
  
- Data set : https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-dataset => 25 GB ( make sure your device)

# what want to used u can to use the test
- Download the images
- get one on sample 
- Compile
