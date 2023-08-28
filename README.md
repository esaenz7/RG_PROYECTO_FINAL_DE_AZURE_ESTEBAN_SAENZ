# RG_PROYECTO_FINAL_DE_AZURE_ESTEBAN_SAENZ

* Proyecto final curso Azure Datapath.
* PF_ESTEBAN_SAENZ_20230827
* Esteban Sáenz V. (esaenz7@gmail.com).
* [Repositorio en github](https://github.com/esaenz7/RG_PROYECTO_FINAL_DE_AZURE_ESTEBAN_SAENZ.git).

## Antecedentes
Este proyecto consiste en un flujo de datos ETL, el cual permite obtener las fuentes de un repositorio local, almacenándolas en la primera capa (bronze) de un datalake. Seguidamente, los datos son unidos en un único conjunto en la segunda capa (silver), para que finalmente sean transformados, preparados - a través de un notebook y un job de spark - y almacenados en la tercera capa (gold).
A partir de esta capa los datos pueden ser utilizados como insumos para modelos análiticos, tableros de información, o modelos de IA.

### Azure Storage Account 
* Contenedor y capas:
![image](https://github.com/esaenz7/RG_PROYECTO_FINAL_DE_AZURE_ESTEBAN_SAENZ/assets/72483241/7af9c6ae-6d54-491e-a10e-522ff244ea45)
* Capa bronze luego de la ejecución del pipeline:
![image](https://github.com/esaenz7/RG_PROYECTO_FINAL_DE_AZURE_ESTEBAN_SAENZ/assets/72483241/c8a6a8c0-b6a7-49ea-815a-36d224447e20)
* Capa silver luego de la ejecución del pipeline:
![image](https://github.com/esaenz7/RG_PROYECTO_FINAL_DE_AZURE_ESTEBAN_SAENZ/assets/72483241/cdde84c5-cbb2-461f-a35c-11d7d897f4eb)
* Capa gold luego de la ejecución del pipeline:
![image](https://github.com/esaenz7/RG_PROYECTO_FINAL_DE_AZURE_ESTEBAN_SAENZ/assets/72483241/6dd9a900-76fd-4afa-952c-1bfa636e99b3)

### Azude Data Factory
* Configuración GIT
  * Main branch (Data Factory):
  ![image](https://github.com/esaenz7/RG_PROYECTO_FINAL_DE_AZURE_ESTEBAN_SAENZ/assets/72483241/c28448d3-5843-4bdf-b8b4-e96e89d420fc)
  * Synapse branch (Synapse):
  ![image](https://github.com/esaenz7/RG_PROYECTO_FINAL_DE_AZURE_ESTEBAN_SAENZ/assets/72483241/69173b14-6326-4b51-9238-1a8d772c7014)
* Linked Services:
![image](https://github.com/esaenz7/RG_PROYECTO_FINAL_DE_AZURE_ESTEBAN_SAENZ/assets/72483241/64545238-ce7b-4059-a00e-d4692d8f465c)
* Integration runtime:
![image](https://github.com/esaenz7/RG_PROYECTO_FINAL_DE_AZURE_ESTEBAN_SAENZ/assets/72483241/0a0f08fd-acf8-4da4-82fc-2799bc025d0c)
* Key vaults:
![image](https://github.com/esaenz7/RG_PROYECTO_FINAL_DE_AZURE_ESTEBAN_SAENZ/assets/72483241/e6a2b1a0-6ee1-4c0f-b08d-615151e208a9)
* Data sets:
![image](https://github.com/esaenz7/RG_PROYECTO_FINAL_DE_AZURE_ESTEBAN_SAENZ/assets/72483241/e685546e-daab-429c-93ce-697ae49ac90f)
* Dataflow:
![image](https://github.com/esaenz7/RG_PROYECTO_FINAL_DE_AZURE_ESTEBAN_SAENZ/assets/72483241/66aed02b-cf54-47c0-939d-696e2639c702)
* Notebook de transformación y preparación en Synapse:
![image](https://github.com/esaenz7/RG_PROYECTO_FINAL_DE_AZURE_ESTEBAN_SAENZ/assets/72483241/eb44a4d9-244c-4106-b896-0dff7655d115)
![image](https://github.com/esaenz7/RG_PROYECTO_FINAL_DE_AZURE_ESTEBAN_SAENZ/assets/72483241/6efe0e80-9ffc-4c76-bb35-b529c1e98324)
![image](https://github.com/esaenz7/RG_PROYECTO_FINAL_DE_AZURE_ESTEBAN_SAENZ/assets/72483241/27ddf9c1-d496-4302-b7b1-4a6dae52bcbc)
![image](https://github.com/esaenz7/RG_PROYECTO_FINAL_DE_AZURE_ESTEBAN_SAENZ/assets/72483241/82d991da-6ca9-4dba-8f14-30f85414365a)
* Pipeline:
![image](https://github.com/esaenz7/RG_PROYECTO_FINAL_DE_AZURE_ESTEBAN_SAENZ/assets/72483241/8c3d1431-873f-4a97-9241-7f7c541c9f6e)
![image](https://github.com/esaenz7/RG_PROYECTO_FINAL_DE_AZURE_ESTEBAN_SAENZ/assets/72483241/698937b0-7330-4ade-bb2b-743b84f870ac)
* Trigger:
![image](https://github.com/esaenz7/RG_PROYECTO_FINAL_DE_AZURE_ESTEBAN_SAENZ/assets/72483241/7f772442-a8e7-4bfe-8da4-0bc50e01db37)
* Vista de las fuentes de datos iniciales (locales):
![image](https://github.com/esaenz7/RG_PROYECTO_FINAL_DE_AZURE_ESTEBAN_SAENZ/assets/72483241/6af010d4-411a-49df-98ec-1bca4ae6fa81)
* Vista del dataset final (gold):
![image](https://github.com/esaenz7/RG_PROYECTO_FINAL_DE_AZURE_ESTEBAN_SAENZ/assets/72483241/58e651b0-dddc-4f4c-9b3c-66b0f687f010)

---

