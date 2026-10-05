
```md
# Terminal no Linux: Manipulação de Arquivos

Manipulação de arquivos no Linux por meio do terminal, incluindo criação, cópia, movimentação, renomeação, visualização e remoção de arquivos.

## Comandos

| Comando | Função |
|---|---|
| `touch` | Cria um arquivo vazio ou atualiza sua data de modificação. |
| `cat` | Exibe o conteúdo de um arquivo no terminal. |
| `cp` | Copia arquivos ou diretórios. |
| `mv` | Move ou renomeia arquivos e diretórios. |
| `rm` | Remove arquivos. |
| `rm -i` | Remove arquivos solicitando confirmação. |
| `rm -r` | Remove diretórios e seus conteúdos recursivamente. |
| `head` | Mostra as primeiras linhas de um arquivo. |
| `tail` | Mostra as últimas linhas de um arquivo. |
| `file` | Identifica o tipo de um arquivo. |

## Parâmetros comuns

| Parâmetro | Nome | Uso comum |
|---|---|---|
| `-i` | `--interactive` | Solicita confirmação antes de determinadas ações. |
| `-r` | `--recursive` | Executa a ação recursivamente em diretórios e seus conteúdos. |
| `-f` | `--force` | Força a execução, ignorando algumas confirmações. |
| `-v` | `--verbose` | Mostra informações durante a execução. |
| `-n` | `--number` | Numera linhas, dependendo do comando utilizado. |

## Exemplos de manipulação de arquivos

| Exemplo | Função |
|---|---|
| `touch arquivo.txt` | Cria um arquivo vazio. |
| `touch arquivo1.txt arquivo2.txt` | Cria vários arquivos de uma vez. |
| `cat arquivo.txt` | Exibe o conteúdo do arquivo no terminal. |
| `cp arquivo.txt copia.txt` | Cria uma cópia do arquivo com outro nome. |
| `cp arquivo.txt Documentos/` | Copia o arquivo para o diretório `Documentos`. |
| `mv arquivo.txt novo-nome.txt` | Renomeia o arquivo. |
| `mv arquivo.txt Documentos/` | Move o arquivo para o diretório `Documentos`. |
| `rm arquivo.txt` | Remove o arquivo. |
| `rm -i arquivo.txt` | Solicita confirmação antes de remover o arquivo. |
| `head arquivo.txt` | Exibe as primeiras linhas do arquivo. |
| `tail arquivo.txt` | Exibe as últimas linhas do arquivo. |
| `file arquivo.txt` | Identifica o tipo do arquivo. |

Nesta aula, aprendi a criar, visualizar, copiar, mover, renomear e remover arquivos pelo terminal, utilizando comandos que facilitam a organização e o gerenciamento de arquivos no Linux.