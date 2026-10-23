# AMARILLOU LIVE

Ferramenta para organizar interações, automações e overlays nas suas lives do TikTok, com integração ao TikFinity.

**Versão atual: 0.5.1 · Windows 64 bits**

## Downloads

- **[Baixar AMARILLOU LIVE — Completa](https://github.com/xAMARILLOUx/amarillou-live-releases/releases/download/v0.5.1/AMARILLOU.LIVE_0.5.1_x64-setup.exe)**
- **[Baixar AMARILLOU LIVE — Lite](https://github.com/xAMARILLOUx/amarillou-live-releases/releases/download/v0.5.1/AMARILLOU.LIVE.LITE_0.5.1_x64-setup.exe)**

[Notas da versão 0.5.1](https://github.com/xAMARILLOUx/amarillou-live-releases/releases/tag/v0.5.1) · [Versão anterior 0.5.0](https://github.com/xAMARILLOUx/amarillou-live-releases/releases/tag/v0.5.0) · [Todas as versões](https://github.com/xAMARILLOUx/amarillou-live-releases/releases)

## Qual edição escolher?

**Completa:** macros, executor, automação, catálogo de presentes, rankings, pontos, X1, Batalha da Comunidade, galeria, destaques, histórico, metas, baú, herói/vilão, timer, placar e overlays.

**Lite:** interface compacta com presets, macros, executor, automação, catálogo de presentes, baú e a overlay do baú. Uma alternativa para quem utiliza outro sistema para as demais funções da live.

Cada edição tem instalação e pasta de dados próprias. Atualize utilizando o instalador da mesma edição. Evite executar macros nas duas edições ao mesmo tempo; os atalhos globais também podem disputar a mesma combinação.

## Novidades

### 0.5.1 — Correção de rolagem

Corrige a rolagem externa em Presets & Macros, mantendo o topo e o menu lateral fixos e a rolagem dentro dos painéis. Disponível na Completa e na Lite.

### 0.5.0 — MVP automático e destaques compactos
- MVP manual ou automático pelos rankings da semana, do dia ou da Batalha da Comunidade; ocultação quando não há participante.
- Overlays compactas com foto circular, presente e combo opcional, incluindo rotação entre quatro destaques.
- Cinco estilos adicionais de molduras e efeitos para overlays: Clássico dourado, Trono real, Brasão prateado, Arena e Neon.
- X1 com barra de disputa, efeito de impacto e simulador local com dois bots, sem alterar os dados da live.
- Atalhos para ferramentas em atividade e opção **Liberar todos** os baús.
- Placar com números em verde/vermelho ou azul/vermelho.
- Correção da rolagem do editor de macros, melhoria da janela compacta Lite, catálogo e migração antiga recolhidos.


### 0.4.0 — Controles, pódio e MVP

- Automação no topo: iniciar, pausar, retomar e parar, junto aos controles de conexão e executor.
- Solicitação do @ do canal na primeira abertura sem canal configurado; edição em **Conexão & Dados**.
- **Reiniciar rodada** na Batalha da Comunidade: zera os pontos da batalha e começa novamente, mantendo a duração escolhida, inclusive sem limite de tempo.
- Destaques em ouro, prata e bronze para o top 3 nas overlays de moedas e curtidas.
- Botões **Ajustar aparência** e **Ajustar layout** na Galeria, Batalha e MVP.
- Novo **Pódio semanal** com os três primeiros do ranking de moedas, fotos e nomes, sem mostrar valores.
- Novo **MVP manual** com @, nome, foto e overlay em formato de brasão.
- Consulta de novas versões na abertura, com download da edição correta e aviso de atualização disponível no rodapé.
- Removido o indicador genérico “Sistema online”.

A Lite recebe os controles, a configuração de canal e a consulta de atualizações. Pódio, MVP e rankings pertencem à edição Completa.

### 0.3.5 — Visual renovado

- Tema escuro em grafite, destaque amarelo e ícones incorporados, sem depender de internet para exibi-los.
- Painéis, botões e formulários renovados.
- Navegação da completa agrupada em Comunidade e Ferramentas da live.
- Resumo visual da conexão, preset, executor e automação.
- A lógica das funcionalidades da 0.3.0 foi mantida.

Selecione **Tema → Moderna** para usar o novo visual. O tema **Clássica** continua disponível.

### 0.3.0 — Fila e controles da live

- Até **100.000 acionamentos pendentes** e **24 horas de duração acumulada estimada**. Vale o limite atingido primeiro.
- A fila cheia não desarma a automação: pedidos novos que não couberem são recusados, enquanto os já aceitos continuam. Novos eventos voltam a entrar conforme houver espaço. Pedidos recusados não são recuperados depois.
- Reset separado dos rankings diário, semanal e mensal de taps ou moedas.
- Batalha da Comunidade com opção de encerramento manual, sem limite de tempo.
- Galeria e Batalha com ajustes próprios de fundo, cores, escala e cabeçalho.

## Recursos da edição completa

- **Macros e presets:** organize suas automações e compartilhe macros por exportação e importação.
- **Overlays para OBS e navegador:** exiba rankings, presentes, destaques, timer e placar. Use várias fontes, inclusive cópias da mesma overlay.
- **Galeria de Presentes:** selecione presentes e quantidades. A overlay alterna entre os presentes que ainda faltam; os concluídos saem da rotação.
- **Timer & Placar:** controle pontos e tempo com atalhos configuráveis. Acrescente tempo por moedas recebidas ou por uma palavra definida para o chat.
- **Batalha da Comunidade:** top 5 de taps e top 5 de moedas recebidos durante uma rodada, com duração definida ou encerramento manual.
- **Rankings:** períodos diário, semanal e mensal, com datas visíveis no painel e opção de reset por período. A semana vai de segunda a domingo, com referência ao horário de São Paulo.
- **Importar & Exportar:** compartilhe macros, configurações compatíveis e catálogo de presentes, além de acessar a migração de macros antigos.

## Instalação e atualização

1. Baixe acima o instalador da edição desejada.
2. Se já utiliza a ferramenta, exporte suas configurações e feche o aplicativo.
3. Execute o instalador. Para atualizar a mesma edição, mantenha o local de instalação anterior; normalmente não é necessário desinstalar.
4. Abra o aplicativo e configure a conexão com o TikFinity.
5. Depois de atualizar, recarregue as fontes de navegador no OBS e as páginas de overlays abertas.

**A partir da 0.4.0, o aplicativo verifica novas versões na abertura.** Quando houver uma versão estável com instalador da sua edição, **Atualizar** abre o download no navegador. A instalação é manual: feche a ferramenta e execute o instalador. **Agora não** recolhe o aviso, mantendo “Atualização disponível” junto à versão durante essa sessão. Na próxima abertura, a consulta é refeita. Falhas de conexão não impedem o uso. Quem utiliza uma versão anterior à 0.4.0 deve baixar esta atualização pelos links acima.

Os arquivos **Source code (zip)** e **Source code (tar.gz)** gerados pelo GitHub não são instaladores. Este repositório público distribui instaladores e documentação; o código do aplicativo é mantido separadamente.

## Como usar as overlays

1. Mantenha o AMARILLOU LIVE aberto.
2. Na seção **Overlays**, copie a URL desejada.
3. No OBS, adicione uma **Fonte de navegador** e cole a URL.
4. Ajuste largura, altura e posicionamento conforme sua cena.

A **Galeria** fica em **Overlays → Presentes da Live** e a **Batalha da Comunidade** em **Overlays → X1 / Batalhas**. Tamanhos sugeridos: **1080 × 380** para a galeria e **1080 × 800** para a batalha. Aparência e layout compartilhados ficam em **Global**.

Na Lite, está disponível a overlay do baú. A quantidade prática de fontes depende dos recursos do computador e do programa que as exibe.

O **Pódio semanal** usa os dados da semana corrente e compartilha aparência e layout com o ranking de moedas; alterar esses ajustes afeta ambos. Tamanho sugerido: **840 × 550**.

Em **Comunidade → MVP**, informe o @ e salve. Nome e foto podem vir do cadastro local de participantes; não há busca de perfis arbitrários no TikTok. Você pode personalizar o nome e enviar uma foto PNG, JPEG ou WebP de até 250 KB. Sem foto, aparece a inicial; **Limpar MVP** oculta o brasão. Tamanho sugerido: **460 × 560**.

Galeria, Batalha e MVP têm controles individuais de aparência e layout. Os ajustes globais continuam disponíveis para as overlays tradicionais.

## Detalhes de funcionamento

- A galeria é montada por você; o aplicativo não consulta automaticamente as missões semanais do TikTok.
- Galeria e regras automáticas do timer começam desativadas: configure e ative quando quiser usá-las.
- O timer recebe acréscimos automáticos enquanto está contando. Não reinicia automaticamente se estiver pausado ou tiver chegado a zero.
- A palavra do timer corresponde à mensagem inteira, ignorando maiúsculas e acentos. Por padrão, conta uma vez por pessoa por rodada; também é possível configurar um intervalo.
- A batalha conta somente eventos recebidos durante a rodada, sem alterar os rankings gerais. Fechar o aplicativo encerra a coleta.
- A exportação de configurações não substitui um backup completo dos dados e históricos.

Ícones Lucide distribuídos com suas licenças ISC/MIT incluídas no aplicativo.
