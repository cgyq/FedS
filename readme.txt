python main.py --dataset=tinyimagenet --model=resnet50 --alg=fedgroup --lr=0.01 --mu=5 --epochs=10 --comm_round=100 --n_parties=10 --partition=noniid --beta=0.5 --logdir='./logs/' --datadir='./data/tiny-imagenet-200/'

tensorboard --logdir='acc'