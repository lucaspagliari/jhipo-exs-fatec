# jhipo-exercicios:

Criado por:
  https://github.com/pjandl/jhipo
  
Objetivo: Disponibilizar conteúdo para estudo dos alunos de Tecnologia de Análise e Desenvolvimento de Sistemas.

Need Java 1.8 +

Como executar: 
1. Mantenha os arquivos .masm no mesmo diretório que o arquivo .jar correspondente ao JHIPO ou em um subdiretório direto;

2. Em um prompt de comandos, navegue até o diretório onde está o arquivo .jar (utilizando o comando: cd ) utilize a tecla TAB para autopreencher;

3. Execute:
• java -cp jhipo-vyyyyddmm.jar masm +a programs\ex1.masm programs\ex1.asm;
 - O arquivo .asm será automáticamente criado na execução desse comando
 - O comando "+a" mostra o mapa da memória.
 
3.1. Para executar o .asm use o comando: 
• java -cp jhipo-vyyyyddmm.jar jhipovm +o +a (seu diretório)\ex1.asm;

3.2 Para executar o .masm direto use o comando:
• java -cp jhipo-vyyyyddmm.jar masm +e (seu diretório)\ex1.masm;
