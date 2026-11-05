# Changelog

## [1.2.0] - 2026-11-04

- Gera o currículo otimizado em Markdown e PDF com a mesma base `curriculo_<primeiro_nome>_<ultimo_nome>` e salva ambos na pasta escolhida pelo usuário.
- Solicita o destino uma única vez e verifica o conteúdo e a apresentação do PDF antes de entregar os links dos dois arquivos.

## [1.1.0] - 2026-11-04

- Gera o arquivo `curriculo_<primeiro_nome>_<ultimo_nome>.md` em UTF-8 ao final da análise, contendo somente o currículo otimizado.
- Pergunta a pasta de destino quando ainda não informada e verifica o arquivo salvo antes de entregar o link.

## [1.0.0] - 2026-11-04

- Compara currículo PDF com uma vaga por URL ou texto e calcula aderência com critérios e evidências explícitos.
- Gera currículo direcionado em Markdown, preservando as qualificações documentadas no original.
