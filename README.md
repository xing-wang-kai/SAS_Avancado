# SAS_Avancado

## CALCULANDO IDADE

## TIPOS DE ENTRADAS DE DATAS

### ENTRADA YYMMDD10.

Podemos declarar formatos especificos de datas com o formato YYMMDD10. O 10. significa que o formato contém 10 caracteres e representa o formato ex. ( YYYY-MM-DD ) contando com os **dash**

YYMMDD10. = 2022-10-13
Entrada
![image](https://github.com/user-attachments/assets/274395d2-f029-4e97-aa5b-47af2fab589c)

Saída
![image](https://github.com/user-attachments/assets/c667efc5-a6f3-4aec-a79d-c06104eff4e3)

### ENTRADA DDMMYYD10.

DDMMYYD10. == 12-12-2022
Usando uma maskacar com o formato esperado da data podemos ter uma saída com o formato desejado. no caso do teste abaixo podemos colocar o D antes do 10 para falhar que quermos uma saída visual na mascará com DASHs.


Entrada
![image](https://github.com/user-attachments/assets/1bf7e8de-48d2-48ea-8abe-8e6cd5c8ed8d)

Saída
![image](https://github.com/user-attachments/assets/02898f19-c559-4d40-9762-f195f0aa1a94)


### ENTRADA DATE9.
O formato DATE9 retorna o mome do mês resumido por extenso o que ajuda a informar com mais detalhes informações sobre a datas.

DATE9. = 03MARC2023 

entrada

![image](https://github.com/user-attachments/assets/3dd7273a-21f4-43ec-b31c-ff33a70d4fb7)

Saída

![image](https://github.com/user-attachments/assets/31e10de1-3739-4451-90c8-ab8b5eb2d9d3)

### ENTRADA YYMMN.

O formato data YYMMN o N representa que não terá nenhum simbolo para informar a data

YYMMN. = 202212

ENTRADA:

![image](https://github.com/user-attachments/assets/cceeac61-9045-44ec-9eb8-7d85162cdc25)

SAÍDA

![image](https://github.com/user-attachments/assets/4c2b6ead-8f84-4384-8cb0-3e325a22b98e)

### ENTRADA DDMMYYD10. 
#### FUNCTION TODAY()
#### FUNCTION MDY(YYYY, MM, DD)

Neste formato a data com o final D retorna somente o total de dias que teve no tempo até o momento da introdução da data.

Retona a data como o dia de hoje
MDY define uma data especifica que precisamos retornar.

ENTRADA: 

![image](https://github.com/user-attachments/assets/cd4552aa-066f-4bb5-a9ae-0bed58cc5d33)

SAÍDA: 

![image](https://github.com/user-attachments/assets/0f1f72a0-41b8-49d6-a2bf-42ef17a3d5c2)

ENTRADA: 
![image](https://github.com/user-attachments/assets/8e95bda1-4e31-48f6-8c8d-8c7ffe7397b9)

SAÍDA:
![image](https://github.com/user-attachments/assets/78d38035-c133-4bc4-89fc-a92776d5eec7)



