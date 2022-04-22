## LINK : https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6487545

# Topic : DESIGN OF A EMG WIRELESS SURFACE EMG 6 CHANNELS

## Summary of Research paper: 
1)	The objective of the paper is to develop a system for recording EMG signals from the area of the back. Currently, the detection of wrong posture is not headed to study every muscle involved in a particular work activity The use of these method generates a high variability on results as for observer, as for the patient. 
2)	This paper developed a wireless EMG that can collect signals from six back muscles and identify whether a posture is correct or incorrect.
3)	It was decided to use data-receiving software. This technology records the patient's muscles in his normal sitting position for a minute, then the patient rests for five minutes before the data is collected again, this time with the patient in perfect sitting posture.
4)	Authors are using following devices to gather and process the data-:
    A.	Electrodes
    B.  Pre-Amplification- Authors used INA129 instrumentation amplifier due to performance, considering previously the characteristics of the human body.
    C.	Signal Conditioning . Coding, ADC and transmission using MC908ap16abcd.
    D.	Receive Data and Visualization- It was shown that the development of the project in processing the response signal was too slow to program all the needs required in this medical equipment. Therefore a program was used to establish the labview as an executable, this consisted of a friendly interface that could implement a system of sending emails
    E.	Acquision labview- To collect data matrices were available in this case is how much data was analyzed in 1 minute receiving time at which the test is performed so arranged EMG and the matrix (6 x 50000 data channels), [10] which are then routed to a Excel workbook to keep track and to analyze the data later, as they can be routed to an email from visual Basic interface.

## Limitations-:
1. Small data set used,only 21 students.
2. Only 80.92% of overall accuracy We have to improve accuracy
3. 8.31% mean square error,We should try to reduce the error.
