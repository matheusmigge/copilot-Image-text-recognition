# Projeto para o Bootcamp Dio Decola Tech 2025
Pequeno estudo do reconhecimento de texto em imagens no Copilot.

## Procedimento:
1. Foram escolhidas algumas imagens contendo diferentes tipos de textos para avaliar a precisão do reconhecimento. 

- Imagem 1: Texto em fontes nítidas e legíveis;
- Imagem 2: Texto manuscrito;
- Imagem 3: Texto distorcido ou parcialmente oculto;
- Imagem 4: Texto sobre fundos complexos (ex: imagem com baixa visibilidade);
- Imagem 5: Texto parcialmente coberto por sombras;

2. Entrada no Copilot.

- Inserir cada imagem no Copilot e solicitar a extração do texto contido nela.
- Comparar o resultado com o texto real esperado.

3. Registro dos resultados:

- Armazenar o texto extraído pelo Copilot para análise comparativa.
- Identificar possíveis falhas, como erros de reconhecimento, omissões ou trocas de caracteres.

# Critérios de Avaliação e resultados

**Precisão na extração: O texto extraído corresponde exatamente ao original?**

Sim. Em todas as imagens testadas, o Copilot foi capaz de retornar com exatidão todos as palavras e não apenas isso: interpretar o que foi extraído e sugerir ações relacionadas ao texto extraído, como por exemplo, de buscar mais informações acerca do assunto, dar inspirações sobre o tema e fazer perguntas, como "há algo especial nesta citação para você?" (imagem 2) ou, sobre uma placa de rua (imagem 5), ele pergunta "Esse é um cruzamento em algum lugar da sua cidade?".

Apenas uma das imagens testadas, essa extração não ocorreu de maneira perfeita: foi na foto de um livro aberto, com a página distorcida e com o texto parcialmente oculto (imagem 3). Para as palavras que estavam parcialmente ocultas, ou seja, simplesmente não estavam completas, o Copilot retornou palavras completas (provavelmente sugerindo, em cada caso, qual seria a palavra completa). Ainda assim, o ideal é que ele tivesse retornado exatamente o que estava contido no texto, sinalizasse perfeitamente as palavras transcrita literalmente e quais ele estava sugerindo. Ainda assim, para esta imagem, o Copilot foi capaz de identificar que o texto estava incompleto e sugeriu explorar sobre o tema para dar mais contexto sobre o assunto do livro.  

**Capacidade de lidar com variações: O Copilot consegue identificar corretamente texto em diferentes estilos, tamanhos e fundos?**

Sim. Com relação a identificação dos textos, o Copilot foi capaz de extrair perfeitamente todas as palavras, independente de todas estas variáveis. O único ponto a ressaltar foi o caso da imagem 3, mencionado no ponto anterior.

**Interpretação contextual: Se houver ambiguidades (ex: palavras com caracteres borrados), o Copilot tenta inferir a palavra correta?**

Sim. Ele tentou inferir a palavra correta, mas não informou que essa palavra não estava literalmente visivel na imagem. Ainda assim, ele foi capaz de identificar esse obstáculo e mencionar isso, mas sem dizer, dentre o texto extraído, quais estava realmente na imagem e quais foram inferidas por ele.

**Sensibilidade a ruído: O reconhecimento é afetado por elementos visuais, como sombras ou distorções?**

Parcialmente. Ele teve sucesso em todas as imagens, menos na imagem 3, que, além dos pontos mencionados, também apresentava distorção da folha do livro levemente flexionada. Como as linhas de cada verso do texto não estavam totalmente retas, ouve dificuldade do Copilot interpretar quais palavras permaneciam na mesma linha e quais estavam nas linhas superiores e inferiores. Ainda assim, essa imagem em questão também trazia como obstáculo o fato do boa parte da página estar ocultada. Talvez, numa outra tentativa, com a folha flexionada, mas com todo o texto à mostra, o Copilot poderia inferir melhor as linhas sob distorção da página, baseada no contexto da folha.

# Aplicações Práticas

Digitalização e Arquivamento de Documentos
- Conversão de documentos físicos em arquivos digitais pesquisáveis.
- Indexação automática de conteúdo para facilitar buscas.

Acessibilidade
- Leitura de textos em imagens para auxiliar pessoas com deficiência visual.
- Tradução automática de textos em imagens para acessibilidade multilíngue.

Análise e Extração de Dados
- Captura de informações de faturas, contratos e formulários.
- Extração de textos de imagens para automação de processos empresariais.

Monitoramento de Mídia e Redes Sociais
- Análise de textos em imagens postadas nas redes sociais.
- Identificação de padrões de comunicação, fake news ou tendências.

Tradução e Localização
- Tradução automática de cardápios, placas e documentos fotografados.
- Adaptação de textos para diferentes idiomas e contextos culturais.

Segurança e Conformidade
- Monitoramento de documentos para detectar fraudes ou falsificações.
- Reconhecimento de textos em imagens para controle de identidade e verificação de documentos.

Educação e Pesquisa
- Extração e organização de textos de livros e artigos acadêmicos digitalizados.
- Auxílio na conversão de anotações manuscritas em textos editáveis.

### Os inputs e outputs deste estudo podem ser encontrados nas suas respectivas pastas, nos arquivos deste repositório. 
