# Backup da CaptaMais

`contas.db.gz.gpg`: banco de contas, criptografado (gpg, AES-256). Cada commit é um dia.

Para restaurar: `.venv/bin/python backup.py restaurar contas.db.gz.gpg contas.db` no projeto, com a senha em `contas/backup.chave`.
