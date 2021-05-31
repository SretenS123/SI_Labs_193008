# SI_Labs_193008
Втора Лаб вежба по Софтверско Инжинерство
Сретен Стрезовски 193008
Control Flow Graph

![1 1](https://user-images.githubusercontent.com/80340197/120225493-a4e5fd00-c245-11eb-8ea4-918aac2e1ae2.png)

Цикломатска комплексност
Цикломатската комплексност на графот е 8. 
Се бележи на три начини:
1.	Според бројот на региони, кој е еднаков на 8
2.	Според формулата: V(G) = E – N + 2 V(G) = 26 – 20 + 2 = 8 -Каде што Е е бројот на врски, а N е бројот на јазли во графот
3.	Според друга формула: V(G) = P + 1 V(G) = 7 + 1 = 8 -Каде што P е бројот на предикатни јазли, кои во CFG се 2.2, 3, 4, 7, 8, 10, 13.
Multiple Condition
If(hr<0 || hr>24)

![2](https://user-images.githubusercontent.com/80340197/120225503-a8798400-c245-11eb-9766-a3f63532e7d3.png)

If(min<0 || min>59)

![3](https://user-images.githubusercontent.com/80340197/120225519-aca5a180-c245-11eb-8188-1bf1628c2cf7.png)

If(sec>=0 && sec<=59)

![4](https://user-images.githubusercontent.com/80340197/120225524-ae6f6500-c245-11eb-9d0f-d1c87a734176.png)

If(hr==24 && min==0 &&sec==0)

![5](https://user-images.githubusercontent.com/80340197/120225526-af07fb80-c245-11eb-935f-72061d20c621.png)
