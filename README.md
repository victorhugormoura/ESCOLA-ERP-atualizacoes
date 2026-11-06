# ESCOLA-ERP — canal de atualizações

Este repositório publica as versões do **ESCOLA-ERP** que os computadores das escolas baixam sozinhos.

- `versao.json`: versão atual, notas e SHA-256 do pacote, assinado com Ed25519 pelo autor.
- `pacotes/EscolaERP-x.y.z.zip`: arquivos do programa. Nenhum dado de escola.

O programa só instala um pacote se a assinatura conferir com a chave pública embutida nele, se o SHA-256 bater e se a versão nova passar num teste antes de substituir a atual.

O código-fonte fica no repositório privado do projeto. Fase beta: licença gratuita. Uso, cópia e distribuição seguem o `LICENSE`.

Copyright © 2026 Victor Hugo Rebollo de Moura — Infinity Technology · victorhugormoura@gmail.com
