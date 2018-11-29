# cheatsheet
cheatsheet for work

1. Docker Migration

sudo nvidia-docker commit 86b9a0e1dd1a nvidia/cuda:9.0-cudnn7-devel-netAdapt-181109

sudo nvidia-docker save -o image.tar nvidia/cuda:9.0-cudnn7-devel-netAdapt-181109

scp image.tar etri@129.254.70.249:/home/etri/

sudo docker load -i image.tar

