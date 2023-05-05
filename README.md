# Bos Backend File Upload Module


Módulo que faz parte da arquitetura BOS (BierOnStack) e serve para adicionar coleções *(resources)*  com recurso de **upload de arquivos** pelo frontend.
Conheça o projeto BOS, sua framework para desenvolver softwares [BOS BierOnStack](https://github.com/eduardo-bier-bos/bos)


## Instalação


Todo projeto criado pelo BOS (BosApp), já tem com a referência para o Bos Backend File Upload Module instalado nativamente.


## Uso


Para usar recursos do FileUpload Module, você deve acessar o dashboard do BOS e adicionar uma coleção do tipo **FileUpload**. Após isso, selecionar a coleção e ir na opção **Event**, para configurar informações de **path e segurança** da coleção.


## Autor

[Carlos Eduardo Bier](https://about.me/eduardo.bier.bos)  
<br>

# Changelog  

## 28-abr-2023 eduardo.bier
Adicinando dependência para o módulo formidable, que é utilizado porém não havia sido adicionado como dependência do módulo.
Corrigindo erro na criação do diretório quando o mesmo não existe e adicionando dependência ao BosBackendHelpers.

## 05-mai-2023 eduardo.bier
Alterando caminho da pasta default utilizada de public para bos-app-web
