# TerraFirmaGreg Modern — tradução PT-BR

Tradução comunitária em português brasileiro para **TerraFirmaGreg Modern 0.13.10** (Minecraft 1.20.1, Forge).

> **Estado:** funcional e praticamente 100% traduzida nas chaves de idioma identificadas. O projeto ainda está em validação dentro do jogo; podem existir textos literais em mods ou problemas visuais que as verificações automáticas não detectam.

## Downloads

Baixe os dois arquivos da seção [Releases](https://github.com/Malk10/terrafirmagreg-modern-pt-br/releases/latest):

1. `TerraFirmaGreg_PT-BR_0.13.10.zip` — resource pack com traduções de itens, interfaces, guias e quests.
2. `TerraFirmaGreg_PT-BR_0.13.10_Patch_Quests.zip` — patch de compatibilidade para substituir textos das quests que ficam gravados nos arquivos do FTB Quests e uma mensagem literal do KubeJS.

Os dois arquivos são necessários para a experiência completa em PT-BR.

## Instalação

1. Confirme que sua instância é **TerraFirmaGreg Modern 0.13.10**.
2. Feche o Minecraft.
3. Extraia `TerraFirmaGreg_PT-BR_0.13.10.zip` em `resourcepacks/` da instância.
4. Extraia `TerraFirmaGreg_PT-BR_0.13.10_Patch_Quests.zip` na pasta principal da instância, preservando os caminhos do ZIP. Ele substitui 15 arquivos de capítulos e `kubejs/server_scripts/tfg/events.interactions.js`; inclui a licença LGPL-3.0 da origem desses arquivos.
5. Abra o jogo, ative o resource pack e selecione **Português (Brasil)**.

> Antes de aplicar o patch, mantenha uma cópia dos arquivos que serão substituídos, especialmente se você tiver alterado quests ou scripts. Não aplique em outras versões do modpack.

## Cobertura e verificações

- 201 namespaces e 59.227 chaves de idioma examinadas; nenhuma chave examinada ficou sem entrada PT-BR no pacote gerado.
- 26 capítulos comparados individualmente ao original 0.13.10; 656 textos literais passaram a usar chaves localizadas.
- O patch substitui somente 15 capítulos que contêm mudanças textuais. IDs, tarefas, recompensas, dependências e estrutura das quests foram preservados.
- 3.847 chaves de idioma de quests e um texto de script cobertos.
- Foram validados os JSONs, a cobertura das chaves, a estrutura das quests e os caminhos e conteúdos dos ZIPs.

As verificações ainda não substituem uma revisão visual completa dentro do Minecraft. “Praticamente 100%” descreve a cobertura das chaves de idioma analisadas, não uma garantia de que todo texto embutido em todos os mods foi localizado.

## Uso de IA/LLMs

Este trabalho teve auxílio de modelos de inteligência artificial/LLMs na tradução, revisão, padronização, comparação de versões e preparação dos arquivos. Houve verificações automatizadas e revisão humana, mas o conteúdo ainda está em validação e não deve ser apresentado como tradução revisada exclusivamente por pessoas.

## Créditos e escopo

- A tradução PT-BR de [KoalApenas](https://github.com/KoalApenas/TerraFirmaGreg-PT-BR) para a versão 0.13.7 foi usada como base. A página do projeto no [CurseForge](https://www.curseforge.com/minecraft/texture-packs/terrafirmagreg-modern-translation-pt-br) declara a licença **Public Domain**. Este projeto credita KoalApenas e não implica endosso ou afiliação.
- O pacote foi adaptado para 0.13.10 e ampliado com traduções, revisões e chaves de idioma para textos de quests.
- TerraFirmaGreg Modern, FTB Quests, KubeJS e os mods incluídos pertencem aos seus respectivos autores. Este projeto comunitário não é oficial e não substitui os arquivos do modpack completo.

Veja [CRÉDITOS-E-LICENÇAS.md](CRÉDITOS-E-LICENÇAS.md) e [VALIDAÇÃO.md](VALIDAÇÃO.md) para detalhes.

## Compatibilidade

Esta versão foi preparada para TerraFirmaGreg Modern **0.13.10**, Minecraft **1.20.1**, Forge. Atualizações do modpack podem alterar os arquivos de quests; aguarde um patch correspondente antes de aplicar em uma versão diferente.
