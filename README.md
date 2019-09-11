
to train model using: 
  1- Bilstm:
              python main.py -tr1 bilstm
              
  2- CRF:
              python main.py -tr1 crf
              
  3- Bilstm-CRF:
              python main.py -tr1 bilstm-crf
              
  4- Bilstm-CNN:
              python main.py --train BILSTM-CNN
 
 
 To test model using :
   1- Bilstm:
              python main.py -test1 bilstm
              
  2- CRF:
              python main.py -test1 crf
              
  3- Bilstm-CRF:
              python main.py -test1 bilstm-crf
              
  4- Bilstm-CNN:
              python main.py -t BILSTM-CNN
              
 
- Datasets: Chinese NER,Resume NER,conll2003 dataset.
- Config file contains all the parameters needed for training.
- the output results will be in the output.txt file.
- evaluting the performance and testing using evaluate.py.

        
