# Deep-Learning-Environment-Setup-Windows & Ubuntu

### On Windows
1. Check your GPU model:

Device Manger >> Display Adapter >>

I am using **NVIDIA GeForce RTX 3070**

![image](https://user-images.githubusercontent.com/55071205/152475962-cf15b995-1434-4c45-b71f-fc15d5138073.png)

2. Install Visual Studio Community Edition: I installed 2019 version

https://my.visualstudio.com/Downloads?q=Visual%20Studio%202019

![image](https://user-images.githubusercontent.com/55071205/152482639-9b15985a-f096-4eeb-b663-99236d32a9de.png)


2. Install Nvidia Driver compatible with your Gpu 



3.Check the installed Cuda Version

nvcc -V

![image](https://user-images.githubusercontent.com/55071205/152477689-5d1382dd-3273-42c6-88cb-83adf3b8bf51.png)




4. Search to get the correct version of cudnn

conda search cudnn

![image](https://user-images.githubusercontent.com/55071205/152477868-ecc43e4b-b736-4eea-8c42-b6a46ed9fcaf.png)

5.1 Then install cudnn 

conda install cudnn=8.2.1=cuda11.3_0

![image](https://user-images.githubusercontent.com/55071205/152478139-0475258d-fc14-440a-a4d4-60e16e04091b.png)


* 5.2 Or you can use an alterantive method to install Cudnn from the webistes
* 5.2.1 Choose the Cudnn version that is compatible with the Cuda version

![image](https://user-images.githubusercontent.com/55071205/152501078-2153c9e6-e90f-4a86-a4be-709a71ffc40b.png)

![image](https://user-images.githubusercontent.com/55071205/152501330-8b2ad0f9-2a44-4f11-8cde-cb47e2b2aba9.png)

* 5.2.2 Download the zip file >> unzip the file >> Copy all the file >> Go to the 'Programmingfiles'

![image](https://user-images.githubusercontent.com/55071205/152501930-4333c77e-9ce9-415b-a476-95330240c07a.png)

* 5.2.3 Paste the copied files such as ' bin, include, lib ' to the above destination

6. Install tensorflow

pip install tensorflow 

Check whether tensorflow is recognizing the GPU.  

![image](https://user-images.githubusercontent.com/55071205/152479462-26baeeeb-384d-44fc-8b08-197887d602e4.png)

