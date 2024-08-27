# READ ME
# How to run

Firstly, open the run.ipynb in collab
<a target="_blank" href="https://colab.research.google.com/github/jmp-3/test-notebook/blob/main/run.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

Then, follow the steps bellow:
1. Create a folder in your Google Drive (for example: "my_data")
2. Add your input data file (for example: data.csv) as a csv to this folder in your google drive;

      The input file must be a csv file containing 16 columns, each column must contain in each row the value for the following variables for a patient:

        1. nsyll_pataka
        2. n_pausas_pataka
        3. dur_pataka
        4. phonationtme_pataka
        5. speech_rate_pataka
        6. articulationrate_pataka
        7. asd_pataka
        8. nsyll_monologo
        9. n_pausas_monologo
        10. dur_monologo
        11. phonationtime_monologo
        12. speechrate_monologo
        13. articulationrate_monologo
        14. asd_monologo
        15. pausas_monologo
        16. pause_ratio_monologo

      Each row of the csv file must be a patient.  

2. Edit the PATH_TO_OUTPUT_DIR and PATH_TO_INPUT_FILE in the cell below;
3. Run all cells in this notebook;
4. Predictions will be saved in the output folder indicated in the path.
