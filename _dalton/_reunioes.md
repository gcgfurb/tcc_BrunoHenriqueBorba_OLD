# Anotações das reuniões  

## 2021-01-21  

.. escreveu por e-mail ..  
Boa noite professor, tudo bem?  

Esse semestre começo a primeira parte do meu TCC (TCC I).  

Não tenho exatamente uma ideia formada, mas estou pensando em aproveitar que tenho boa parte dos dispositivos da maçã (Mac, iPhone, Watch, bem fã boy infelizmente) e fazer algo que utilize alguma tecnologia que a própria Apple disponibiliza, seja em linguagem de programação ou em hardware. Andei vendo algumas coisas sobre o Lidar, mas não sei até que ponto pode ser algo proveitoso ou o quanto eu conseguiria explorar desse hardware. Por esse motivo resolvi procurar você.  

Podemos marcar algo para alinhar esses pontos?  

Agradeço desde já!  
Att, Bruno  

## 2021-02-25

Respondi a msg e-mail para conversar sobre orientação de TCC.  

## 2021-03-12  

Acho que possou e acabei esquencendo de responder as suas dúvidas anteriores.  

- Famosas 4 perguntas (por quê, o que, como e para quem)  
- Pode ser destinado aos desenvolvedores de aplicações que usaram o LIDAR.  
O seu estudo pode esclarecer dúvidas, expor limites, etc. da sua real usabilidade.  

- Pensei em envolver a questão da mobilidade do sensor por exemplo. O fato de você ter sensores desse tipo vindo em equipamentos móveis como tablets ou smartphones, e focar em algo aplicado mais para os usuários no dia a dia mesmo.  
Sim, é que acho que na época que definimos o título ainda não tinhas certeza querias conseguir comprar o iPhone com LIDAR  
Mas agora podemos trazer a palavra mobilidade para o seu título. E sim, pode aparecer algo, mas não sei se seria no título, talvez nos objetivos com "utilizar ambientes não estruturados" ... algo como ambiente não controlado.  

### Acessibilidade usando LIDAR com atuadores de orientação

Numa pesquisa rápida, achei um vídeo (<https://youtu.be/8Au47gnXs0w>) onde a pessoa usa o lidar do iPad para auxiliar num deslocamento, totalmente vendado. O sensor faz a detecção do ambiente, e uma espécie de “motor” vibra para indicar as direções que pessoa deveria seguir. É uma ajuda para a acessibilidade.  
Muito interessante ...  
Já orientei um TCC que tínhamos uma caixa com uma "cela braile" e com motores de eletroimas.  
Eu tenho esta caixa, e tenhos alguns motores aqui.  
Poderíamos pensar em algo deste tipo.  
O TCC: <http://dsc.inf.furb.br/arquivos/tccs/monografias/2019_1_jader-antonio-tomelin_monografia.pdf>  

Esse seria o caminho? Como a gente pode focar em explorar esse sensor?  
Eheh, achei a ideia muito boa.  
Poderias usar como base o TCC acima.  

## 2021-05-03

### Defesa Pré-projeto

[Anotações de defesa do Pré-projeto](./tcc_BrunoHenriqueBorba_2021-05-03_PreProjeto_Defesa.md "Anotações de defesa do Pré-projeto")  

## 2021-08-09

Pedi as anotações desta reunião.  

## 2021-08-16

Obstáculos: Objetos  

- material: não refletivo, ser um espelho  
- formas:  
- profundidade: altura (escada)  
- alternação de ser um obstáculo ou não  

## 2021-08-23

- testar distância (colocaria uma trena):  
  - background fixo (branco)  
  - foreground fixo (preta) menor background (poder borda)  
    variável: distancia do celular  
  - celular fixo:
    variável: foreground
  .. testar limites ... até onde ele "enxerga".

- testar abertura do campo de visão lateral:  
    a distância máxima (sem erro)  
      colocar o foreground nas bordas  
        fita adessiva mostrar onde ele "enxerda"  

- testes de cor:  
   foreground: variar a cor  
   foreground: variar a matiz (brilho)  
   background: variar a cor  

- testes de variações de luz do ambiente
  medidor de luz  
