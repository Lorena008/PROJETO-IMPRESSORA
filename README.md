# README – Sistema PDV Elgin

Este projeto apresenta um PDV básico desenvolvido em Java, criado para se comunicar com uma impressora Elgin utilizando a biblioteca oficial disponibilizada pela marca.
O sistema funciona pelo console e oferece um menu com ações de impressão e comandos comuns em ambientes de automação comercial.

# Como abrir o projeto no IntelliJ

1. Baixe o arquivo compactado
2. Extraia a pasta para qualquer local da sua máquina
3. Abra o IntelliJ
4. Clique em **Open**
5. Selecione a pasta do projeto que você acabou de extrair
6. Aguarde o ambiente carregar os arquivos

# Como executar o programa

1. Abra o arquivo `Main.java`
2. Clique em **Run**
3. O menu será exibido no console:

1 - Configurar Conexao
2 - Abrir Conexao
3 - Impressao Texto
4 - Impressao QRCode
5 - Impressao Cod Barras
6 - Impressao XML SAT
7 - Impressao XML Canc SAT
8 - Abrir Gaveta Elgin
9 - Abrir Gaveta
10 - Sinal Sonoro
0 - Fechar Conexao e Sair

Digite o número da ação desejada.

# Recursos disponíveis no sistema

O programa utiliza todas as rotinas fornecidas pela biblioteca da impressora, incluindo:

* Abrir e fechar a conexão
* Impressão de texto
* Impressão de QR Code
* Impressão de código de barras
* Avanço de papel
* Corte de papel
* Comando de abertura de gaveta
* Sinal sonoro
* Impressão de XML SAT e XML de cancelamento

A lógica está separada em funções e o menu é mantido ativo através de laços de repetição e estruturas condicionais.

# Testando na impressora

1. Conecte a impressora ao computador
2. No menu, configure a conexão conforme o modelo
3. Abra a conexão
4. Execute qualquer ação para verificar o funcionamento

Se a impressora responder, a comunicação está correta.

# Considerações finais

Este projeto demonstra como criar um PDV simples em Java integrado a impressoras da Elgin, servindo como base para entender o funcionamento da biblioteca e para estudos na área de automação comercial.

Autores:
Heloisa Carvalho
Isaac José
Lorena Mendes
Luan Felipe
Rebecca Vilas Boas
21BTI
