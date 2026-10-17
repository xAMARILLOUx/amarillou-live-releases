# AMARILLOU LIVE

Ferramenta para organizar interações, automações e overlays nas suas lives do TikTok, com integração ao TikFinity.

**Versão: 0.2.0 · Windows 64 bits**

[⬇️ Baixar a versão mais recente](https://github.com/xAMARILLOUx/amarillou-live-releases/releases/latest) · [Ver todas as versões](https://github.com/xAMARILLOUx/amarillou-live-releases/releases)

## Recursos

- **Macros e presets:** organize suas automações e compartilhe macros por exportação e importação.
- **Overlays para OBS e navegador:** exiba rankings, presentes, destaques, timer e placar. Use várias fontes simultaneamente, inclusive cópias da mesma overlay.
- **Galeria de Presentes:** escolha presentes do catálogo ou informe seus IDs, defina as quantidades e acompanhe o progresso. A overlay alterna entre os presentes que ainda faltam; os concluídos saem da rotação.
- **Timer & Placar:** controle pontos e tempo com atalhos configuráveis. Acrescente tempo automaticamente por moedas recebidas ou por uma palavra definida para o chat.
- **Batalha da Comunidade:** crie rodadas com duração definida e dois rankings: top 5 de taps e top 5 de moedas. O resultado fica congelado ao terminar.
- **Rankings com período visível:** consulte as datas do diário, semanal e mensal no painel. A semana vai de segunda a domingo, com referência ao horário de São Paulo.
- **Importar & Exportar:** compartilhe macros, configurações compatíveis e o catálogo de presentes, além de acessar a migração de macros antigos.
- **Controles por cores:** identifique com mais facilidade ações de iniciar, pausar, retomar, parar e excluir.

## Instalação

1. Acesse a [página da versão mais recente](https://github.com/xAMARILLOUx/amarillou-live-releases/releases/latest).
2. Em **Assets**, baixe o arquivo `AMARILLOU LIVE_0.2.0_x64-setup.exe`.
3. Execute o instalador e siga as instruções.
4. Abra o aplicativo e configure a conexão com o TikFinity para receber os eventos da live.

Os arquivos **Source code (zip)** e **Source code (tar.gz)** gerados pelo GitHub não são o instalador.

## Atualização

Feche o AMARILLOU LIVE e execute o novo instalador sobre a instalação anterior, mantendo o mesmo local de instalação. Não é necessário desinstalar antes: esta versão mantém a identidade do aplicativo e utiliza a mesma pasta de dados.

Você pode atualizar diretamente para a **0.2.0**, que já inclui as correções da **0.1.1**. Depois da atualização, recarregue as fontes de navegador no OBS e as páginas de overlays abertas.

## Como usar as overlays

1. Mantenha o AMARILLOU LIVE aberto.
2. Na seção **Overlays**, copie a URL da overlay desejada.
3. No OBS, adicione uma **Fonte de navegador** e cole a URL.
4. Ajuste largura, altura e posicionamento conforme sua cena.

As novas overlays ficam em **Overlays → Galeria & Comunidade**. Tamanhos sugeridos: **1080 × 380** para a galeria e **1080 × 800** para a batalha. Elas têm visual próprio e controles nos respectivos módulos.

Não há um limite fixo de três overlays; a quantidade prática depende dos recursos do computador e do programa que exibe as fontes.

## Detalhes das novas funções

- A lista da galeria é montada por você. O aplicativo não consulta automaticamente as missões semanais do TikTok.
- Galeria e regras automáticas do timer começam desativadas: configure e ative quando quiser usá-las.
- O timer recebe acréscimos automáticos enquanto está contando. Ele não reinicia automaticamente se estiver pausado ou tiver chegado a zero.
- A palavra do timer deve corresponder à mensagem inteira, ignorando maiúsculas e acentos. Por padrão, conta uma vez por pessoa por rodada; também é possível configurar um intervalo.
- A batalha conta os eventos recebidos durante a rodada, sem alterar os rankings gerais. Fechar o aplicativo encerra a coleta da rodada.
- A exportação de configurações inclui aparência/layout, interface e ajustes das novas ferramentas. Ela não substitui um backup completo de todos os dados e históricos.

Este repositório distribui os instaladores e as notas de versão do AMARILLOU LIVE.
