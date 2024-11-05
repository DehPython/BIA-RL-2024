# BIA-RL-2024

## Rocket League 

Nossa primeira tentativa foi com o Rocket League, porém foi totalmente frustrada devido ao fato de que alguns pré-requisitos básicos da biblioteca já nos atrapalhavam, como:

- **Necessidade de um PC com Windows 10**: Nem toda a equipe possuía Windows; alguns utilizavam Linux, outros macOS. Além disso, a maioria dos que tinham Windows estava na versão mais atual, Windows 11, e não na 10.

Além disso, o tamanho do próprio jogo, que ocupa cerca de 25 GB, não seria insignificante no armazenamento de alguns membros.

Entretanto, o maior problema revelou-se no tempo necessário para treinar um bom modelo e conseguir algo que funcionasse minimamente. Primeiro, pelo fato de que a melhor GPU que tínhamos disponível era uma RTX 3050 de notebook. Portanto, por mais que fosse possível realizar alguns treinos, não era suficiente. Além disso, pelo RLGym, as partidas de treino são realizadas em tempo real com o jogo aberto.

Para tentar contornar esses problemas, pesquisamos e encontramos a biblioteca **Rocket League Gym Simulator** [4], que prometia rodar em 1 segundo o equivalente a 20 minutos de vida real, algo que de fato parece muito incrível à primeira vista. Porém, essa biblioteca estava em C++, o que não condizia com as competências da equipe nessa linguagem de programação. E, embora no próprio repositório houvesse referência ao mesmo código tentando implementação em Python, constatamos que esse repositório em Python estava arquivado e descontinuado.

Portanto, optamos por pivotar a ideia.

### Referências
[1]. **[RLGym - Site Oficial](https://rlgym.org/)**  
   O RLGym é um ambiente de aprendizado por reforço para o jogo Rocket League, permitindo que pesquisadores e entusiastas treinem agentes personalizados.

[2]. **[RLGym no PyPI](https://pypi.org/project/rlgym/)**  
   Página oficial do pacote RLGym no PyPI, contendo instruções de instalação e documentação detalhada.

[3]. **[Guia RLGym-PPO por ZealanL](https://github.com/ZealanL/RLGym-PPO-Guide)**  
   Um guia completo sobre como implementar o algoritmo Proximal Policy Optimization (PPO) usando o RLGym.

[4]. **[Rocket League Gym Sim por AechPro](https://github.com/AechPro/rocket-league-gym-sim)**  
   Um simulador que integra o Rocket League ao OpenAI Gym, facilitando a criação de ambientes de aprendizado por reforço.

[5]. **[Rocket League Gym por Lucas Emery](https://github.com/lucas-emery/rocket-league-gym)**  
   Projeto que fornece um ambiente customizado para treinamento de agentes de aprendizado por reforço no Rocket League.

[6]. **[Replay Pretraining por Rolv-Arild](https://github.com/Rolv-Arild/replay-pretraining)**  
   Explora técnicas de pré-treinamento de agentes utilizando replays de partidas do Rocket League para melhorar a eficiência do aprendizado. Muito interessante porem de dificil implementação pela necessidade de ter muitos anotadores e posteriormente treinar uma rede que aprenda a generalizar os dados anotados.
   
[7]. **Conversas com o Bryan**

 
## Sistema de Recomendação

### Referências

https://useinsider.com/pt/sistemas-de-recomendacao-tudo-que-voce-precisa-saber/

https://github.com/fuxiAIlab/RL4RS/tree/main?tab=readme-ov-file

https://www.sciencedirect.com/science/article/pii/S095070512030407X

https://github.com/irskid5/drr_restaurants

tcc: SISTEMA DE RECOMENDAÇÃO DE MÚSICAS BASEADO EM DEEP REINFORCEMENT LEARNING - Leandro Yamachita da Costa

