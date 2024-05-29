Diffusion mdel + YOLO

Note: The images included are made by prompt givem by me 

step 1:
using following commands you can donwload yolov9 model(same has been included in ipynb file also) 

!git clone https://github.com/SkalskiP/yolov9.git </br>
!pip install -r yolo9/requirements.txt -q

and 
Also download the weights from these link given below:-
you can use any one to get predictions

https://github.com/WongKinYiu/yolov9/releases/download/v0.1/yolov9-c.pt
https://github.com/WongKinYiu/yolov9/releases/download/v0.1/yolov9-e.pt
https://github.com/WongKinYiu/yolov9/releases/download/v0.1/gelan-c.pt
https://github.com/WongKinYiu/yolov9/releases/download/v0.1/gelan-e.pt

after downloading place in weights folder

the above commnd will create yolov9 folder which will contain model

step 2: run the file named GAN_YOLO.ipynb

step 3: give prompt

sttep 4(bug): you might need to chaange output folder name from exp to what it is currently (ususlly its name increment with +1 eg. (exp2, exp3, etc))
