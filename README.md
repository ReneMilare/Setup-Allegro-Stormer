# Setup-Allegro-Stormer
Robô investidor escrito em Mql5 com o setup do Stormer chamado Allegro,
explicado pelo próprio Stormer no vídeo que segue o link, a partir do minuto 1:50.

https://www.youtube.com/watch?v=WdhPgOHkW1k&t=547s

boa parte do código foi aproveitado do projeto do Fenerick, segue link:
https://github.com/RafaelFenerick/IntroducaoMQL5

Também foi adicionado o .set desse setup, porém não é a melhor configuração, cabe otimização.
Lembrando que uma boa prática é separar o período de otimização e o período de teste.
Essa configuração produziu essa curva de capital:

![Curva-de-capital-Allegro](https://user-images.githubusercontent.com/24875841/70440307-ad0a1580-1a70-11ea-8aaf-2fa3b8b9907f.png)

A configuração para essa curva de capital foi a seguinte:

![Configuacao](https://user-images.githubusercontent.com/24875841/70440517-243fa980-1a71-11ea-85a4-d821d612edbb.PNG)

Com isso produzimos um back teste com a seguinte cara:

![Backtest-imagem1](https://user-images.githubusercontent.com/24875841/70440658-6668eb00-1a71-11ea-868a-da3cc65d4da5.PNG)

![Backtest-imagem2](https://user-images.githubusercontent.com/24875841/70440766-a9c35980-1a71-11ea-997c-41869a13df64.PNG)
