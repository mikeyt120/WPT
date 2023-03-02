# WPT
Wave Peel Tracking algorithm applied to a wave basin

![WPT_lab_img](https://github.com/mikeyt120/WPT/blob/main/WPT_lab_img.JPG)

To run the WPT algorithm, download the entire WPT repository into a directory where you have access through Anaconda Distribution. Through Anaconda Distribution -> Jupyter Notebooks, open the WPT_lab.ipynb script. Once the script is open in a notebook, run the first cell to initialize variables and produce a rectification image example. Click on one of the images shown and press enter to finish running that cell. Then run the next cell to start the WPT algorithm. A few windows will appear which will visualise the WPT algorithm in action. Once the WPT algorithm has processed the whole video, run the next cell to post process the data to create WPT stats and figures. All these stats and figures will be saved in a results folder.

If you need to train a new CNN model for your use of the WPT algorithm, use the WPT_lab_CNN_trainer.ipynb script. 

Tracking parameter settings and classification model settings for each test in the paper are described in "Algorithm Key Parameters for Each Test.docx" and "Classification_model_results.docx" (accompanied by "WPT_CNN_lab_best_results.xlsx").

Note: The SM2p2_comp.mp4 video provided is a compressed version of the original test SM2.2 video, therefore the results for SM2.2 in the paper may be very slightly different (but not by much). This video is made available courtesy of the Queensland Government Hydraulics Laboratory.

Fig9_individual_plots and Fig10_individual_plots include all individual WPT plot related to Figures 9 and 10 respectively in the journal paper. Note that the background depth contours in the plots are at model scale and the axis are at prototype scale.
