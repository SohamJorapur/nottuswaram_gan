# nottuswaram_gan

Steps to run:

1. !pip uninstall tensorflow 
   !pip install tensorflow-gpu

2. !pip list | grep tensor  ( check that tensorflow-gpu 2.x is installed)


3. !git clone  https://github.com/SohamJorapur/nottuswaram_gan.git

4. ! export CUDA_VISIBLE_DEVICES="0"; python ./wavegan2/train_wavegan.py train ./train 	--data_dir ./wavegan2/data/
