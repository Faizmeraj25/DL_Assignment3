# DL_Assignment3

## Instructions to run the seq_2_seq_model.ipynb file: 
- Run the given file in the sequence order of all the cells.
- Run all the functions in the sequence.
- In last, after the 'run_sweep_without_attention' function, run the cell below it if wanted to run on default configuration for a single run.
- In case, if sweep is required to run, then run the cell with 'sweep_config' dictnionary and then run the cell below it containing sweepid. 
- In order to create the prediction.csv file run the cell with function 'infer' and the one below it to call the 'infer'.
- It would generate a csv file with name 'prediction.csv' which contains Input English word, Output Hindi word & Target Hindi word in separate columns for all the test dataset words. 



## Instructions to run the seq_2_seq_Attention.ipynb file:
- Run the given file in the sequence order of all the cells.
- Run all the functions in the sequence.
- In last, after the 'run_sweep_with_attention' function, run the cell below it if wanted to run on default configuration for a single run.
- In case, if sweep is required to run, then run the cell with 'sweep_config_attn' dictnionary and then run the cell below it containing sweepid. 
- In order to create the prediction_attention.csv file run the cell below sweepid cell to call the 'infer'.
- It would generate a csv file with name 'prediction_attention.csv' which contains Input English word, Output Hindi word & Target Hindi word in separate columns for all the test dataset words. 


Source of References : 
https://www.youtube.com/watch?v=sQUqQddQtB4
https://pytorch.org/tutorials/intermediate/seq2seq_translation_tutorial.html
