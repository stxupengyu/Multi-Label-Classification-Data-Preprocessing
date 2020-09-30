# Milti-Label-Classification-Data-Preprocessing
对于多标签分类数据集的预处理。Data preprocessing for multi label classification.  
Eurlex_data_analysis.ipynb实现了对Eurlex数据集的预处理，统计了所有共同出现过的二元组，以及其频次。最后以.csv文件输出。  
Eurlex_Label2Glove_Embedding.ipynb实现了将Eurlex数据集的每个标签划分为多个单词，继而通过glove embedding提取其语义信息。最后输出每个标签对应的glove embedding。  
Label2Glove_Embedding.ipynb与Eurlex_Label2Glove_Embedding.ipynb几乎一样，区别在于其处理的数据集更简单。  

