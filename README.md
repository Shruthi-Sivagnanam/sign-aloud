# Sign Aloud  - Sign Language Recognition System

## Abstract
The major focus of this project is to create a deep learning-based android 
application that offers sign language translation to text and speech thereby aiding 
communication between signers and non-signers. We use a custom CNN 
(Convolution Neural Network) for recognizing the sign from a live video frame. 
This system can help in public speaking and students with speech impairment.

## Output Screenshots
<div style="margin-right: 30px;" align="center">
<img src="https://github.com/Shruthi-Sivagnanam/sign-aloud/assets/82823305/e5616027-6832-4db4-bafa-5aeda6e9c7ed)" float="left" width="200px" height="500px" />
  &nbsp; &nbsp;
<img src="https://github.com/Shruthi-Sivagnanam/sign-aloud/assets/82823305/b1d948f9-bdbe-4a28-b9fe-6dff4bd260c5" float="left" width="200px" height="500px"/>
  &nbsp; &nbsp;
  <img src="https://github.com/Shruthi-Sivagnanam/sign-aloud/assets/82823305/c9b5d57e-4398-4b71-a859-318cf3bd411c" float="left" width="200px" height="500px"/>
</div>

## Result and Conclusion

The proposed system describes the development of an effective real-time vision based American sign language recognition system for Deaf and Dumb persons. On our dataset, we finally obtained a final accuracy of 92.0%. After implementing of an algorithm that allow us to verify and forecast symbols that are more similar to one another, we are able to better our prediction. In this manner, as long as the symbols are properly displayed, there is no background noise, and the lighting is sufficient, we can almost always recognise all the symbols.

## Further Enchancements

- The detection is controlled with buttons. It can be overcome by introducing the timestamps. If the letter is detected for more than five seconds the letter can be displayed in the text view. The words can be read when a sentence is formed. These modifications can help the users to feel the application more user-friendly.
- The memory storage is nearly 170 MB. As this had been developed in Android Studio IDE, it occupies more storage. The storage can be optimized
- The application can only run in android os. It can be developed in React Native, so that application would be platform independent.
- Few simple hand gestures can be trained for detection. As only ASL has been trained, for simple hand gesture user have to spell the whole word which is time consuming process. The hand gestures which don’t have any clashes with the ASL symbol can be trained
