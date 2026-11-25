# Como usar a MdEditor

## Instalar e iniciar

Em um agente compatível com Agent Skills, instale a skill pelo terminal:

```bash
npx skills add maisterdev/mdeditor --skill editar
```

Para disponibilizá-la globalmente no Codex:

```bash
npx skills add maisterdev/mdeditor --skill editar -g -a codex
```

Depois, invoque `/editar` na conversa. O suporte a instalação automática e a comandos slash depende do agente. Para um chat sem esse suporte, gere as instruções com `npx skills use maisterdev/mdeditor@editar` ou anexe o `SKILL.md` e as referências incluídas no projeto; então descreva seu objetivo e envie `/editar` no pedido.

## Editar um vlog ou outro vídeo gravado

1. Anexe o vídeo original à conversa com a IA que vai trabalhar nele. Inclua outros ângulos, áudio separado, imagens e referências relevantes.
2. Invoque `/editar` e escolha **Editar meus vídeos**. Esse caminho usa as gravações como fonte da história; animação, gráficos e efeitos não entram por padrão.
3. No configurador, selecione o vídeo se quiser conferir uma prévia local e indicar os arquivos no briefing. O site não envia o vídeo à IA.
4. Explique o contexto: onde foi, o que aconteceu, quais momentos importam e o que deve ser evitado. Escolha a direção visual; um preset cinematográfico esportivo está disponível como opção, não como regra.
5. Configure ritmo, cor, som, legendas, formato e restrições. Se ainda não tiver uma preferência, deixe a IA recomendar depois de analisar os arquivos anexados.
6. Revise o resumo, exporte o brief e envie-o à mesma conversa que contém os vídeos. Peça uma proposta de montagem com timecodes; renderize somente com ferramentas de edição disponíveis.
7. Revise o primeiro corte e peça alterações concretas, como “preserve mais o som ambiente”, “encurte a ida” ou “deixe o final respirar”.

## Criar motion ou animação

1. Invoque `/editar` e escolha **Criar motion ou animação**.
2. Explique a ideia, a mensagem e o público. Se ainda não houver roteiro, peça uma proposta.
3. Anexe logos, imagens e referências à conversa com a IA. O configurador pode mostrar arquivos localmente, mas não os transfere.
4. Escolha a linguagem, por exemplo motion gráfico, colagem, animação de personagem, tipografia ou realismo cinematográfico. Defina ritmo, cor, movimento, som e duração.
5. Exporte o brief e envie-o junto dos assets. Peça primeiro roteiro visual e storyboard; depois, peça geração e montagem se houver ferramentas adequadas.

## Transformar um vídeo em Reel ou Short

1. Anexe o vídeo original e invoque `/editar`.
2. Escolha **Transformar em Reel** e informe mensagem, público e duração.
3. Defina proporção vertical, ritmo, legendas, música e chamada final. Preserve o contexto e evite recortes que mudem o sentido.
4. Exporte o brief e peça uma seleção de momentos com timecodes antes de montar a versão vertical.

## O que cada parte faz

- **Skill `/editar`:** orienta o trabalho, analisa os arquivos acessíveis e planeja ou edita quando o agente tem ferramentas de vídeo compatíveis.
- **Configurador:** organiza escolhas, mostra uma prévia ilustrativa e exporta brief e prompt. Funciona no navegador e não renderiza vídeo.
- **Arquivos anexados à IA:** dão ao agente acesso ao vídeo bruto. Selecionar um arquivo apenas no configurador não permite que a IA o analise.

## Navegar no configurador

- Escolha um dos três fluxos no início.
- Responda uma etapa de cada vez. Use **Continuar** e **Voltar** para avançar ou corrigir decisões.
- A coluna lateral acompanha a prévia e o resumo. Um vídeo selecionado pode ser reproduzido localmente no navegador.
- A animação de direção é uma referência ilustrativa, não uma edição do vídeo.
- Na etapa final, revise o pedido e confirme antes de exportar.
- O site mantém as respostas de texto neste navegador. Os vídeos não são enviados nem guardados no briefing; mantenha-os anexados à conversa com a IA.

Se o agente não puder renderizar, peça um mapa de cortes com timecodes, decisões de áudio e cor, storyboard e instruções para o editor disponível. A MdEditor só declara que um vídeo foi editado quando um render final está realmente acessível para revisão.
