# Terminal no Linux: Referência Global

Uso de comandos de referência global no Linux para localizar e consultar informações sobre arquivos, diretórios e comandos do sistema.

## Comandos

| Comando | Função |
|---|---|
| `find` | Procura arquivos e diretórios a partir de um local definido. |
| `locate` | Localiza arquivos utilizando uma base de dados de nomes. |
| `which` | Mostra o caminho do executável de um comando. |
| `whereis` | Localiza arquivos relacionados a um comando, como binários, fontes e manuais. |
| `grep` | Procura por textos ou padrões dentro de arquivos ou resultados de comandos. |

## Parâmetros comuns

| Parâmetro | Nome | Uso comum |
|---|---|---|
| `-name` | Nome | Procura arquivos ou diretórios pelo nome. |
| `-type` | Tipo | Define o tipo de item que será procurado. |
| `-iname` | Ignora maiúsculas/minúsculas | Faz a busca pelo nome sem diferenciar letras maiúsculas e minúsculas. |
| `-i` | Ignore case | Ignora diferenças entre letras maiúsculas e minúsculas em buscas com `grep`. |
| `-r` | Recursive | Procura recursivamente dentro de diretórios. |
| `-n` | Number | Exibe o número das linhas encontradas. |
| `-v` | Invert match | Mostra resultados que não correspondem ao padrão informado. |

## Tipos de arquivos no `find`

| Tipo | Significado |
|---|---|
| `f` | Arquivo comum. |
| `d` | Diretório. |
| `l` | Link simbólico. |

Nesta aula, aprendi a utilizar ferramentas de busca e referência global para localizar arquivos, diretórios, comandos e informações dentro do sistema Linux.
