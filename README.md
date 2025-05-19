# Comandos mais comuns do Tailwind CSS

## 1. Layout e espaçamento
- `p-4` → padding (espacamento interno) de 1rem  
- `m-4` → margin (espacamento externo) de 1rem  
- `pt-2`, `pb-2`, `pl-3`, `pr-3` → padding top, bottom, left, right  
- `mt-2`, `mb-2`, `ml-3`, `mr-3` → margin top, bottom, left, right  
- `w-full` → largura 100%  
- `h-full` → altura 100%  
- `max-w-md` → largura máxima média (aprox 28rem)  
- `container` → largura máxima responsiva para conteúdo centralizado  

## 2. Flexbox
- `flex` → ativa display flex  
- `flex-row` → organiza itens em linha horizontal (padrão)  
- `flex-col` → organiza itens em coluna vertical  
- `justify-center` → centraliza horizontalmente os itens  
- `justify-between` → espaça itens com espaço entre eles  
- `items-center` → centraliza verticalmente os itens  

## 3. Texto e fontes
- `text-center` → alinha texto ao centro  
- `text-left` → alinha texto à esquerda  
- `text-right` → alinha texto à direita  
- `text-xl` → texto maior (extra large)  
- `text-sm` → texto menor (small)  
- `font-bold` → texto em negrito  
- `font-light` → texto mais fino  
- `text-gray-500` → texto cinza médio (cor pré-definida)  
- `text-white` → texto branco  

## 4. Background
- `bg-blue-500` → fundo azul médio  
- `bg-red-400` → fundo vermelho claro  
- `bg-gray-100` → fundo cinza claro  
- `bg-transparent` → fundo transparente  

## 5. Bordas
- `border` → adiciona borda fina padrão  
- `border-2` → borda com 2px  
- `border-gray-300` → cor da borda cinza claro  
- `rounded` → borda arredondada pequena  
- `rounded-lg` → borda arredondada maior  
- `rounded-full` → borda totalmente arredondada (círculo)  

## 6. Tamanhos
- `h-8` → altura 2rem  
- `w-8` → largura 2rem  
- `h-16` → altura 4rem  
- `w-16` → largura 4rem  

## 7. Sombra
- `shadow` → sombra padrão leve  
- `shadow-lg` → sombra maior  
- `shadow-md` → sombra média  

## 8. Outros úteis
- `cursor-pointer` → cursor muda para pointer (mãozinha)  
- `opacity-50` → opacidade 50%  
- `overflow-hidden` → esconde overflow  
- `hidden` → esconde elemento  

---

## Exemplo simples de uso:

```html
<button class="bg-blue-500 text-white px-4 py-2 rounded hover:bg-blue-700">
  Clique aqui
</button>
