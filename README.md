# PINTAR-O-SETI-

Livro de colorir digital, responsivo e otimizado para toque em celulares e tablets. Publicação estática: não exige servidor, banco de dados, API ou instalação de dependências.

## Publicar no GitHub Pages

1. Abra **Settings** do repositório.
2. Entre em **Pages**.
3. Em **Build and deployment**, selecione **Deploy from a branch**.
4. Escolha a branch **main** e a pasta **/(root)**.
5. Salve. O GitHub publicará o aplicativo em:

   https://detiillimichel-max.github.io/PINTAR-O-SETI-/

## Como usar

- Toque em uma região fechada do desenho para preenchê-la com a cor atual.
- Escolha uma cor na paleta e uma das sete tonalidades.
- Use **Desfazer** e **Refazer** para voltar ou reaplicar pinturas.
- A **Borracha** devolve as regiões tocadas ao branco.
- **Limpar** remove todas as cores do desenho atual, após confirmação.
- **Salvar** exporta a arte como PNG.
- Use os controles de zoom e a galeria para alternar entre Raposa Mandala, Flor Mandala e Borboleta.

## Estrutura

- `index.html` — HTML5, CSS3 e JavaScript puro. Contém a interface, os desenhos SVG vetoriais, o balde de tinta, histórico, paleta, zoom e exportação PNG.

## Observações técnicas

O aplicativo funciona como site estático e pode ser hospedado diretamente pelo GitHub Pages. As pinturas são mantidas na memória da página durante a sessão; ainda não há salvamento automático entre visitas.
