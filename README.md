# hse21_hw3
I часть: https://colab.research.google.com/drive/1jmIFCTqD4-Pa1s1oCnnrQq_2ebqnFAdQ?usp=sharing

## Статистика с MultiQC

![image](https://user-images.githubusercontent.com/86663451/145616821-eddbaa26-bf3f-447d-be29-f8ec798e5ed4.png)

Можно заметить, что в наших данных довольно много дубликатов.

![image](https://user-images.githubusercontent.com/86663451/145616884-4fd0ac73-c1c6-4299-8760-28a3413458a5.png)

Среднее качество хорошее: всё время держится в зелёной зоне.

![image](https://user-images.githubusercontent.com/86663451/145617018-429ef0a6-ecc3-4eea-9999-67ffba931b31.png)

Однако меня как-то почему-то смущает такое распределение GC состава.

![image](https://user-images.githubusercontent.com/86663451/145617100-b3f4838b-d2f4-4e8f-ad41-a2edb2ede77b.png)

Как можно видеть, в данных ооочень мало гэпов.

![image](https://user-images.githubusercontent.com/86663451/145617182-76020fc8-3ec7-414a-9413-88d93c46c2ca.png)

А вот duplication level, как я уже говорил, оставляет желать лучшего.

## Общая таблица со статистикой

| ID sample | Type  | Total number of initial readings | Mapped reads | Uniquely mapped reads | Matches |
|----------|:-------:|:----------------:|:----------------:|:----------------:|:----------------:|
| **SRR3414629** | reprogrammed | 21106089 | 20510113 | 18375888 | 16049609 |
| **SRR3414630** | reprogrammed | 15244711 | 14832680 | 13186139 | 11465324 |
| **SRR3414631** | reprogrammed | 24244069 | 23547686 | 20928945 | 18408851 |
| **SRR3414635** | control | 20956475 | 10395865 | 18428317 | 16275997 |
| **SRR3414636** | control | 20307147 | 19757059 | 17825380 | 15757580 |
| **SRR3414637** | control | 20385570 | 19847291 | 17844858 | 15736978 |

II часть: https://colab.research.google.com/drive/1bYcJcdM7h-lrldVjK6l3JpVHY81PlM3k?usp=sharing

Pheatmap:

![image](https://user-images.githubusercontent.com/86663451/145627100-29ccba65-e3b3-46a9-987e-07746f202969.png)

MA-график:

![image](https://user-images.githubusercontent.com/86663451/145627029-6d6ef92d-d145-4b5c-bc63-d5cf39a9917b.png)

Графики со значениями "Normalized counts":

![image](https://user-images.githubusercontent.com/86663451/145628445-3e74b33a-b7da-4820-8961-a6fffff53613.png)

![image](https://user-images.githubusercontent.com/86663451/145628483-93a9f00e-c96d-44b8-879d-71462be1a688.png)

![image](https://user-images.githubusercontent.com/86663451/145628529-0fc215c8-bb09-47dc-9020-d17839495756.png)

![image](https://user-images.githubusercontent.com/86663451/145628575-2467aa48-4069-40fd-93c8-8d6209f5d81d.png)

![image](https://user-images.githubusercontent.com/86663451/145628633-cdd15391-b285-461a-a43d-e14be0833364.png)
