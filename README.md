## Trabalho de PDI

### **Diretórios de imagens**
O diretório [ft-DB](ft-DB) possui os dados crús nas dimensões originais. Já  [dataset](dataset) [dataset-augmented](dataset-augmented/) possuem uma pasta ``images`` dentro de cada e um arquivo ``annotations.xml`` com anotações no tipo *CVAT for images 1.1*:
- **dataset**: imagens do dataset redimensionadas para 512x910;
- **dataset-augmented**: imagens augumentadas do dataset a partir do notebook [augumentation.ipynb](augumentation.ipynb);

### **Notebooks:**
- **augumentation**: realiza a augumentação da pasta dataset;
- **normalize-dataset**: histograma equalizado do dataset.


![Dataset augumentado](./augumented_imgs.png)