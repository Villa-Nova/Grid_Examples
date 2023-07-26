## PROPRIEDADES DE ALINHAMENTO

Existem 9 propriedades fundamentais:

**6 aplicadas em container(pai):**

`align-content`: Move todos os filhos para direção desejada no eixo Y;

`justify-content`: Move todos os filhos para direção desejada no eixo X;

`place-content`: Junção do align-content e justify-content movendo nos dois eixos X e Y;

___
`align-items`: Muda a "altura" do item (filho) dentro do espaço original do próprio item (eixo Y);

`justify-items`: Muda a "largura" do item (filho) dentro do espaço original do próprio item (eixo X);

`place-items`: Redimenciona a "altura" (eixo Y) e "largura" (eixo X) dos itens (filhos) dentro do seu espaço original;

**3 aplicadas em itens(filho):**

`align-self`: Muda a "altura" do item em que foi aplicado, dentro do espaço original do próprio item (eixo Y);

`justify-self`: Muda a "largura" do item em que foi aplicado, dentro do espaço original do próprio item (eixo X);

`place-self`: Redimenciona a "altura" (eixo Y) e "largura" (eixo X), dentro do seu espaço original do item aplicado;

Então podemos separar em 3 grupos:
`align`, `justify` e `place`

E cada um deles irá observar ou o:
- Conteúdo do elemento `content`
- Itens do elemento `items`
- O próprio elemento `self`