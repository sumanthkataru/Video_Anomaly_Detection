# Video_Anomaly_Detection
Video  anomaly  detection  is  one  of  the  most  important  research  areas 
in  surveillance  and  security  systems,  which  identifies  unusual  events 
from  video  streams  with  minimal  human  intervention.  This  work  uses 
state-of-the-art  deep  learning  models  for  effective  detection  of 
anomalous  events  in  surveillance  videos.  Our  work  addresses  the 
problem  of  scarcity  of  labeled  abnormal  data  and  the  contextual 
nature  of  anomalies  to  find  novel  solutions  for  the  improvement  of 
accuracy and efficiency of detection. 
Our  methodology  combines  Convolution  and  Attention  mechanisms 
to  develop  the  Conv-  Attention  model,  which  captures  intricate 
spatiotemporal  dynamics.  This  approach  incorporates  attention 
mechanisms  to  improve  feature  extraction  and  anomaly  prediction. 
The  UCSD  Ped1  dataset  was  the  primary  benchmark,  with  additional 
evaluations  using  other  publicly  available  datasets.  The  project  also 
explored  Conv-LSTM,  which  showed  promising  results  with  a  focus 
on reconstruction-based approaches using lstm also. 
The  performance  of  the  models  was  measured  in  terms  of  AUC-ROC 
metrics,  indicating  that  Conv-Attention  could  potentially  handle  the 
complexity  of  video  sequences.  Despite  the  AUC  value  of  0.65  on  the 
UCSD  Ped1  dataset,  it  was  observed  to  be  prone  to  overfitting  and 
computationally  resource-intensive.  In  the  future,  more  robust 
reconstruction-based  strategies  will  be  explored  and  the  evaluation 
process  will  be  expanded  to  include  various  datasets  for  improved 
generalizability. 
