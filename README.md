## EXP.NO.3.-IMPLEMENTATION-OF-DELTA-MODULATION

3.Implementation of Delta Modulation 
  
## AIM:  

 To study the Delta modulation using the Delta Modulation trainer kit. 
 
## APPARATUS REQUIRED:

Trainer Kit, DSO(10MHz) , Patch Cords and Power Supply (0-30V) 

## PROCEDURE:

1.Delta Modulation (DM) is a simple technique for converting analog signals into digital form. In DM, the analog signal is sampled at a rate much higher than the Nyquist rate. Instead of encoding the absolute value of each sample, DM encodes the difference between the current input and the previous output. 

2.This difference is represented by a single bit: if the signal is rising, a '1' is transmitted; if it is falling, a '0' is transmitted. The receiver uses this stream of bits to reconstruct the signal by incrementing or decrementing the previous value by a fixed step size.

3.A low-pass filter then smooths the staircase output to recover the analog waveform. DM is simple and requires less bandwidth than PCM but can suffer from slope overload distortion if the signal changes rapidly, and granular noise if the step size is too large for slowly varying signals. 

4.Adaptive methods can improve performance.

## CIRCUIT DIAGRAM:
![image](https://github.com/user-attachments/assets/3d9cc6ff-8d44-4e65-b0f5-5498d0a1a35e)


## MODEL GRAPH:
![image](https://github.com/user-attachments/assets/e93f994b-5fab-4823-a621-8959d96d58c5)


## TABLE:
![WhatsApp Image 2025-04-28 at 21 16 43_2e17eb70](https://github.com/user-attachments/assets/d77dbad8-72a3-4db4-a484-6adaedfc72d0)



## OUTPUT GRAPHS:
![WhatsApp Image 2025-04-28 at 21 16 11_e40b32f6](https://github.com/user-attachments/assets/7b6e0907-02a9-4c34-aec2-d6ce3337a016)



## RESULT:
Thus, the delta modulation is studied and the delta modulated waveform is obtained.
