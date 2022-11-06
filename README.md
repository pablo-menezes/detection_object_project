# detection_object_project

# Projeto Final - Modelos Preditivos Conexionistas

### Pablo Henrique de Lira Menezes

|**Tipo de Projeto**|**Modelo Selecionado**|**Linguagem**|
|--|--|--|
|Detecção de Objetos| YOLOv5|PyTorch|

## Performance

O modelo treinado possui performance de **:**
                
                   Class     Images    Instances    P          R         mAP50     mAP50-95: 100% 1/1 [00:01<00:00,  1.09s/it]
                   all        102        116      0.918      0.845       0.91      0.548
                   Car        102         26      0.975      0.962      0.968      0.758
                Cattle        102         33      0.866      0.818      0.855      0.491
                   Dog        102         27      0.914      0.852      0.935      0.462
                People        102         30      0.918      0.749       0.88      0.482


### Output do bloco de treinamento


     ?????

### Evidências do treinamento

![labels_correlogram](https://user-images.githubusercontent.com/110351146/199569425-d6dbaa98-908e-49f8-af3d-3f567e69ff6e.jpg)

![train_batch0](https://user-images.githubusercontent.com/110351146/199569369-37d7955f-eebf-40ee-bf46-b47b60a1aa7d.jpg)


## Roboflow

https://app.roboflow.com/cesar-school-jtqzc/projeto-deteccao/1

## HuggingFace

https://huggingface.co/spaces/paablo/detection
