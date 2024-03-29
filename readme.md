# PRESTem   

If your matlab version is R2020b, run the PRESTem.exe file, otherwise run the MyAppInstaller_web.exe file.   


## Usage   

1. Click the Menu toolbar and press the File Open button   
<img src= "././imgs/file_open.png" width="50%" height="50%">

   
2. Select the image you want to analyze.   

    If you want to analyze ABF and HAADF images at the same time, please select images at the same time.   
    
        
3. Enter the parameters of the image.
 
<img src= "././imgs/parameter.png" width="30%" height="30%">

   If you don't know the exact parameters of the structure, fill in with 0 and press OK button.
   
<img src= "././imgs/parameter_2.PNG" width="30%" height="30%">
 
<img src= "././imgs/parameter_3.PNG" width="30%" height="30%">

   Then, crop the unit cell into the main figure. pm/pixel is set to 10 and lattice is set to cropped unit cell size.
<img src= "././imgs/unit_cell.PNG" width="50%" height="50%">
  
4. Press the Click button or Drag add button to segment atoms.   
   As for the Click button function, the left mouse button is an add function, the right mouse button is a remove function, and the mouse wheel button or the esc key is an end function.
<img src= "././imgs/segmentation.png" width="50%" height="50%">
</br> 
5. Press the Select button and drag to select a unit cell.
<img src= "././imgs/select.png" width="50%" height="50%">
 
 
6. Enter the atomic information of the unit cell.   
   Atomic selection works the same way as a click button.
<img src= "././imgs/select_2.png" width="50%" height="50%">

7. Check that the atomic information is entered correctly and click the Run button.   
   If the atomic peak is not correct, please press the Re Seg button.
<img src= "././imgs/run.png" width="50%" height="50%">

8. The Analysis Results window appears.   
   If the atomic peak is wrong, correct it and click the run button again.   
   If you also selected the ABF image, press the ABF button, and then press the Run button again.
   For more accurate analysis, it is recommended to press the ABF button and then the Re Seg button before pressing the RUN button.

<img src= "././imgs/run_2.png" width="80%" height="80%">

   The analysis results are saved in the result folder.
   


