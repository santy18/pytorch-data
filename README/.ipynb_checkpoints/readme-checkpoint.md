# pytorch
making a volume so you can keep all your notebooks in one place in the host. while still using pytorch. 
```
mkdir -p ~/Desktop/jetson/pytorch-data
jetson-containers run --volume ~/Desktop/jetson/pytorch-data:/workspace/data $(autotag pytorch)
```