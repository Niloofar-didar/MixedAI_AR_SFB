
Welcome to the Mixed AR-AI project!

![](https://github.com/Niloofar-didar/Mixed_AI_AR/blob/main/MIR-exp-highQ.gif)

This project is aimed at improving the performance of AI and AR by controlling virtual objects' triangle count, which affects the overall GPU usage of the mobile phone to leave enough space for both modules to run their tasks on GPU.
You need to have Android Studio installed on your system. Then, you can download and install the android app on your phone. The app consists of two modules, AR and AI. In the AI module, some AI tasks are run some inferences on input of camera frames.
To use the AR module, you can select the virtual objects from the menu and put them on the screen. The result for AR module, i.e., the overall triangle count of the objects and the GPU usage is stored at GPU_Usage.cvs.
The current version of the app uses the decimated objects from the local storage, so you need to have the decimated version of all the used virtual objects on your phone in the same directory. (Storage/emulated/0/Android/data/com.arcore.MixedAIAR/files).
To generate the decimated version of the objects, you could use the python program provided in "Files related to decimating and converting OBJ to SFB" folder of the project and follow the guide from that directory.
You can see below a screenshot of the app.


![demo](https://user-images.githubusercontent.com/27611369/193911248-1e15edce-d97e-427f-8963-8b02638429ce.jpg)
