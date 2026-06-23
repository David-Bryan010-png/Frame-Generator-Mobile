Frame Generator V10.23 — Public Preview

Esta é a primeira versão pública de testes do Frame Generator V10, um projeto experimental de geração e reconstrução temporal de quadros para Android.

O aplicativo funciona sem root e utiliza:

- captura autorizada pelo Android com MediaProjection;
- engine nativa em C++17;
- processamento local;
- overlay OpenGL ES;
- serviço de acessibilidade que preserva os controles por toque;
- adaptação automática de resolução, custo e apresentação;
- telemetria para análise de geração e desempenho.

Package oficial

com.fps.genereitor

Requisitos

- Android 8.0 ou superior;
- aparelho arm64-v8a;
- permissão para captura de tela;
- serviço de acessibilidade do Frame Generator ativado;
- instalação de aplicativos de fontes externas autorizada.

Como instalar

1. Baixe o arquivo APK disponível abaixo.
2. Abra o APK no Android.
3. Autorize a instalação quando solicitado.
4. Abra o Frame Generator V10.
5. Ative o serviço de acessibilidade Frame Generator V10 Overlay.
6. Toque em Iniciar Frame Generator V10.
7. Autorize a captura da tela ou somente do jogo.
8. Abra o jogo e acompanhe as informações na notificação.

Principais recursos

- funcionamento sem root;
- captura e processamento local;
- geração de quadros intermediários;
- detecção de movimento global e regional;
- proteção de HUD;
- reconstrução temporal;
- upscale adaptativo;
- controle de latência e deadline;
- perfis para FPS baixo e intermediário;
- telemetria de geração, apresentação e carga;
- exportação de traces CSV;
- botão para salvar quadro de diagnóstico.

Indicadores da notificação

- "Fonte": FPS real estimado da aplicação;
- "Alvo": taxa de apresentação desejada;
- "Gen": quadros sintéticos produzidos;
- "Show": porcentagem de quadros realmente apresentados;
- "Late": quadros que chegaram atrasados;
- "Cob": cobertura sintética;
- "Proc/Bud": tempo de processamento comparado ao orçamento;
- "Gate": motivo de aceitação ou rejeição;
- "Captura": resolução e frequência da captura.

Privacidade

Esta versão não solicita permissão de internet.

A captura, análise, geração e apresentação dos quadros acontecem localmente no aparelho. Nenhum vídeo ou imagem é enviado para servidores.

Quadros de diagnóstico somente são salvos quando o usuário toca em Salvar quadro. Arquivos CSV podem conter informações técnicas da execução e devem ser revisados antes de serem compartilhados.

Limitações conhecidas

Esta é uma versão Public Preview, não uma versão final.

- Os resultados variam de acordo com aparelho, fabricante, jogo e versão do Android.
- O aplicativo não possui acesso aos vetores de movimento internos dos jogos.
- Em 3–5 FPS existem poucos quadros reais para reconstruir corretamente movimento e oclusão.
- A geração pode produzir borrão, ghosting ou deformações.
- O overlay pode sofrer jitter ou atraso do compositor do Android.
- A resolução de captura pode limitar a qualidade do upscale.
- Alguns aparelhos podem encerrar o serviço por economia de bateria.
- O projeto ainda não garante transformar 4 FPS em 20–25 FPS percebidos.
- Não é recomendado para partidas competitivas ou gravações importantes.

Aviso

Este software está em desenvolvimento e deve ser usado para testes. Ele pode apresentar falhas visuais, perda de desempenho, encerramentos inesperados ou incompatibilidade com determinados jogos.

Envie relatórios contendo:

- modelo do aparelho;
- versão do Android;
- jogo utilizado;
- FPS sem o Frame Generator;
- FPS com o Frame Generator;
- Fonte, Gen, Show, Late, Cob, Gate e Proc/Bud;
- duração do teste;
- screenshot da notificação.

Verificação do arquivo

Compare o SHA-256 do APK com o checksum disponibilizado nesta Release antes de instalar.

Licença

Distribuído sob a Apache License 2.0.


Download e instalação

A versão mais recente do Frame Generator V10 está disponível na seção Releases deste repositório.

Instalação

1. Baixe o APK correspondente à versão mais recente.
2. Autorize a instalação de aplicativos desta fonte no Android.
3. Instale e abra o aplicativo.
4. Ative o serviço de acessibilidade Frame Generator V10 Overlay.
5. Toque em Iniciar Frame Generator V10.
6. Autorize a captura da tela ou somente do aplicativo desejado.
7. Abra o jogo e acompanhe as métricas pela notificação.

Segurança e privacidade

O aplicativo não solicita permissão de internet. O processamento dos quadros ocorre localmente no aparelho.

O serviço de acessibilidade é usado somente para exibir o overlay sem bloquear os controles por toque. A versão publicada não solicita leitura do conteúdo das janelas.

Estado do projeto

O Frame Generator V10 está em Public Preview. Os resultados variam conforme o aparelho, o jogo e o compositor do Android. Artefatos visuais, atrasos, quedas de desempenho e incompatibilidades ainda podem ocorrer.
