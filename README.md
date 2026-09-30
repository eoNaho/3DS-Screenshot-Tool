# 3DS Screenshot Tool

Uma ferramenta web estática, leve e **100% offline** para unir e formatar capturas de tela do Nintendo 3DS (`_top` e `_bot`) geradas pelo **Luma3DS CFW**, **Citra** ou **melonDS**.

---

## Recursos

### 1. Mockup em Carcaças de 3DS
Encaixa automaticamente as duas telas dentro de modelos do console com alinhamento preciso e sem bordas brancas vazando:
* **New Nintendo 3DS XL (Vermelho Metálico)**: Visão frontal direta (`798 × 854 px`).
* **Nintendo 3DS XL (Azul Clássico)**: Visão tridimensional com perspectiva trapezoidal na tela de toque (`835 × 703 px`).
* Exportação em PNG com fundo transparente ao redor do console.

### 2. Modo 400 × 480 (Padrão 3DSScreenshotTool)
* Reproduz o formato clássico: Tela superior `400 × 240 px` e tela inferior `320 × 240 px` centralizada.
* Fundo transparente nas laterais da tela inferior e espaçamento ajustável entre as telas.

### 3. Modo Grade (Mosaico do Time)
* Organiza várias capturas juntas em colunas personalizáveis (2, 3 ou 6 colunas).
* Ideal para exibir times completos de Pokémon (ex: 2 linhas de 3 Pokémon).

---

## Usabilidade e Produtividade

* **Arrastar Pastas ou Arquivos**: Suporte a Drag & Drop de arquivos avulsos ou da pasta de capturas inteira (`prints/`).
* **Detecção Automática**: Pareia automaticamente arquivos que contenham `_top` e `_bot` no nome.
* **Navegação por Teclado**: Use as setas `←` e `→` para folhear rapidamente entre as capturas.
* **Área de Transferência**: Botão para copiar a imagem renderizada diretamente para a área de transferência (para colar com `Ctrl + V` no Discord, WhatsApp ou Twitter).
* **Download em Lote**: Baixe todas as capturas combinadas de uma só vez em arquivos PNG individuais.
* **100% Local**: Processamento via HTML5 Canvas no próprio navegador, sem uploads para servidores externos e sem necessidade de conexão com a internet.

---

## Como Usar

1. Clone este repositório ou baixe o arquivo `index.html`:
   ```bash
   git clone https://github.com/seu-usuario/3ds-screenshot-tool.git
   ```
2. Abra o arquivo `index.html` em qualquer navegador web moderno (Chrome, Edge, Firefox, Brave, etc.).
3. Arraste suas capturas de tela (`.bmp` ou `.png`) para a janela.
4. Escolha o modo de visualização desejado na barra lateral e clique em **Baixar PNG**.

---

## Compatibilidade de Arquivos

* Capturas diretas do Luma3DS (`sdmc:/luma/screenshots/`)
* Emulador Citra (`.bmp` ou `.png`)
* melonDS / DeSmuME
* Imagens nos formatos BMP, PNG, JPG e WebP

---

## Licença

Distribuído sob a licença MIT. Consulte `LICENSE` para mais informações.
