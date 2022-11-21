# Questões Código

* Finalize o código apresentado
    1. Codifique as áreas comentadas com o que é solicitado
    2. Ajuste os erros do código
    3. No final o programa deve conter os seguintes dados
        1. Dados finais:
            | id |                   nome                    |     genero      |
            |----|-------------------------------------------|-----------------|
            | 0  |              'Código Limpo'               |  'Tecnologia'   |
            | 1  |             'Senhor do Anéis'             |   'Fantasia'    |
            | 2  |                'WildCards'                |   'Fantasia'    |
            | 3  | 'Harry Potter e o Prisioneiro de Azkaban' |   'Fantasia'    |
            | 4  |      'Javascript de alto desempenho'      |  'Tecnologia'   |
            | 5  |             'O poder da ação'             | 'Administração' |
            | 6  |            'Arquitetura Limpa'            |  'Tecnologia'   |
            | 7  |     'Harry Potter e a Camara secreta'     |   'Fantasia'    |
            | 8  |                'WildCards'                |   'Esportes'    |
            | 9  |             'O Trono do Sol'              |   'Fantasia'    |

        2. Retorno da listagem de Livros do Tipo Fantasia:
        ```
        Senhor do Anéis, WildCards, Harry Potter e o Prisioneiro de Azkaban, Harry Potter e a Camara secreta, O Trono do Sol
        ```

    4. Utilize este exercicio para explicar os erros que encontrou e o que fez para ajusta-los. Caso ache interessante, explique tambem a implementação do que foi solicitado nos comentários.

        1° Atividade: Foi implementada um Alert comun do jvascript, concatenando a mensgem as variaveis "nome" e "genero" para dar mais sentido na mensagem do erro.

        2° Atividade: Se os parametros ("nome" / "genero"), na função buscarLivro forem iguais aos do indice da variavel listLivros, retornara esse indice. Se forem diferentes, a função não retornara nemhum indice.

        3° Atividade: Criado um array do tipo string para que nela seja inclusa os itens do genero "Fantasia", retornando a lista destes livros.

## Sugestões

A cada etapa do que codificar sugerimos que crie um `commit` e detalhe o que foi feito no `commit`. Isso nos ajuda a ver o progresso do que fez.