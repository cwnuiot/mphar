# mphar
The research team has collected the tag response feature data of twenty-one human activities with the largest number in the bound-RFID HAR so far, thus obtaining the human activity dataset CWNU-MPHAR based on the body RFID skeleton. The twenty-one human activities include the posturechanging activity and the postural-constant activity. There are seventeen kinds of posture-changing activities, such as "standing to crouching," "crouching to standing," "standing to stooping," "standing and stooping," and so on. Some of these activities are quite similar, such as "stride away with swinging arms" and "stride away without swinging arms." The posturalconstant activity includes "standing," "sitting," "crouching" and "lying." The dataset which reflects the polymorphism of human activity is beneficial to improve the generalization ability of HAR model.


An example of data

     Each tag response record in the dataset includes the EPC, timestamp, Dopler Frequency, RSSI, Phase, and the activity number (label) used to identify the activity.

Example:
                0010 1667632738934513 78.0625 -64.5 5.884350302329319 0
                0009 1667633437037975 -15.375 -77.5 4.424000592262189 1
                0008 1667634721907184 25.125 -74.5 1.9819031779482483 2
                0004 1667635276410115 -0.75 -74.5 0.19634954084936207 3
                0015 1667635970702292 -65.0625 -64.0 3.06182565261974 4
                
                
