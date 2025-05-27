# Exp5class-MicronBERT
基于Micron-BERT的微表情5分类识别系统  

项目简介：  
本项目通过微调Micron-BERT预训练模型，构建了一个针对微表情识别的 5分类系统（高兴/悲伤/惊讶/愤怒/中性）。   

Micron-BERT 权重下载：  
  https://unioulu-my.sharepoint.com/:u:/g/personal/hkhor19_univ_yo_oulu_fi/ESMDey8S6phAjhltyiGDdO0BUB0FvAYDDJvej6NdrEp3EA?e=vdHIMQ  

数据集为 CasME-II 数据集（预处理版）：  
  https://www.kaggle.com/datasets/muhammadzamancuiisb/casme-2-preprocessed  
包含：200+微表情视频片段（已转换为帧序列）  

运行训练脚本 micron_classifier.py：  
python micron_classifier.py 

模型推理（应用）——使用训练好的模型进行预测：  
python micron_bert_use.py 
  

  
