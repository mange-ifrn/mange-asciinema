# Ajuda

Saída do comando `asciinema -h`:

Uso: 

- `asciinema [-h] [--version] {rec,play,cat,upload,auth} ...`

Você pode interpretar a linha acima assim (Veja as [referências](referencias.md)):

$$
asciinema 
\begin{Bmatrix}
rec \\
play \\
cat \\
upload \\
auth \\
\end{Bmatrix}
$$

Grave e compartilhe suas sessões de terminal, da maneira certa.


## Argumentos posicionais

| Argumento | Função                                                                          |
| --------- | ------------------------------------------------------------------------------- |
| rec       | Gravar sessão de terminal                                                       |
| play      | Repetir sessão de terminal                                                      |
| cat       | Imprimir saída completa da sessão do terminal                                   |
| upload    | Faça upload da sessão de terminal salva localmente para <https://asciinema.org> |
| auth      | Gerenciar gravações na conta asciinema.org                                      |

## Argumentos opcionais

| Argumento      | Função                                 |
| -------------- | -------------------------------------- |
| `-h`, `--help` | show this help message and exit        |
| `--version`    | show program's version number and exit |

