# PDF → Imagens (Offline-first) com Censura LGPD

Aplicação web estática para:
- Converter PDF em imagens PNG/JPG.
- Adicionar barra de evento por página.
- Editar páginas com tarja preta e blur.
- Aplicar **censura automática LGPD** via OCR (heurística para CPF, CNPJ, RG, e-mail e telefone).

## Como usar

Basta abrir `index.html` no navegador.

Fluxo recomendado:
1. Informe o número do evento.
2. Selecione um PDF.
3. Clique em **Converter para Imagens**.
4. Use **Auto censura LGPD** para rodar OCR nas páginas.
5. Revise manualmente clicando em cada imagem (editor).
6. Exporte em ZIP ou página a página.

## Observações

- O app é offline-first para conversão e edição.
- A função de OCR automático usa `tesseract.js` por CDN na primeira execução (necessita conexão para baixar biblioteca/modelo).
- Para conformidade LGPD, mantenha revisão humana antes da exportação final.
