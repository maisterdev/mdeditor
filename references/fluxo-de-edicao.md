# Fluxo profissional de edição

Adaptação e síntese dos anexos `fluxo-de-edicao` e `showreel-interface`, somadas a práticas de edição documental/cinematográfica. Use as etapas necessárias ao projeto; não force motion se a história não pede.

1. **Brief e inventário:** objetivo, público, destino, proporção, duração, prazo, ferramenta, arquivos, codecs/resoluções, áudio, referências, direitos e limitações.
2. **Organizar e preparar:** estrutura clara, cópia de trabalho/proxies quando necessário, sincronização, transcrição e seleção de takes. Não renomeie ou mova originais.
3. **Mapa narrativo:** logline, arco, momentos indispensáveis, lacunas e estrutura por cena/beat. Cada afirmação factual rastreável à mídia ou fonte.
4. **Assembly e corte:** selects, primeiro corte, refinamento de ritmo, J/L cuts, continuidade e versão da plataforma. Trave decisões de história antes de trabalho visual custoso.
5. **Mapa visual e assets:** storyboard/cards estáticos antes de animar; listar logo, imagens, arquivos de marca, fonte/licença, créditos e elementos faltantes.
6. **Motion e composição:** por necessidade, com intenção, timing e continuidade entre planos. Anime primeiro um trecho representativo; reutilize padrões aprovados.
7. **Cor:** correção técnica por câmera/exposição/balanço, depois look criativo consistente; verifique pele, saturação e telas diferentes. Não aplique LUT como substituto da correção.
8. **Som:** diálogo/ambiente, limpeza, música licenciada, efeitos e mix; preserve inteligibilidade e dinâmica. Alinhe a batidas quando isso apoia o conteúdo.
9. **Export e QC:** preset adequado à plataforma; verifique duração, fps, resolução, aspecto, áudio, clipping, legendas, enquadramento, frames pretos e artefatos. Revise em tela grande e móvel.

## Brief mínimo exportável

```json
{
  "title": "",
  "goal": "",
  "profile": "cinematic | reel | motion-ai | documentary | custom",
  "platform": "",
  "duration_seconds": null,
  "aspect_ratio": "",
  "audience": "",
  "story_beats": [],
  "visual_references": [],
  "assets": [],
  "edit_preferences": {},
  "audio": {},
  "captions": {},
  "export": {},
  "constraints": [],
  "unknowns": []
}
```
