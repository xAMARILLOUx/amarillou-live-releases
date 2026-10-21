# AMARILLOU LIVE

Ferramenta para organizar interações, automações e overlays nas suas lives do TikTok, com integração ao TikFinity.

**Versão atual: 0.3.5 · Windows 64 bits**

## Downloads

- **[Baixar AMARILLOU LIVE — Completa](https://github.com/xAMARILLOUx/amarillou-live-releases/releases/download/v0.3.5/AMARILLOU.LIVE_0.3.5_x64-setup.exe)**
- **[Baixar AMARILLOU LIVE — Lite](https://github.com/xAMARILLOUx/amarillou-live-releases/releases/download/v0.3.5/AMARILLOU.LIVE.LITE_0.3.5_x64-setup.exe)**

[Notas da versão 0.3.5](https://github.com/xAMARILLOUx/amarillou-live-releases/releases/tag/v0.3.5) · [Versão anterior 0.3.0](https://github.com/xAMARILLOUx/amarillou-live-releases/releases/tag/v0.3.0) · [Todas as versões](https://github.com/xAMARILLOUx/amarillou-live-releases/releases)

## Qual edição escolher?

**Completa:** macros, executor, automação, catálogo de presentes, rankings, pontos, X1, Batalha da Comunidade, galeria, destaques, histórico, metas, baú, herói/vilão, timer, placar e overlays.

**Lite:** interface compacta com presets, macros, executor, automação, catálogo de presentes, baú e a overlay do baú. Uma alternativa para quem utiliza outro sistema para as demais funções da live.

Cada edição tem instalação e pasta de dados próprias. Atualize utilizando o instalador da mesma edição. Evite executar macros nas duas edições ao mesmo tempo; os atalhos globais também podem disputar a mesma combinação.

## Novidades

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

**A atualização automática dentro do aplicativo ainda não está disponível.** As atualizações são baixadas e instaladas manualmente por esta página.

Os arquivos **Source code (zip)** e **Source code (tar.gz)** gerados pelo GitHub não são instaladores. Este repositório público distribui instaladores e documentação; o código do aplicativo é mantido separadamente.

## Como usar as overlays

1. Mantenha o AMARILLOU LIVE aberto.
2. Na seção **Overlays**, copie a URL desejada.
3. No OBS, adicione uma **Fonte de navegador** e cole a URL.
4. Ajuste largura, altura e posicionamento conforme sua cena.

A **Galeria** fica em **Overlays → Presentes da Live** e a **Batalha da Comunidade** em **Overlays → X1 / Batalhas**. Tamanhos sugeridos: **1080 × 380** para a galeria e **1080 × 800** para a batalha. Aparência e layout compartilhados ficam em **Global**.

Na Lite, está disponível a overlay do baú. A quantidade prática de fontes depende dos recursos do computador e do programa que as exibe.

## Detalhes de funcionamento

- A galeria é montada por você; o aplicativo não consulta automaticamente as missões semanais do TikTok.
- Galeria e regras automáticas do timer começam desativadas: configure e ative quando quiser usá-las.
- O timer recebe acréscimos automáticos enquanto está contando. Não reinicia automaticamente se estiver pausado ou tiver chegado a zero.
- A palavra do timer corresponde à mensagem inteira, ignorando maiúsculas e acentos. Por padrão, conta uma vez por pessoa por rodada; também é possível configurar um intervalo.
- A batalha conta somente eventos recebidos durante a rodada, sem alterar os rankings gerais. Fechar o aplicativo encerra a coleta.
- A exportação de configurações não substitui um backup completo dos dados e históricos.

Ícones Lucide distribuídos com suas licenças ISC/MIT incluídas no aplicativo.
