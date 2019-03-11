## Build & run
* Install docker-ce and nvidia-docker2 (https://github.com/NVIDIA/nvidia-docker)
* docker build -t tensortest .
* sudo docker run --runtime=nvidia -it tensortest

## Run tests
* cd /models/tutorials/image/cifar10
* python cifar10_train.py tai python cifar10_multi_gpu_train.py
