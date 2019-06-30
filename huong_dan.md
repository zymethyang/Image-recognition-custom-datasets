0. Activate virtual environment

./venv/Scripts/activate.bat

1. Training: 

python train.py --train training_data/ --val testing_data/ --num_classes 2

2. Sau khi train xong thì bắt đầu sử dụng. 

python predict.py testing_data/cats/cat.1110.jpg


