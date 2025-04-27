# Redes Temporais de Co-Autoria

## Autores: 
### • Lucas Garcia Costa   

### • Maurício Matheus Araújo Silva Galvão  

Link do vídeo de explicação: https://drive.google.com/drive/u/0/folders/1wRX3CzMqgV-vRoV5M9_VavyTttBIDMgL

Neste projeto foram analisadas cuidadosamente redes temporais de co-autoria nos seguintes formatos:

• Anuais (2010-2025);   

• Trienais; 

• Quadrienais;   

• Geral.     



### Na Base de dados com redes temporais de co-autoria anuais foram estudados:  



• Número de vértices;

• Número de arestas;   

• Número médio de vizinhos;  

• Densidade da rede;    

• Distribuição do número médio de vizinhos.    

  
  
Para uma visualização precisa utilizamos bibliotecas do Python como Matplotlib e Joyplot para plotagem, fazendo inicialmente um gráfico único contendo detalhadamente 4 das métricas mencionadas, além de utilizar uma IA generativa como o ChatGPT-4.1 para explorar novos métodos dessas bibliotecas com o intuito de aplicar melhorias aos gráficos já feitos.  

### Exemplo de prompt utilizado: 

![image](https://github.com/user-attachments/assets/73c6d02b-c769-40ce-90f0-62741915f1c1)  

### Gráfico de 4 curvas:



![image](https://github.com/user-attachments/assets/8236914e-7333-49bb-9d29-6ce5df85f9f8)


Em seguida, foi feito um histograma inicial para visualização da distribuição do número de vizinhos.


![image](https://github.com/user-attachments/assets/d0884a91-100c-45b6-aeae-616406cb9bc6)


Após esse histograma fizemos um Ridgeline Chart contendo detalhadamente, de forma mais visível o comportamento da distribuição do número de vizinhos, ou distribuição de grau de cada rede de co-autoria (2010-2025).


![image](https://github.com/user-attachments/assets/29162a5a-f8df-4a8b-9b43-81001d361fa9)



### Na Base de dados com redes temporais de co-autoria trienais e quadrienais foram realizadas as seguintes análises:

• Destacamos os 5 vértices com mais vizinhos;  
• Pintamos as arestas de vermelho caso conectassem dois membros permanentes, e de preto caso contrário;  
• Tornamos as larguras das arestas proporcionais às quantidades de citações.  


### Grafo trienal 2010-2012 com os 5 vértices destacados e arestas com larguras e cores definidas

![image](https://github.com/user-attachments/assets/10b29fc6-ae3f-4917-9ff0-69dbd426a314)



### A partir do grafo de dados gerais (2010-2025) criamos um subgrafo contendo apenas as vértices que possuiam no mínimo 71 vizinhos, calculamos sua densidade e comparamos ao grafo original:  

![image](https://github.com/user-attachments/assets/822b4eb6-0f55-441f-b2d5-66a8262dc6d1)



### Por fim, criamos uma rede ego de um nó aleatório e analisamos suas propriedades:

![image](https://github.com/user-attachments/assets/0cd5f740-5178-425f-a460-578b5155ae21)





