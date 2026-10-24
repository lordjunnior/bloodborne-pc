# Bloodborne para Windows
<a href="https://trendshift.io/repositories/306163?utm_source=trendshift-badge&amp;utm_medium=badge&amp;utm_campaign=badge-trendshift-306163" target="_blank" rel="noopener noreferrer"><img src="https://trendshift.io/api/badge/trendshift/repositories/306163/daily?language=C%2B%2B" alt="Supermedo%2Funcharted_pc | Trendshift" width="250" height="55"/></a>

**Bloodborne rodando nativamente no Windows 10 e 11, por [Supermedo](https://github.com/Supermedo) Mohammed Albarghouthi.**

O jogo original de PlayStation 4 roda diretamente no seu PC: o código nativo x86-64 é executado diretamente pelo processador e a parte gráfica é traduzida em tempo real para Vulkan. Sem janelas pesadas de emulador e sem necessidade de scripts manuais: descompacte o arquivo zip, execute `Bloodborne.exe`, selecione a pasta do seu jogo e clique em **JOGAR**.

**[Baixar a versão mais recente](https://github.com/Supermedo/bloodborne_pc/releases/latest)** · **[Entrar no Discord](https://discord.gg/yTMG8c4Bqm)** · **[Acompanhar no X/Twitter](https://x.com/SuperMedoPorts)**  
Conheça outros ports: https://nativeretro.com/

> **Nenhum arquivo do jogo está incluído.** Você precisa do seu próprio dump descriptografado do Bloodborne (CUSA03173). A atualização 1.09 é obrigatória para o funcionamento dos patches da comunidade (60/90/FPS desbloqueado, resolução, efeitos); outras versões rodam travadas em 30 FPS.  
> Este projeto não possui afiliação com a Sony Interactive Entertainment ou FromSoftware.

---

## Recursos

- **Modo Online (beta):** mensagens no chão, manchas de sangue e espectros de outros caçadores via [The Hunter's Dream](https://thehuntersdream.com), além de sinos e invocações cooperativas por meio de servidores shadNet (servidor público do shadPS4 configurado por padrão).
- **Inicializador completo em janela única**, com suporte a 13 idiomas: Português (Brasil), Inglês, Espanhol, Francês, Alemão, Italiano, Polonês, Russo, Árabe, Turco, Chinês, Japonês e Coreano.
- **Primeiro início guiado:** assistente em cinco etapas que verifica a integridade dos seus arquivos (um `eboot.bin` limpo na versão 1.09 e pasta completa), checa a compatibilidade do hardware, calibra os gráficos para a sua meta de desempenho, configura controle ou teclado/mouse, importa seus personagens salvos e conecta ao modo online.
- **Visualização Simples ou Avançada:** a visão simples exibe apenas as telas essenciais ao jogador e faz os ajustes técnicos automaticamente; a visão avançada libera todas as opções detalhadas. A alternância é feita na barra lateral.
- **Objetivos de desempenho práticos em vez de termos técnicos confusos:** Suave (até 120 FPS), Equilibrado (60 FPS com máxima fidelidade visual) ou Silencioso (60 FPS com menor carga na placa de vídeo). As configurações são sugeridas com base no seu hardware e a opção "Medir neste PC" valida a estabilidade direto no jogo.
- **Busca rápida (Ctrl+F):** localize configurações e soluções de problemas por palavras-chave ("stutters", "tela preta", "controle").
- **Importação de saves:** localiza e importa automaticamente personagens salvos do shadPS4, port do Awaken, bbhost ou exportados do PS4 (com backup automático dos saves existentes).
- **Página de Ajuda e Diagnóstico:** analisa a instalação (verificação do `eboot.bin` 1.09, integridade da pasta, memória virtual do Windows e diretório do port) e aponta a solução passo a passo. Após qualquer travamento, o inicializador identifica a causa lendo os logs de execução. O botão "Salvar relatório" gera um pacote zip pronto para análise no Discord.
- **Testes de benchmark integrados:** o inicializador roda uma cena fixa de forma automatizada para medir o desempenho, encontrar a configuração ideal para 60, 90 ou 120 FPS, comparar ajustes lado a lado com capturas de tela ou testar estabilidade em longas sessões.
- **Atualizações em um clique:** o launcher avisa quando há uma nova versão disponível e o botão **Atualizar** instala tudo mantendo saves, configurações e mods intactos.
- **NVIDIA DLSS** para placas GeForce RTX (Série RTX 20 e superiores).
- **AMD FSR 3.1 e FSR 4** para upscaling com alta fidelidade, além de TAA em resolução nativa.
- **AMD ML-FG 4.0.1 no Windows** para placas RX 9000 suportadas, junto à geração de quadros via FSR 3.1 ([Requisitos e medições](docs/ML_FRAME_GENERATION_WINDOWS.md)).
- **Taxa de quadros desbloqueada** com limitador customizável (até 120 FPS por padrão), ou modos travados em 30, 60 e 90 FPS.
- **Resoluções de saída de 720p até 4K real**, com perfis que vão de Native AA até Ultra Performance.
- **Página de Cheats e Modificadores:** vida infinita, furtividade, passos silenciosos, mecânica de Rally permanente, controle de inimigos e ajustes de jogabilidade (distância da câmera, desativação da auto-rotação de câmera, corrida facilitada, física ragdoll e layout japonês/asiático com Círculo para confirmar e X para esquiva).
- **Controle de efeitos visuais:** ligue ou desligue aberração cromática, profundidade de campo (DoF), motion blur, SSAO, anti-aliasing original do jogo, sombras dinâmicas, reflexos em screen-space e nível de detalhe dos modelos (LOD).
- **Ajuste de Campo de Visão (FOV):** configurável de 30 a 90 graus (o padrão original do jogo é 43) para todas as câmeras.
- **Silenciar em segundo plano:** opção para cortar o áudio e liberar o ponteiro do mouse quando a janela do jogo perder o foco.
- **Suporte a Mods e Patches:** carregamento limpo de modificações sem alterar os arquivos originais do jogo.
- **Suporte a DLC:** carregamento de The Old Hunters a partir do seu próprio dump, com configuração de diretório dedicado para conteúdos adicionais.
- **Adicionar à Steam:** integração direta com a biblioteca da Steam em apenas um clique.
- **Atalho rápido (`Play Bloodborne.exe`):** inicia a gameplay direto com as configurações salvas, ideal para atalhos na Área de Trabalho.
- **Menu de configurações no jogo:** acessível via tecla **Insert** (ou combinação **L3 + R3** no controle), permitindo ajustes em tempo real, digitação de nome na tela e limpeza rápida do cache de shaders.
- **Teclado e Mouse completos:** remapeamento total de teclas na aba Controles (até 3 botões por ação), suporte a combinações como Shift + clique esquerdo, perfil pré-configurado no padrão Dark Souls III e movimentação de câmera 1:1 com o mouse ([docs/INPUT.md](docs/INPUT.md)).
- **Seleção independente de idioma:** escolha vozes e legendas separadamente, com legendas em Português do Brasil inclusas.
- **Painel de Conquistas:** acompanhamento em tempo real dos troféus conquistados no jogo diretamente pelo launcher.

---

## Requisitos do Sistema

- Windows 10 (versão 1903 ou superior) ou Windows 11 de 64 bits.
- Processador Intel Core de 4ª geração (Haswell, 2013 em diante) ou AMD Ryzen. O jogo utiliza instruções da CPU do PS4 (AVX, BMI1, MOVBE, LZCNT). Processadores Intel de 2ª e 3ª geração operam via tradução de instruções em regime de melhor esforço; CPUs sem suporte a AVX não são compatíveis.
- Placa de vídeo com suporte a Vulkan 1.3 e drivers atualizados.
- Cerca de 6 GB de memória livre (RAM + arquivo de paginação do Windows), ou 10 GB para saída em 1440p / 4K.
- Para uso de DLSS: placa de vídeo NVIDIA GeForce série RTX 20 ou mais recente.

Não há dependências externas: todos os arquivos e bibliotecas necessários acompanham o pacote.

---

## Como Jogar

1. Baixe o pacote compactado na aba de [Releases](https://github.com/Supermedo/bloodborne_pc/releases/latest) e extraia em qualquer pasta (preferencialmente em SSD).
2. Execute o inicializador `Bloodborne.exe`. No primeiro acesso, o assistente verifica a pasta do jogo (onde se encontra o arquivo `eboot.bin`), avalia seu computador e aplica o perfil gráfico recomendado.
3. Clique em **JOGAR**.

### Conteúdo Adicional (DLC)
A edição Game of the Year (CUSA03173) já inclui a expansão The Old Hunters integrada. Se você estiver utilizando o dump da versão base, extraia os arquivos de expansão (pastas no formato `SPEXPANSIONDLC03` contendo a pasta interna `sce_sys`). Aponte para esse diretório na opção **Pasta de DLC** na aba **Jogo e Efeitos**, ou copie os arquivos para a estrutura `user\addcont\<title id>\`.

### Comandos e Atalhos
Durante a execução, a tecla **Insert** (ou **L3 + R3** no controle) abre as opções rápidas na tela.

* **Layout Padrão de Teclado:**
  * Movimentação: `W`, `A`, `S`, `D`
  * Controle de Câmera: Setas direcionais ou Mouse
  * Esquiva / Corrida: `Espaço` (equivale ao Círculo)
  * Interagir: `Shift Esquerdo` (equivale ao X)
  * Usar Item: `E` (Quadrado)
  * Curar (Frasco de Sangue): `V` (Triângulo)
  * Arma da mão direita (Ataque Leve / Forte): `3` / `1` (R1 / R2)
  * Arma da mão esquerda (Disparo / Tocha): `R` / `F` (L1 / L2)
  * Travar Mira (Lock-on): `Q` ou `C` (R3)
  * Menu do Jogo: `Enter` (Options)
  * Touchpad Esquerdo / Direito: `Tab` / `Backspace`

* **Controles de Xbox:**
  * Toque rápido no botão `Back`: abre o lado esquerdo do touchpad (gestos).
  * Combinação `Back + Direcional analógico (Esquerda/Direita)`: ativa o lado correspondente do touchpad.

O teclado e o controle conectado funcionam em conjunto de forma simultânea. Todas as atribuições podem ser personalizadas pela interface ou pelo arquivo `input.ini` (sintaxe padrão do shadPS4).

---

## Modo Online (Beta)

1. Crie uma conta no portal [shadnet.shadps4.net](https://shadnet.shadps4.net).
2. No launcher, abra a aba **Co-op Online**, marque a caixa **Jogar online** e insira seu nome de usuário (não utilize o e-mail) e sua senha.
3. Clique em **Testar conexão**. As três linhas de status devem indicar "acessível". Em seguida, clique em **JOGAR** e confirme a opção online na tela inicial do jogo. A mensagem de boas-vindas do The Hunter's Dream confirma que você está conectado.

Todos os participantes de uma sessão devem utilizar a versão 1.09 do jogo e o mesmo servidor. Servidores privados shadNet (do projeto [shadp2p](https://github.com/Wozzardman/shadp2p)) também são suportados através do campo **Endereço do Servidor**.

---

## Problemas Conhecidos

- Algumas placas de vídeo AMD podem apresentar travamento durante o carregamento de novas áreas; caso ocorra, envie o arquivo `user\last_run.log`.
- O modo online está em fase beta. Mensagens, poças de sangue, fantasmas e invocações com sinos funcionam no servidor padrão; compartilhe seu feedback no servidor do Discord.
- Recomenda-se manter o limite de quadros em até 120 FPS. A taxa de aceleração da corrida foi corrigida para taxas elevadas, mas a sincronização de eventos acima de 120 FPS ainda está sob validação.
- Processadores Intel de 2ª e 3ª geração utilizam tradução em tempo real de instruções; instruções raramente usadas podem causar instabilidades pontuais.

---

## Suporte e Relatórios

Dúvidas e relatos de erros podem ser enviados no [Discord do projeto](https://discord.gg/yTMG8c4Bqm) ou abrindo uma [Issue no GitHub](https://github.com/Supermedo/bloodborne_pc/issues), anexando o log `user\last_run.log` e especificando o modelo da sua placa de vídeo e o comportamento observado.

Caso o jogo inicialize em tela preta, utilize a opção **Avançado → Limpar cache de shaders** antes de reiniciar. Orientações adicionais sobre GPUs AMD RDNA2 e ajustes de desempenho estão documentadas em [docs/WINDOWS_TROUBLESHOOTING.md](docs/WINDOWS_TROUBLESHOOTING.md).

---

## Compilação a partir do Código-Fonte

Consulte as instruções detalhadas em [packaging/windows/README.md](packaging/windows/README.md):
1. Ambiente MSYS2 CLANG64.
2. Execução de `bash build.sh` seguido por `bash packaging/windows/package.sh`.
3. O módulo de DLSS é gerado separadamente através de `packaging/windows/build_dlss.sh` (requer Visual Studio 2022 instalado).

---

## Créditos e Tecnologias

Desenvolvido a partir do [bbport](https://github.com/deadinside28/bloodborne_pc) (port nativo para Linux criado por deadinside28) e do renderizador do projeto [shadPS4](https://github.com/shadps4-emu/shadPS4). O documento original encontra-se em [docs/original-readme](docs/original-readme/README.md).

A estrutura de rede utiliza as implementações de NP e shadNet do shadPS4 0.20 integradas por **Awaken** ([BloodBorneButPc](https://github.com/Awakenchan/BloodBorneButPc)), com rotinas para The Hunter's Dream adaptadas do [bbhost](https://github.com/droogie/bbhost) por droogie (sob licença GPL-3.0-or-later; detalhes em [gpu/bbnet/SHADNET-PORT.md](gpu/bbnet/SHADNET-PORT.md)). Agradecimentos a Metr1k, à equipe do The Hunter's Dream e ao projeto [shadp2p](https://github.com/Wozzardman/shadp2p) de Wozzardman.

O perfil otimizado para placas com 4 GB de VRAM é baseado no mod de **fixdag** e **bashiku**.

Bibliotecas e tecnologias integradas:
- [FSR-Vulkan](https://github.com/FireBurn/FSR-Vulkan) e AMD FidelityFX SDK (FSR).
- Elementos de FSR 4 baseados em [FireBurn/Q2RTX](https://github.com/FireBurn/Q2RTX).
- Ponte de DLSS adaptada de [IFreemz/shadPS4-Bloodborne-DLSS-FSR](https://github.com/IFreemz/shadPS4-Bloodborne-DLSS-FSR).
- SDK NVIDIA DLSS (`nvngx_dlss.dll` sob licença da NVIDIA).
- LibAtrac9, SDL3, FFmpeg, Dear ImGui, sirit, magic_enum, miniz, xbyak, wepoll, cpp-httplib, Protocol Buffers, OpenSSL, miniupnpc, JSON for Modern C++, Vulkan Memory Allocator, MSYS2 / LLVM, PyInstaller e Pillow.
- Patches e correções de gameplay criados por Kyo, Lance McDonald, auser1337, illusion, emoose e toda a comunidade de Bloodborne.

NVIDIA, GeForce RTX e DLSS são marcas registradas da NVIDIA Corporation. O ícone do inicializador é arte original do projeto.

---

## Licença

Distribuído sob os termos da licença GNU GPL v2 ou posterior ([LICENSE](LICENSE)). Componentes e bibliotecas de terceiros permanecem regidos por suas respectivas licenças (consulte a pasta `licenses\` no download).