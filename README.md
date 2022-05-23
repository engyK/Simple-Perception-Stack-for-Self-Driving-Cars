# Simple-Perception-Stack-for-Self-Driving-Cars

**Download the repo**

## Phase 1
1.   to run the normal mode
 write this command in cmd  >>
    **python Lane.py -i inputVideoPath -o outputVideoPath**

2.  to run debug mode
 write this command in cmd  >>
    **python debug.py -i inputVideoPath -o outputVideoPath**
    
3.**Radius of curvature**
we calculated the Radius of curvature given the polynomial fit for both left and right lanes by substituting in the formula 
<a href="https://www.intmath.com/applications-differentiation/8-radius-curvature.php">here</a>
we also scaled the Distance units from pixels to meters; we assumed 7 meters per 400 pixels in the Y direction and 3.7 meters per 255 pixels in the X direction
then we take the average of both curvatures

    
 ## Phase 2
 1.  write the following command in cmd >>
    **python phase2.py -i inputVideoPath -o outputVideoPath**
    
   ### **Note:** the videos must be in the same directory of the python project
   
