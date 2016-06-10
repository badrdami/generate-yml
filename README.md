# generate-yml
to generate yml files for face recognitions (Eigen, Fisher, LBPH)

You have tree function to generate yml:
    void eigenFaceTrainer();
    void fisherFaceTrainer();
    void LBPHFaceTrainer();
    
then you have one other function to test recognition:
    int  FaceRecognition();
    
In the VideoCap file , there's functions to add images of a person to the data base by taking a real time video of the person

there is somme extra functions in other files.
