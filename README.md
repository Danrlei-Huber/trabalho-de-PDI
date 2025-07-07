## Trabalho de PDI

### **Diretórios de imagens**
O diretório [ft-DB](ft-DB) possui os dados crús nas dimensões originais com subdiretórios para cada classe de fruta. Já [dataset](dataset) [dataset-augmented](dataset-augmented/) possuem uma pasta ``images`` dentro de cada contendo todas as imagens e um arquivo ``annotations.xml`` com anotações no tipo *CVAT for images 1.1*:
- **dataset**: imagens do dataset redimensionadas para 512x910;
- **augmented_dataset**: imagens augumentadas do dataset a partir do notebook [augumentation.ipynb](augumentation.ipynb);
- **normalized_dataset**: imagens do dataset criadas a partir da equalização de histogramas.

### **Notebooks:**
- **augumentation**: realiza a augumentação da pasta dataset;
- **normalize-dataset**: processo para equalização de histograma do dataset.



![Dataset aumentado](./augumented_imgs.png)
=======
## Imagens

Mosaico do dataset aumentado. As transformações (quando espaciais) foram aplicadas nas _bounding boxes_ também:

![Dataset aumentado](./augumented_imgs.png)
---

Exemplo de uma imagem com histograma equalizado:

![image](https://github.com/user-attachments/assets/e59b9b92-e913-43d7-8e22-100b480599a1)