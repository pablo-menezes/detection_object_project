# detection_object_project

# Projeto Final - Modelos Preditivos Conexionistas

### Pablo Henrique de Lira Menezes

|**Tipo de Projeto**|**Modelo Selecionado**|**Linguagem**|
|--|--|--|
|Deteção de Objetos| YOLOv5|PyTorch|

## Performance

O modelo treinado possui performance de **:**
                
                Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.16s/it]
                   all        102        116      0.908       0.89      0.904      0.566
                   Car        102         26      0.982      0.962      0.968      0.772
                Cattle        102         33      0.717      0.846       0.81      0.468
                   Dog        102         27      0.995      0.852      0.932      0.501
                People        102         30      0.936        0.9      0.904      0.523


### Output do bloco de treinamento

<details>
  <summary>Click to expand!</summary>
  
  ```text
    Você deve colar aqui a saída do bloco de treinamento do notebook, contendo todas as épocas e saídas do treinamento
  ```
</details>

### Evidências do treinamento

![labels_correlogram](https://user-images.githubusercontent.com/110351146/199569425-d6dbaa98-908e-49f8-af3d-3f567e69ff6e.jpg)

![train_batch0](https://user-images.githubusercontent.com/110351146/199569369-37d7955f-eebf-40ee-bf46-b47b60a1aa7d.jpg)


## Roboflow

https://app.roboflow.com/cesar-school-jtqzc/projeto-deteccao/1

## HuggingFace

https://huggingface.co/spaces/paablo/detection
