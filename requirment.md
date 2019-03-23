if use dlib:
    python = 2.7
    pytorch = 1.0.0
    cuda = 9.0
    cudnn = 7.4.1_1
python code/train_hopenet.py --snapshot hopenet_robust_alpha1.pkl --dataset AFLW2000 --data_dir ~/anaconda3/Dataset/PoseFace/AFLW2000-3D/AFLW2000 --filename_list ../../Dataset/PoseFace/AFLW2000-3D/AFLW2000/file_name.txt