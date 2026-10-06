# FENIÉ PRO — Site institucional

Site estático da FENIÉ PRO, distribuidora de cosméticos profissionais em Curitiba e Região Metropolitana.

## Páginas

- Página inicial: `dist/index.html`
- Bio para Instagram: `dist/bio/index.html`
- Olenka: `dist/marcas/olenka/index.html`

Imagens, vídeos e outros recursos estão em `dist/assets/`.

## Visualizar localmente

Não é necessário instalar dependências ou executar uma compilação.

```sh
cd dist
python -m http.server 8080
```

Acesse `http://localhost:8080`.

## Publicar na HostGator

Envie o **conteúdo** de `dist/` para a pasta raiz do domínio no Gerenciador de Arquivos do cPanel. Preserve a estrutura das subpastas e faça backup da versão atual antes de substituir arquivos.

A configuração `.openai/hosting.json` registra a hospedagem original e não é necessária para servir o site na HostGator.

## Versão importada

Versão 46 do site institucional, com Hero em camadas e trecho adicional de rolagem, importada em 06/10/2026.

Commit de origem: `2ed84da7eb20197220f5108747ea0e86e4e649da`.
