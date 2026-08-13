# Guia do Minecraft Education — Criação de Mundo e Conexão em Rede

Este guia foi criado para a equipe de TI da escola, com o objetivo de explicar de forma prática como o **Minecraft Education** funciona: desde a criação de um mundo até a abertura desse mundo em rede local (LAN) para que os alunos possam se conectar e jogar juntos, no modo criativo, durante as aulas.

Cada seção abaixo é ilustrada com um GIF demonstrativo. Se você já conhece o funcionamento básico do Minecraft Education, pode pular direto para a seção final, onde está disponível um **mundo plano já pré-configurado**, pronto para ser importado e usado em aula.

> 📁 **Observação sobre os arquivos:** os nomes dos GIFs contêm acentos e espaços. Recomenda-se colocá-los em uma pasta `assets/` dentro do repositório e, se possível, renomeá-los sem acentos/espaços (ex.: `mundo-plano.gif`) para evitar problemas de exibição em alguns visualizadores do GitHub. Os caminhos usados abaixo assumem que os GIFs estão na mesma pasta deste arquivo `README.md`.

---

## Sumário

1. [Criando um mundo plano](#1-criando-um-mundo-plano)
2. [Opções avançadas de criação de mundo](#2-opções-avançadas-de-criação-de-mundo)
3. [Mais opções de criação de mundo](#3-mais-opções-de-criação-de-mundo)
4. [Armazenamento do mundo em nuvem (OneDrive)](#4-armazenamento-do-mundo-em-nuvem-onedrive)
5. [Opções do modo multijogador](#5-opções-do-modo-multijogador)
6. [Cheats na criação do mundo](#6-cheats-na-criação-do-mundo)
7. [Pacotes de recursos e finalização da criação](#7-pacotes-de-recursos-e-finalização-da-criação)
8. [Abrindo o inventário e colocando blocos](#8-abrindo-o-inventário-e-colocando-blocos)
9. [Dicas de controle e como voar](#9-dicas-de-controle-e-como-voar)
10. [Abrindo o mundo para LAN (outros alunos conectarem)](#10-abrindo-o-mundo-para-lan-outros-alunos-conectarem)
11. [Conectando no mundo (como aluno)](#11-conectando-no-mundo-como-aluno)
12. [Mundo pré-configurado para download](#mundo-pré-configurado-para-download)

---

## 1. Criando um mundo plano

Ao abrir o Minecraft Education, a tela inicial apresenta os botões **Jogar** e **Opções**. Para começar um mundo novo, clique em **Jogar** e, em seguida, em **Criar**.

Na tela **Criar Novo Mundo**, na aba **Avançado**, é possível transformar o mundo padrão em um **mundo plano**:

- Ative a opção **Mundo clássico**, usada para construir ou minerar.
- Em **Predefinição do mundo clássico**, selecione **Mundo Superior**.
- Em **Camadas**, defina as camadas de blocos que vão compor o terreno — por exemplo:
  - Bloco de Grama — altura 1
  - Terra — altura 3
  - Pedra — altura 59
  - Rocha Matriz — altura 1

Esse é o ponto de partida ideal para aulas de construção, já que gera um terreno totalmente plano, sem relevo, árvores ou estruturas naturais atrapalhando os alunos.

![Como criar um mundo plano](./Como_criar_um_mundo_plano.gif)

---

## 2. Opções avançadas de criação de mundo

Ainda na tela de criação de mundo, a aba **Sala de Aula** reúne as configurações que mais impactam o comportamento do jogo durante a aula:

| Opção | O que faz |
|---|---|
| Comandos do console | Permite usar comandos no chat para ativar recursos específicos |
| Criador de Código | Libera os recursos de programação (blocos de código) dentro do mundo |
| Clima perfeito | Desativa o ciclo de clima, mantendo o tempo sempre claro |
| Criaturas restritas | Impede o surgimento de criaturas, seja natural ou por comando/ovo de invocação |
| Itens destrutivos | Quando desativado, bloqueia o uso de TNT, poções nocivas, explosão de bloco de renascimento e fogo se espalhando |
| Dano do jogador | Quando desativado, os jogadores não sofrem dano de nenhuma fonte |
| Dano de jogador x jogador (fogo amigo) | Permite que os jogadores causem dano uns aos outros |
| Mundo imutável | Os alunos podem interagir com blocos existentes, mas não podem destruir, minerar ou colocar novos blocos |

Para aulas de construção, é comum **desativar criaturas** e **itens destrutivos**, mantendo o foco dos alunos na criação, sem riscos de explosões ou ataques.

![Opções avançadas](./Opções_Avançadas.gif)

---

## 3. Mais opções de criação de mundo

Complementando a aba **Sala de Aula**, há também a opção **Mostrar efeitos de bloco de fronteira**, que faz os blocos de fronteira emitirem pequenas partículas vermelhas — útil para sinalizar aos alunos os limites da área de construção.

Mais abaixo, em **Configurações do link de recurso**, é possível cadastrar uma **URL** e um **nome de botão**. Ao preencher esses campos, um novo botão aparece no menu de jogo *(dentro do mundo)*, permitindo abrir um site, ferramenta de avaliação ou qualquer outro recurso vinculado à aula diretamente de dentro do Minecraft.

![Mais opções](./Mais_opções.gif)

---

## 4. Armazenamento do mundo em nuvem (OneDrive)

Na aba **Armazenamento da Nuvem**, é possível ativar a opção **Faça Backup no OneDrive**. Com isso, o mundo criado passa a ser salvo automaticamente na conta do OneDrive vinculada ao Minecraft Education, evitando perda de progresso caso o computador local apresente problemas.

Essa configuração é especialmente recomendada quando o mesmo mundo será reaproveitado em várias aulas ou turmas.

![Armazenamento em nuvem (OneDrive)](./OneDrive.gif)

---

## 5. Opções do modo multijogador

A aba **Multijogador** define como os alunos vão interagir entre si dentro do mesmo mundo:

- **Permissões de jogador padrão**: define o nível de permissão de quem entra no mundo.
  - **Visitante** — apenas observa, não interage.
  - **Membro** — pode construir, minerar, atacar jogadores/criaturas e interagir com itens e entidades (opção recomendada para aulas).
  - **Operador** — controle total sobre o mundo, incluindo comandos administrativos (recomendado apenas para o professor/host).
- **Fogo amigo**: define se os jogadores podem causar dano uns nos outros.
- **Indicadores do jogador**: define se os alunos aparecem como indicadores na barra localizadora, ajudando a encontrar os colegas dentro do mundo.

![Opções do modo multijogador](./Opções_do_modo_Multijogador.gif)

---

## 6. Cheats na criação do mundo

A aba **Cheats** permite habilitar comandos de trapaça (como voo livre, modo de jogo, teletransporte, dar itens, etc.) diretamente no mundo. Isso é útil para o professor ter controle total durante a aula — por exemplo, teletransportar um aluno até a área de construção ou alternar rapidamente entre modo criativo e sobrevivência.

> ⚠️ Cheats concedem acesso a comandos poderosos. Recomenda-se manter essa permissão restrita ao professor (permissão **Operador**), evitando que alunos com permissão de Membro usem comandos de forma indevida.

![Cheats de criação de mundo](./Cheats_de_criação_de_mundo.gif)

---

## 7. Pacotes de recursos e finalização da criação

Por fim, na aba **Pacotes de recursos** (e **Pacotes de comportamento**), é possível adicionar texturas, modelos ou comportamentos customizados ao mundo, caso a aula exija uma ambientação específica.

Depois de revisar todas as configurações, basta clicar em **Criar**, no menu lateral esquerdo, para gerar o mundo com as opções escolhidas.

![Pacotes de recursos e criação do mundo](./Pacotes_de_recurso_e_criação_do_mundo.gif)

---

## 8. Abrindo o inventário e colocando blocos

> 🚧 **Seção em construção — GIF pendente de envio.**
>
> Aqui será explicado como abrir o inventário criativo, selecionar blocos e itens, e como posicioná-los no mundo.

<!-- GIF: abrindo-inventario-colocando-blocos.gif -->

---

## 9. Dicas de controle e como voar

> 🚧 **Seção em construção — GIF pendente de envio.**
>
> Aqui serão explicados os controles básicos de movimentação, câmera, e como ativar/usar o voo no modo criativo (útil para construções em altura).

<!-- GIF: dicas-de-controle-como-voar.gif -->

---

## 10. Abrindo o mundo para LAN (outros alunos conectarem)

> 🚧 **Seção em construção — GIF pendente de envio.**
>
> Aqui será explicado o passo a passo para o professor abrir o mundo em rede local (LAN), permitindo que os computadores dos alunos, conectados na mesma rede da escola, encontrem e entrem no mundo.

<!-- GIF: abrindo-mundo-para-lan.gif -->

---

## 11. Conectando no mundo (como aluno)

> 🚧 **Seção em construção — GIF pendente de envio.**
>
> Aqui será explicado o processo do lado do aluno: como localizar o mundo aberto em LAN pelo professor na lista de servidores/jogos e entrar nele.

<!-- GIF: conectando-no-mundo-como-aluno.gif -->

---

## Mundo pré-configurado para download

Para quem já está familiarizado com o funcionamento do Minecraft Education e só precisa de um mundo pronto para uso em aula, disponibilizamos abaixo um **mundo plano já configurado** no modo **criativo**, ideal para atividades de construção.

> 📎 **Anexe aqui o arquivo do mundo** (formato `.mcworld`) e o link de download, por exemplo:
>
> `[⬇️ Baixar mundo plano pré-configurado](./mundos/mundo-plano-criativo.mcworld)`

**Como importar o mundo baixado no Minecraft Education:**

1. Baixe o arquivo `.mcworld` disponibilizado acima.
2. Dê duplo clique no arquivo baixado (ou abra-o pelo Minecraft Education).
3. O jogo será aberto automaticamente e importará o mundo para a lista de mundos salvos.
4. Na tela inicial, clique em **Jogar** e selecione o mundo importado na lista.

---

### Checklist rápido para a equipe de TI

- [ ] Confirmar que todos os computadores estão na mesma rede local antes de tentar o modo LAN.
- [ ] Definir a permissão padrão dos alunos como **Membro** (não Operador), exceto para o professor.
- [ ] Desativar criaturas e itens destrutivos em aulas de construção.
- [ ] Ativar backup em nuvem (OneDrive) para mundos que serão reutilizados.
- [ ] Testar a importação do mundo pré-configurado antes da aula.
