# Character-Animation

Basic_Character_Animation shows the basic data structure and animation creation pipeline and are required to create an animation clip with provided infrastructure. Also, it shows the use of the mathematics in FK and IK to read the motion capture files and play with them.     

Motion_Processing provide a practical introduction to working with animation data through various algorithms such as interpolation and concatenation. Also, it considers various variables from motion data to enhance the performance of the motion matching method.    


# recommend to use Anaconda to manage enviroment conda create -n comp3360 python=3.8         
conda activate comp3360        
conda install numpy scipy         
pip install panda3d         
# Enviroments verification. After running, you should see a skeleton in a 3D space       
cd ./Basic_Character_Animation                
python env_test.py         

In Basic_Character_Animation,
python task2_forward_kinematic.py       
python task3_inverse_kinematic.py         

In Motion_Processing,
python task1_motion_editing.py      
python task2_motion_matching.py
