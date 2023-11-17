# Open-Source PKU Respiratory Sound Dataset

This repository contains an open-source respiratory sound dataset.  

The audio files are compressed and stored in `./Audio Files/`. Each file name is divided into **patient ID** and **recording index**, separated with hyphens (-). For example, `11-2.wav` means that patient ID is 11 and this is the second audio file from him/her. Each audio file has a text file with the same name. The .txt files, stored in `./TXT Files/`, contain information about the beginning and end of the breathing cycles. Each file comprises two columns, such as the following:  
```
  1.17	2.68  
  2.68	4.91  
  4.91	7.09  
  7.09	10.03  
  16.03	18.60
```
The two columns separated by `tab` are beginning time and end time of breathing cycles. 

In `audio_file_labels.csv`, you can find the respiratory sound type. In `patient_information.csv`, you can find the patient information: disease, gender and age. The abbreviations used in the patient information file are:
- COVID: Coronavirus Disease 2019
- Abscess: Pulmonary Abscess
- AHRF: Acute Hypoxemic Respiratory Failure
