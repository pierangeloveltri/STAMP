# STAMP
Discovering Spatiotemporal Gene Signatures Across Aging with the STAMP Framework
This repository contains the link to the Graphical User Interface for STAMP. You can run in two different way:

1) Full code and data: to run the GUI of STAMP please download the code and db of the GUI_Stamp tool 
from https://drive.google.com/drive/folders/10_oSYnsHfPSfqheOeHJ-ux607b0woXGh?usp=sharing
then in a Linux environment 
sudo docker run -p 8501:8501 gui_stamp_full
then from your browser link to http://localhost:8501
In this mode, you can use the full interface locally, including the data-generation modules. You can either generate new files and analyze them, or load the pre-computed files described in Section 2.

2) You can also use the online version of the STAMP GUI:
   https://stampgui-n2mm84ueuclex9zggm93jv.streamlit.app/
   To use this interface, you must first download the processed data from Google Drive, because the current web application does not include the data-generation step.
   The dataset has been generated using a switching threshold of 0.5: https://drive.google.com/drive/folders/1lDR84MXooIi2XCcXOwnY9_bKkLFbWbTW?usp=drive_link
   
   
Original Dataset can be downloaded at:  https://gtexportal.org/home/  
