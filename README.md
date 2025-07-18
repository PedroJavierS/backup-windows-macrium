# Projeto: Backup no Windows com ferramenta nativa

## Objetivo
Este projeto tem como objetivo documentar um backup simples usando a ferramenta "Cópia de segurança e restauro (Windows 7)" incluída no Windows.

## Etapas realizadas

1. Acedi ao Painel de Controlo e abri "Cópia de segurança e restauro (Windows 7)".
2. Iniciei a configuração do backup clicando em "Configurar cópia de segurança".
3. Escolhi o HDD 2 como destino para armazenar o backup.
4. Durante a configuração, desmarquei a opção de incluir imagem do sistema.
5. Selecionei apenas a "Biblioteca de documentos" para backup.
6. Executei o processo e registrei o resultado.

## Resultados

Backup concluído com sucesso. As imagens do processo foram salvas e servem como documentação do procedimento.

## Prints de tela

![Texto alternativo](inicio-do-backup.png)



### Sobre os arquivos gerados no backup

Durante o processo de backup, o Windows cria uma pasta com os arquivos dos dados selecionados para backup, onde ficam os arquivos e pastas de usuário.

Além disso, é criado um arquivo chamado `MediaID.bin`. Este arquivo é um arquivo de controle que serve para que o Windows identifique e gerencie este backup específico. Ele contém informações técnicas importantes que permitem a restauração correta dos dados no futuro.

**Importante:** Não apague ou altere esse arquivo, pois ele é fundamental para que o backup funcione corretamente.


### Sobre o backup e restauração do Windows 7

A ferramenta de backup utilizada chama-se "Backup e Restauração (Windows 7)" porque foi originalmente introduzida no Windows 7. Apesar do nome, ela continua disponível nas versões atuais do Windows (10, 11) para garantir compatibilidade e funcionalidades consolidadas.

Você pode fazer backups simples dos seus arquivos pessoais ou incluir uma imagem do sistema para criar uma cópia completa do Windows, programas e dados. A inclusão da imagem do sistema leva mais tempo e ocupa mais espaço, mas oferece uma restauração completa em caso de problemas graves.


