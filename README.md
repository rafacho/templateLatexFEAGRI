# Template Latex FEAGRI
Template de tese no padrão de artigo da Faculdade de Engenharia Agrícola da Unicamp

Cada artigo está dentro de uma pasta, caso queira incluir mais algum, crie a pasta e faça o input no arquivo principal (tese_template.tex).

Todas as configurações estão em settings.tex, caso queira incluir algum pacote, faça nesse arquivo.

O arquivo principal a ser compilado é o tese_template.tex, ele chama todos os outros arquivos. Caso precise criar um arquivo novo, este deve ser chamado no arquivo principal.

As referências devem ser incluídas no arquivo bibliografia.bib e chamada no texto com os comandos \cite{<nomeDaReferência>} para citação em parênteses "(autor, ano)" ou com o comando textcite{<nomeDaReferência>} para citação em linha "autor (ano)".
