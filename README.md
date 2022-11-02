# detection_object_project

# Projeto Final - Modelos Preditivos Conexionistas

### Pablo Henrique de Lira Menezes

|**Tipo de Projeto**|**Modelo Selecionado**|**Linguagem**|
|--|--|--|
|Detecção de Objetos| YOLOv5|PyTorch|

## Performance

O modelo treinado possui performance de **:**
                
                  Class      Images   Instances     P           R       mAP50      mAP50-95: 100% 1/1 [00:01<00:00,  1.16s/it]
                   all        102        116      0.908       0.89      0.904      0.566
                   Car        102         26      0.982      0.962      0.968      0.772
                Cattle        102         33      0.717      0.846      0.81       0.468
                   Dog        102         27      0.995      0.852      0.932      0.501
                People        102         30      0.936      0.9        0.904      0.523


### Output do bloco de treinamento


      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
       0/79      14.1G     0.1151    0.03174    0.04983         55        640: 100% 12/12 [00:11<00:00,  1.02it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:03<00:00,  3.44s/it]
                   all        102        116    0.00105      0.244    0.00407   0.000816

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
       1/79      12.6G     0.0815    0.03145    0.04175         42        640: 100% 12/12 [00:08<00:00,  1.36it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:02<00:00,  2.02s/it]
                   all        102        116      0.609      0.123      0.292      0.124

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
       2/79      12.6G    0.06627    0.02788    0.03109         42        640: 100% 12/12 [00:08<00:00,  1.37it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.85s/it]
                   all        102        116      0.329      0.509      0.421      0.217

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
       3/79      12.6G    0.05975    0.02311    0.02622         41        640: 100% 12/12 [00:08<00:00,  1.37it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.48s/it]
                   all        102        116      0.471      0.466      0.507      0.264

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
       4/79      12.6G    0.05754    0.02181    0.01925         40        640: 100% 12/12 [00:09<00:00,  1.22it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.83s/it]
                   all        102        116      0.476      0.495       0.53      0.301

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
       5/79      12.6G    0.05539    0.01966    0.01871         46        640: 100% 12/12 [00:08<00:00,  1.37it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.74s/it]
                   all        102        116      0.562      0.592       0.58      0.262

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
       6/79      12.6G    0.05595    0.01934    0.01514         46        640: 100% 12/12 [00:08<00:00,  1.39it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.45s/it]
                   all        102        116      0.501      0.645      0.583      0.247

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
       7/79      12.6G    0.05343    0.01834    0.01277         36        640: 100% 12/12 [00:08<00:00,  1.38it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.58s/it]
                   all        102        116      0.427      0.419       0.45      0.189

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
       8/79      12.6G    0.05397    0.01981    0.01723         47        640: 100% 12/12 [00:08<00:00,  1.39it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.33s/it]
                   all        102        116      0.106      0.254       0.13     0.0289

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
       9/79      12.6G    0.05604    0.02048    0.01625         48        640: 100% 12/12 [00:08<00:00,  1.38it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.31s/it]
                   all        102        116      0.154      0.303     0.0852     0.0253

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      10/79      12.6G    0.05414    0.01915    0.01579         46        640: 100% 12/12 [00:09<00:00,  1.22it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.34s/it]
                   all        102        116      0.114     0.0848     0.0257    0.00801

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      11/79      12.6G    0.04845    0.01931    0.01409         55        640: 100% 12/12 [00:08<00:00,  1.39it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:02<00:00,  2.04s/it]
                   all        102        116      0.149       0.29      0.133     0.0543

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      12/79      12.6G    0.05352    0.01925    0.01425         39        640: 100% 12/12 [00:09<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.62s/it]
                   all        102        116      0.198      0.415      0.175     0.0614

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      13/79      12.6G    0.05223    0.01902    0.01443         38        640: 100% 12/12 [00:08<00:00,  1.37it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.57s/it]
                   all        102        116      0.335      0.449      0.344      0.159

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      14/79      12.6G    0.04363    0.01895    0.01415         46        640: 100% 12/12 [00:08<00:00,  1.38it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.50s/it]
                   all        102        116      0.306      0.459      0.272     0.0973

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      15/79      12.6G    0.04955    0.01928    0.01459         36        640: 100% 12/12 [00:08<00:00,  1.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.90s/it]
                   all        102        116      0.212      0.366      0.213     0.0823

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      16/79      12.6G    0.04323    0.01864    0.01661         37        640: 100% 12/12 [00:08<00:00,  1.36it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.58s/it]
                   all        102        116      0.399      0.394      0.314      0.139

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      17/79      12.6G    0.04827    0.01935    0.01559         45        640: 100% 12/12 [00:08<00:00,  1.39it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.45s/it]
                   all        102        116      0.489      0.328      0.236     0.0879

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      18/79      12.6G    0.04509    0.01934    0.01442         54        640: 100% 12/12 [00:08<00:00,  1.38it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.61s/it]
                   all        102        116      0.438      0.329      0.272      0.128

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      19/79      12.6G    0.04755    0.01865    0.01367         43        640: 100% 12/12 [00:08<00:00,  1.39it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.41s/it]
                   all        102        116      0.357      0.522      0.469      0.232

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      20/79      12.6G    0.04364    0.01825    0.01127         44        640: 100% 12/12 [00:08<00:00,  1.39it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.55s/it]
                   all        102        116      0.624       0.53      0.575      0.288

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      21/79      12.6G    0.04223    0.01922   0.009697         53        640: 100% 12/12 [00:09<00:00,  1.20it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.46s/it]
                   all        102        116      0.653      0.605      0.623      0.335

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      22/79      12.6G    0.04523    0.01793    0.01129         49        640: 100% 12/12 [00:08<00:00,  1.37it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.35s/it]
                   all        102        116      0.707      0.647      0.626      0.315

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      23/79      12.6G    0.03938    0.01749   0.009891         48        640: 100% 12/12 [00:08<00:00,  1.39it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.48s/it]
                   all        102        116      0.795      0.693      0.735      0.375

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      24/79      12.6G    0.03757    0.01731    0.01066         47        640: 100% 12/12 [00:08<00:00,  1.39it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.41s/it]
                   all        102        116      0.754      0.633      0.727      0.349

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      25/79      12.6G    0.04276     0.0175    0.01223         43        640: 100% 12/12 [00:08<00:00,  1.38it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.49s/it]
                   all        102        116      0.631      0.731      0.691      0.344

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      26/79      12.6G    0.03878    0.01762   0.008436         46        640: 100% 12/12 [00:08<00:00,  1.37it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.53s/it]
                   all        102        116      0.738      0.717       0.78      0.401

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      27/79      12.6G    0.04009    0.01773   0.008725         48        640: 100% 12/12 [00:09<00:00,  1.23it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.64s/it]
                   all        102        116      0.783      0.758      0.793      0.418

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      28/79      12.6G    0.03826     0.0173    0.01016         51        640: 100% 12/12 [00:08<00:00,  1.41it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.66s/it]
                   all        102        116      0.747      0.758      0.778       0.39

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      29/79      12.6G    0.03909    0.01694   0.007784         42        640: 100% 12/12 [00:08<00:00,  1.38it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.43s/it]
                   all        102        116      0.728      0.742      0.767      0.412

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      30/79      12.6G    0.04114     0.0163    0.01132         52        640: 100% 12/12 [00:08<00:00,  1.38it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.36s/it]
                   all        102        116      0.788      0.745      0.756      0.384

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      31/79      12.6G    0.03745     0.0166   0.009564         55        640: 100% 12/12 [00:08<00:00,  1.37it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.43s/it]
                   all        102        116      0.599      0.658      0.618      0.322

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      32/79      12.6G    0.03594    0.01678   0.009048         45        640: 100% 12/12 [00:09<00:00,  1.28it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.72s/it]
                   all        102        116      0.664      0.739      0.728      0.368

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      33/79      12.6G    0.03754    0.01649   0.007342         42        640: 100% 12/12 [00:08<00:00,  1.38it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.64s/it]
                   all        102        116      0.665      0.765      0.752      0.374

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      34/79      12.6G    0.03642    0.01603    0.00981         50        640: 100% 12/12 [00:09<00:00,  1.20it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.57s/it]
                   all        102        116      0.737       0.73      0.763      0.372

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      35/79      12.6G    0.03311    0.01577   0.007368         42        640: 100% 12/12 [00:08<00:00,  1.39it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.52s/it]
                   all        102        116      0.731      0.771      0.806      0.428

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      36/79      12.6G    0.03486     0.0171   0.005858         47        640: 100% 12/12 [00:08<00:00,  1.39it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.54s/it]
                   all        102        116      0.801      0.805        0.8      0.412

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      37/79      12.6G    0.03274    0.01471    0.00796         30        640: 100% 12/12 [00:08<00:00,  1.36it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.49s/it]
                   all        102        116      0.771      0.747      0.756      0.383

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      38/79      12.6G    0.03587    0.01601   0.009067         45        640: 100% 12/12 [00:09<00:00,  1.20it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.53s/it]
                   all        102        116      0.686      0.662      0.725      0.362

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      39/79      12.6G    0.03625    0.01569   0.008992         43        640: 100% 12/12 [00:08<00:00,  1.37it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.63s/it]
                   all        102        116      0.766      0.758      0.795      0.414

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      40/79      12.6G     0.0335    0.01528   0.007344         45        640: 100% 12/12 [00:08<00:00,  1.39it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.45s/it]
                   all        102        116      0.788      0.868      0.825      0.462

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      41/79      12.6G    0.04042    0.01661    0.00664         52        640: 100% 12/12 [00:08<00:00,  1.41it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.53s/it]
                   all        102        116      0.745      0.769      0.762      0.398

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      42/79      12.6G    0.03794    0.01582   0.005538         52        640: 100% 12/12 [00:08<00:00,  1.40it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.58s/it]
                   all        102        116      0.852      0.812      0.836      0.438

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      43/79      12.6G    0.03453    0.01528   0.007785         43        640: 100% 12/12 [00:08<00:00,  1.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:02<00:00,  2.12s/it]
                   all        102        116      0.839       0.78      0.838      0.504

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      44/79      12.6G    0.03501    0.01578   0.006452         45        640: 100% 12/12 [00:08<00:00,  1.37it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.37s/it]
                   all        102        116      0.856      0.842      0.864      0.502

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      45/79      12.6G     0.0343    0.01524   0.005846         39        640: 100% 12/12 [00:08<00:00,  1.40it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.54s/it]
                   all        102        116      0.835      0.802      0.847      0.472

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      46/79      12.6G    0.03345    0.01515   0.007626         46        640: 100% 12/12 [00:08<00:00,  1.38it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.52s/it]
                   all        102        116      0.853      0.754      0.818       0.48

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      47/79      12.6G    0.03378    0.01526   0.006741         47        640: 100% 12/12 [00:08<00:00,  1.39it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.55s/it]
                   all        102        116      0.827      0.791      0.806      0.466

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      48/79      12.6G    0.02819    0.01502   0.006046         45        640: 100% 12/12 [00:08<00:00,  1.40it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.62s/it]
                   all        102        116      0.768       0.81      0.828       0.46

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      49/79      12.6G    0.03131    0.01414   0.005168         38        640: 100% 12/12 [00:09<00:00,  1.24it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.65s/it]
                   all        102        116      0.877      0.831      0.877      0.489

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      50/79      12.6G    0.03152    0.01527   0.007152         50        640: 100% 12/12 [00:08<00:00,  1.37it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.56s/it]
                   all        102        116      0.844      0.828      0.868      0.502

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      51/79      12.6G    0.03426     0.0148   0.006463         43        640: 100% 12/12 [00:08<00:00,  1.37it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.48s/it]
                   all        102        116      0.786      0.753      0.799      0.456

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      52/79      12.6G    0.03103    0.01392   0.004926         37        640: 100% 12/12 [00:08<00:00,  1.39it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.50s/it]
                   all        102        116      0.801      0.785       0.83      0.472

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      53/79      12.6G    0.03189    0.01439   0.005268         38        640: 100% 12/12 [00:08<00:00,  1.39it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.49s/it]
                   all        102        116      0.879      0.796      0.855      0.511

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      54/79      12.6G    0.02975    0.01414   0.004362         44        640: 100% 12/12 [00:09<00:00,  1.33it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:02<00:00,  2.24s/it]
                   all        102        116      0.861       0.85      0.872      0.479

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      55/79      12.6G    0.03273    0.01403   0.005704         50        640: 100% 12/12 [00:08<00:00,  1.38it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.49s/it]
                   all        102        116      0.849      0.876      0.875      0.527

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      56/79      12.6G    0.03363    0.01391    0.00527         41        640: 100% 12/12 [00:09<00:00,  1.20it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.50s/it]
                   all        102        116       0.84      0.871      0.857      0.529

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      57/79      12.6G    0.03127    0.01382   0.003512         50        640: 100% 12/12 [00:08<00:00,  1.38it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.51s/it]
                   all        102        116      0.897      0.856      0.891      0.521

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      58/79      12.6G    0.02871    0.01426   0.003208         52        640: 100% 12/12 [00:08<00:00,  1.37it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.43s/it]
                   all        102        116      0.852      0.864      0.866      0.515

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      59/79      12.6G    0.02702    0.01316   0.003365         38        640: 100% 12/12 [00:08<00:00,  1.38it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.51s/it]
                   all        102        116      0.861      0.837       0.83      0.467

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      60/79      12.6G     0.0278     0.0137   0.003362         49        640: 100% 12/12 [00:09<00:00,  1.25it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.48s/it]
                   all        102        116      0.815      0.848      0.854      0.453

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      61/79      12.6G    0.02722    0.01384    0.00429         44        640: 100% 12/12 [00:08<00:00,  1.37it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.37s/it]
                   all        102        116      0.862      0.868      0.878      0.496

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      62/79      12.6G     0.0275    0.01391   0.003334         41        640: 100% 12/12 [00:08<00:00,  1.37it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.31s/it]
                   all        102        116      0.917      0.839      0.887      0.497

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      63/79      12.6G    0.03028    0.01413   0.003377         57        640: 100% 12/12 [00:08<00:00,  1.39it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.46s/it]
                   all        102        116      0.936      0.869      0.918      0.552

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      64/79      12.6G     0.0283      0.014   0.005079         33        640: 100% 12/12 [00:08<00:00,  1.38it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.29s/it]
                   all        102        116       0.88      0.883       0.88      0.538

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      65/79      12.6G    0.02536     0.0135   0.003244         40        640: 100% 12/12 [00:08<00:00,  1.38it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.34s/it]
                   all        102        116      0.833      0.867      0.849       0.49

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      66/79      12.6G    0.02712    0.01401   0.002138         52        640: 100% 12/12 [00:09<00:00,  1.25it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.56s/it]
                   all        102        116      0.845      0.864       0.88      0.513

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      67/79      12.6G    0.02636    0.01349   0.002829         47        640: 100% 12/12 [00:08<00:00,  1.37it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.49s/it]
                   all        102        116      0.849      0.873      0.899      0.559

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      68/79      12.6G    0.02369    0.01324   0.002702         39        640: 100% 12/12 [00:08<00:00,  1.39it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.27s/it]
                   all        102        116       0.86      0.888      0.905      0.559

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      69/79      12.6G    0.02471    0.01305   0.003314         50        640: 100% 12/12 [00:08<00:00,  1.38it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.47s/it]
                   all        102        116      0.908      0.889      0.904      0.565

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      70/79      12.6G     0.0245     0.0131   0.002226         38        640: 100% 12/12 [00:08<00:00,  1.40it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.58s/it]
                   all        102        116      0.914      0.839      0.903       0.54

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      71/79      12.6G    0.02663    0.01319   0.002483         50        640: 100% 12/12 [00:09<00:00,  1.23it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.60s/it]
                   all        102        116      0.871      0.893       0.91      0.553

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      72/79      12.6G    0.02262    0.01234    0.00395         52        640: 100% 12/12 [00:08<00:00,  1.38it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.49s/it]
                   all        102        116      0.872       0.87      0.889      0.536

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      73/79      12.6G    0.02475    0.01301   0.002775         45        640: 100% 12/12 [00:08<00:00,  1.38it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.45s/it]
                   all        102        116      0.843      0.897       0.89      0.516

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      74/79      12.6G    0.02487    0.01274   0.005667         44        640: 100% 12/12 [00:08<00:00,  1.40it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.51s/it]
                   all        102        116       0.84      0.896      0.891       0.52

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      75/79      12.6G    0.02188    0.01273   0.002471         45        640: 100% 12/12 [00:08<00:00,  1.39it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.43s/it]
                   all        102        116      0.899      0.883      0.901      0.524

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      76/79      12.6G    0.02314    0.01242   0.002397         38        640: 100% 12/12 [00:08<00:00,  1.37it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.49s/it]
                   all        102        116      0.908      0.879      0.913      0.533

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      77/79      12.6G    0.02535    0.01282   0.004826         50        640: 100% 12/12 [00:09<00:00,  1.21it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.57s/it]
                   all        102        116      0.919      0.868      0.905      0.527

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      78/79      12.6G    0.02515      0.013   0.002582         43        640: 100% 12/12 [00:10<00:00,  1.19it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.87s/it]
                   all        102        116      0.881       0.88        0.9      0.514

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      79/79      12.6G    0.02462    0.01254   0.003962         45        640: 100% 12/12 [00:08<00:00,  1.36it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.52s/it]
                   all        102        116      0.899      0.876        0.9      0.519

80 epochs completed in 0.248 hours.
Optimizer stripped from runs/train/exp/weights/last.pt, 14.5MB
Optimizer stripped from runs/train/exp/weights/best.pt, 14.5MB

### Evidências do treinamento

![labels_correlogram](https://user-images.githubusercontent.com/110351146/199569425-d6dbaa98-908e-49f8-af3d-3f567e69ff6e.jpg)

![train_batch0](https://user-images.githubusercontent.com/110351146/199569369-37d7955f-eebf-40ee-bf46-b47b60a1aa7d.jpg)


## Roboflow

https://app.roboflow.com/cesar-school-jtqzc/projeto-deteccao/1

## HuggingFace

https://huggingface.co/spaces/paablo/detection
