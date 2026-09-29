# Registro de validação — 0.13.10

## Estado

O pacote é funcional e cobre praticamente todas as chaves de idioma examinadas. O projeto segue em validação: ainda falta percorrer visualmente as interfaces, livros, menus e quests dentro do Minecraft.

## Verificações estáticas

- **Idiomas:** 201 namespaces e 59.227 chaves de origem examinadas; 0 chaves examinadas sem uma entrada PT-BR no pacote gerado.
- **Quests:** 26 capítulos comparados individualmente com o original 0.13.10; 656 textos literais convertidos em referências de idioma; 0 mudanças estruturais e 0 chaves de quest ausentes.
- **Patch de quests:** 15 capítulos realmente alterados são distribuídos. Os outros 11 capítulos comparados não precisam ser substituídos.
- **Chaves de quests:** 3.847 entradas localizadas.
- **Pacote:** 663 arquivos; JSONs válidos; caminhos internos do ZIP verificados.
- **KubeJS:** uma mensagem literal convertida para chave de idioma; a comparação confirma que essa é a única alteração naquele script.
- **Guias:** estrutura e links/código preservados nas verificações automatizadas.

## Limitações conhecidas

- A ausência de chaves sem tradução não prova que não existam textos literais em código compilado ou arquivos não examinados.
- A validação estática não detecta cortes de texto, problemas de fonte, formatação, quebra de linha ou inconsistências visuais em jogo.
- O patch de quests é específico da versão 0.13.10 e pode sobrescrever personalizações locais nos arquivos incluídos.

## Política de contribuição do projeto oficial

A documentação oficial de contribuição do TerraFirmaGreg Modern declara que contribuições de tradução feitas com IA/LLMs não são aceitas no projeto oficial e encaminha traduções ao Crowdin. Este repositório independente divulga o uso de IA/LLMs e não representa uma contribuição oficial. Consulte a regra atual antes de tentar enviar qualquer material ao projeto original.
