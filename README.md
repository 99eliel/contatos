# Contatos

PWA para consultar contatos armazenados no Firebase Firestore e abrir conversas no WhatsApp sem salvar os números na agenda do aparelho.

## Configuração necessária

1. Ative **Authentication > Email/Password** no projeto Firebase.
2. Crie manualmente pelo menos um usuário em **Authentication > Users**.
3. Crie o banco **Cloud Firestore**.
4. Publique as regras presentes em `firestore.rules`.
5. Abra o PWA, faça login e use **Importar contatos** para selecionar o arquivo JSON gerado a partir da base original.

Os dados pessoais não devem ser enviados ao repositório GitHub. O arquivo de importação fica apenas no dispositivo usado para carregar os contatos ao Firestore.
