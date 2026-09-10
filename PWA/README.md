# Arcanum PWA

Versão web instalável do Arcanum. Não requer conta Apple Developer nem uma licença anual.

## Publicar

Publica **o conteúdo desta pasta `PWA`** num alojamento estático com HTTPS (por exemplo, GitHub Pages, Cloudflare Pages ou Netlify). Não é necessário servidor, base de dados ou variáveis de ambiente.

Depois, no iPhone:

1. Abre o URL no Safari.
2. Toca em **Partilhar**.
3. Escolhe **Adicionar ao ecrã principal**.

A aplicação passa a abrir como uma app independente e mantém uma cópia offline dos ficheiros da interface. Os livros e definições são guardados localmente no navegador do dispositivo. Usa **Definições → Exportar biblioteca** antes de trocar, restaurar ou limpar o iPhone.

## Nota sobre migração

Esta PWA não lê diretamente a base de dados SwiftData da aplicação iOS. Para levar os dados existentes para a versão web, é preciso primeiro criar uma exportação JSON na app SwiftUI que respeite o formato de importação da PWA.
