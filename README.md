# 10 estilos de animação no Claude

A mesma cena em 10 estilos diferentes. Você troca só a cena e reaproveita os estilos.

Lista mantida pela [Exos Marketing](https://www.instagram.com/exosmkt/). Os prompts são livres para copiar, adaptar e usar.

## Como usar

1. No Claude, ligue um conector de vídeo. Os clipes do Reel foram gerados no **Seedance 2.5** pelo conector da Higgsfield (Conectores → Adicionar conector personalizado → `https://mcp.higgsfield.ai/mcp`). O Claude não gera vídeo sozinho: ele escreve o pedido e aciona o modelo. A Higgsfield é um serviço à parte, com conta e plano próprios.
2. Copie o **estilo** que você quer e cole a **sua cena** logo depois.
3. Peça no chat: `Gere um vídeo vertical 9:16 de 4 segundos, sem áudio, com este prompt:` e cole o prompt.

Os prompts estão em inglês porque o modelo responde melhor assim. Eles descrevem o visual sem citar marca (marcas costumam ser bloqueadas).

## A cena (troque pela sua)

```
A young soccer player wearing a plain yellow jersey and blue shorts dribbles a soccer ball while running toward the camera on a stadium pitch at golden hour sunset, stadium lights and crowd in the background. Full body, subject centered, vertical framing, camera tracking backward. No text, no logos, no watermarks.
```

Dica: mantenha o final (`Full body, subject centered, vertical framing… No text, no logos, no watermarks.`). É ele que segura o enquadramento e evita letreiro na imagem.

## Os 10 estilos (cole antes da cena)

### 1. Pixel Art
```
16-bit pixel art animation, retro video game style, chunky visible pixels, limited color palette, crisp pixel edges, sprite animation.
```

### 2. Quadro de Giz
```
Hand-drawn chalk animation on a dark green school blackboard, rough white and colored chalk strokes, chalk dust texture, sketchy outlines, frame-by-frame hand-drawn feel.
```

### 3. Traço Neon
```
Glowing neon line art animation on a pure black background, luminous cyan, yellow and magenta outlines only, no fills, light trails, soft glow bloom.
```

### 4. Estilo PS2
```
Early 2000s sixth-generation console video game graphics, low-poly 3D character models, low-resolution textures, simple flat lighting, slight aliasing, retro sports video game look, gameplay camera.
```
Acrescente no fim da cena: `No HUD.`

### 5. Quadrinhos
```
Comic book animation style, bold black ink outlines, halftone dot shading, saturated flat colors, dynamic speed lines, graphic novel look.
```
Acrescente no fim da cena: `No speech bubbles.`

### 6. Vetor Flat
```
Premium flat vector animation, clean geometric shapes, solid flat colors, no outlines, minimal shading, modern motion graphics style, smooth easing.
```

### 7. Linha Dourada
```
Minimal line art animation, thin elegant metallic gold lines on a deep black background, single continuous line drawing, lots of negative space, subtle golden shimmer, no fills.
```

### 8. 3D de Cinema
```
Cinematic 3D CGI animated feature film style, high-end stylized character animation, expressive face, detailed fabric and grass, volumetric golden light, shallow depth of field, lens flare.
```

### 9. Estilo Lego
Este é o único em que a cena precisa ser reescrita, porque o personagem vira boneco. Prompt completo usado no Reel:
```
Toy brick stop-motion animation, everything built from glossy plastic interlocking building bricks. Medium close shot: a blocky toy minifigure soccer player with a yellow cylindrical head, smiling printed face, plain yellow jersey and blue shorts, fills most of the frame, facing the camera, running toward the camera while dribbling a round black-and-white toy soccer ball on a green studded brick pitch at sunset. Brick-built stadium stands with minifigure crowd blurred in the background, warm golden light, macro lens, slight stop-motion jitter. Full body visible, subject large and centered, vertical framing, camera tracking backward at ground level. No text, no logos, no watermarks.
```

### 10. Massinha
```
Pastel claymation stop-motion animation, soft handmade plasticine clay character and miniature set, visible fingerprints in the clay, pastel color palette, soft studio lighting, slight stop-motion jitter.
```

## Exemplo montado (Pixel Art)

```
16-bit pixel art animation, retro video game style, chunky visible pixels, limited color palette, crisp pixel edges, sprite animation. A young soccer player wearing a plain yellow jersey and blue shorts dribbles a soccer ball while running toward the camera on a stadium pitch at golden hour sunset, stadium lights and crowd in the background. Full body, subject centered, vertical framing, camera tracking backward. No text, no logos, no watermarks.
```

## Configuração usada

- Modelo: Seedance 2.5 · 9:16 · 4 segundos · 720p · sem áudio
- Um clipe por estilo, sem imagem de referência
- Se o personagem sair pequeno ou longe, peça de novo trocando `Full body` por `Medium close shot, subject fills most of the frame`
