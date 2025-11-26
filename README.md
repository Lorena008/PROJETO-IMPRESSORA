Este trabalho apresenta um PDV simples desenvolvido em Java, criado para realizar operações básicas com uma impressora da Elgin. Toda a comunicação com o equipamento é feita por meio da biblioteca oficial disponibilizada pela empresa. O sistema funciona no console e disponibiliza um menu com diferentes ações relacionadas à impressão e comandos usados em ambientes comerciais.

# Abrindo o projeto no IntelliJ

Após baixar o arquivo compactado, basta extrair a pasta em qualquer local do computador e abrir o IntelliJ. Em vez de criar um projeto novo, basta selecionar a opção de abrir um diretório existente e apontar para a pasta extraída. Depois disso, o ambiente já carrega os arquivos e o código fica pronto para ser acessado.

# Configuração da biblioteca da impressora

A pasta do projeto possui um diretório chamado **lib**, onde estão o arquivo `.jar` fornecido pela Elgin e as bibliotecas nativas necessárias. Para que o projeto reconheça esse material no IntelliJ, é preciso ir até a seção de configuração do projeto e incluir a biblioteca manualmente, selecionando o arquivo `.jar` que está dentro da pasta mencionada. Feita essa inclusão, o código já consegue acessar as funções da impressora.

# Execução do sistema

Com o projeto aberto, basta localizar o arquivo `Main.java` e executá-lo. O menu principal aparece diretamente no console, reunindo todas as opções implementadas:

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

Cada número corresponde a uma função do sistema, permitindo testar e utilizar os recursos da impressora conforme necessário.

# Recursos disponíveis

O programa utiliza todas as funções exigidas no projeto, incluindo abertura e fechamento da conexão, impressão de texto, códigos de barras e QR Code, avanço e corte do papel, comando de abertura da gaveta, emissão de sinal sonoro e impressão dos XMLs de venda e cancelamento do SAT. A organização do código foi feita com funções separadas, condicionais e laços de repetição para manter o menu funcionando de maneira contínua.

# Teste com a impressora

Com a impressora ligada e conectada ao computador, é possível configurar a comunicação diretamente pelo menu do sistema. Depois de ajustar os parâmetros e abrir a conexão, qualquer uma das opções pode ser utilizada para verificar o comportamento do equipamento.

# Autores
**Heloisa Carvalho**
**Isaac José**
**Lorena Mendes**
**Luan Felipe**
**Rebecca Vilas Boas**
**21BTI**
