# Criar Repositorio no GitHub de forma Automatizada.
### QUAL O PROPOSITO DO SCRIPT?
- Facilitar a criação de repositorios e envio de arquivos para o mesmo.

### REQUISITOS PARA RODAR O SCRIPT?
- Possuir o ChromeDriver

- Para o envio de arquivos, é recomendado ter uma resolução 1920x1080 (Irei explicar o motivo).

### COMO FUNCIONA O SCRIPT?
- Nas três primeiras linhas nós importamos algumas bibliotecas, sendo elas: PyAutoGui, Selenium, Time.

- Quatro linhas abaixo, nós pegamos algumas informações do usuario como: Usuario, Senha, Nome do Repositorio, Nome do Arquivo.

- Foi estabelecido um tempo de 1.5 segundos para preencher os campos de texto e 1.2 segundos para clicar em 'Entrar' e fazer o login.

- Estabeleci mais alguns tempos de ação com 1.2 segundos para: Clicar em New, Inserir o nome do Repositorio e Clicar em criar.

- Após isso estabeleci um tempo de 1.5 segundos para mover o cursor do mouse até "choose files", 1.3 segundos para mover o cursor para uma área em branco e clicar. Logo após fiz uma sequência de 'tab' e 'down' para que pudesse chegar na área de trabalho, procurar pelo arquivo e fazer o envio do arquivo assim concluindo todo o script.

### OBSERVAÇÕES DO SCRIPT
- Tive complicações com o selenium para clicar em 'choose files', então foi usado o PyAutoGui para essa operação, porém, o PyAutoGui para executar a ação de mover o mouse precisa da posição do link e a posição pode variar de resolução para resolução.

- Quando eu fiz com que o script clique em um 'espaço em branco' na seleção de arquivos, foi para justamente o 'tab' funcionar corretamente e para que possamos navegar até a área de trabalho, pesquisar nosso arquivo e enviar.

- Este script envia UM ARQUIVO direto, não uma pasta contendo o arquivo.

### TEMPO DE CRIAÇÃO
- Levei cerca de 30/40 minutos para concluir todo o script (contando com os testes que foram feitos para garantir que tudo funcionasse como deveria).

## FIQUEM Á VONTADE PARA PEGAR O CÓDIGO E UTILIZAR PARA AUTOMATIZAR ESSA TAREFA.
