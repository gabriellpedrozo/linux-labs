# Terminal no Linux: Manipulando Diretórios

Manipulação de diretórios no Linux por meio do terminal, incluindo criação, navegação e remoção de diretórios.

## Comandos

| Comando | Função |
|---|---|
| `mkdir` | Cria um novo diretório. |
| `mkdir -p` | Cria diretórios e subdiretórios, incluindo os diretórios intermediários. |
| `cd` | Permite entrar ou navegar entre diretórios. |
| `cd ..` | Volta para o diretório pai. |
| `cd ~` | Vai para o diretório pessoal do usuário. |
| `cd /` | Vai para o diretório raiz do sistema. |
| `pwd` | Mostra o caminho completo do diretório atual. |
| `ls` | Lista arquivos e diretórios. |
| `ls -l` | Exibe arquivos e diretórios em formato detalhado. |
| `ls -a` | Mostra arquivos e diretórios ocultos. |
| `ls -la` | Mostra arquivos ocultos em formato detalhado. |
| `rmdir` | Remove um diretório vazio. |
| `rm -r` | Remove um diretório e seu conteúdo recursivamente. |
| `rm -ri` | Remove diretórios e conteúdos solicitando confirmação. |

## Parâmetros comuns

| Parâmetro | Nome | Uso no gerenciamento de diretórios |
|---|---|---|
| `-a` | `--all` | Mostra todos os arquivos e diretórios, incluindo ocultos. |
| `-l` | `--long` | Exibe informações detalhadas. |
| `-p` | `--parents` | Cria os diretórios intermediários necessários. |
| `-r` | `--recursive` | Executa a ação de forma recursiva nos subdiretórios. |
| `-i` | `--interactive` | Solicita confirmação antes de determinadas ações. |

## Caminhos

| Símbolo | Significado |
|---|---|
| `/` | Diretório raiz do sistema. |
| `~` | Diretório pessoal do usuário. |
| `.` | Diretório atual. |
| `..` | Diretório pai. |

### Caminho absoluto

Indica o caminho completo a partir da raiz `/`.

```bash`
cd /home/usuario/Documentos


Nesta aula, aprendi a criar, navegar e remover diretórios pelo terminal, além de entender a diferença entre caminhos absolutos e relativos e o uso de parâmetros para facilitar a manipulação de diretórios.