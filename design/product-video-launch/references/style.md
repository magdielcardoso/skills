# Reference: launch-film visual grammar

Source: https://x.com/SpaceXSI/status/2120584928983441826 — Grok Bot 1.0. Analyzed from the 1280×720, 30 fps, approximately 79.15 s copy. The shot chronology below was visually sampled at one-second intervals. It is an approximate editorial map, not a frame-accurate motion trace; measure consecutive frames before making precise timing claims. The reference contains people, logos, interface marks and music belonging to others; replace these with the product's own authorized materials.

## Visual observations

- Predominantly pure white backgrounds, near-black simple sans-serif type and substantial negative space. Feature labels appear alone, small relative to the canvas, often centered. Occasional very pale blue, violet or peach fields contextualize a scene.
- Product UI is the hero: rounded white floating voice/chat panels with soft, diffuse shadows, small icons and colored message bubbles; close-ups are often so tight that the UI extends beyond frame edges. Small colored mascot-like marks and pointers identify agents/actions. Use the product's own visual vocabulary instead of copying reference marks.
- Transitions alternate between isolated feature cards and live-looking action: a voice panel expands, messages appear, a cursor interacts, a conference grid and a chart come into view, and the camera travels into a message or design surface. Some graphics are deliberately oversized and cropped; typography and transitions stay restrained.
- A digital-work story unfolds across meeting, chat, charts, design, presentations and reactions. The finale resolves from a reaction/character and a short statement into a simple centered product lockup. Use only analogous situations substantiated by the new product.

## Approximate shot map (seconds)

| Time | Observed material |
| --- | --- |
| 0–4 | Introduction, colorful agent symbols, purple close-up and notification |
| 4–7 | Sparse centered introduction, then small floating voice UI |
| 7–13 | Pale blue field, oversized feature title, voice/chat panel and admission action |
| 13–20 | Meeting grid and blue agent; quiet centered feature card |
| 20–32 | Conversation, enlarged chart and animated pointer, messages and reaction; next feature title |
| 32–44 | Collaborative chat and design-tool interface, pointer selects and edits headline; campaign imagery |
| 44–59 | Peach voice panel, deck/financial slide close-up, message exchange |
| 59–68 | Response, announcement, campaign images and reaction count |
| 68–79 | Large reaction mark, centered closing line, colored marks, final black logo lockup |

## Construction recipes (starting points, not measurements)

- Canvas: 1920×1080 / 30 fps; use white as default. Preserve generous empty space. Make type near-black and use the product's licensed font, otherwise a neutral sans-serif. Use brand colors sparingly for a single active object or panel background.
- Title beat: a single concise line centered with a calm hold, then a clean cut or subtle scale/position change to a UI detail. Build readable text at actual output size, rather than shrinking a web layout.
- UI beat: float a cropped, rounded panel over a nearly white tinted field. Start with a compact bar, smoothly expand into a card, stagger a cursor or waveform and reveal one message at a time. Soft low-opacity shadow; no heavy outlines. For a cursor, animate position and a brief click scale; ensure that its target and resulting state are legible.
- Camera: animate a parent viewport transform to push into a relevant UI region, hold for comprehension, then cut to a distinct context. Mix medium framing and extreme crops; avoid continuous random drifting. Keep UI internally stable during a move. Use short, gentle ease-in/out curves and reserve hard cuts for scene changes.
- Data/design beat: show one meaningful chart, selection or document detail, then animate a pointer and resulting change. Draw curves and highlights as independent, editable layers. Preserve labels and source values from the real product.
- Ending: remove interface clutter, hold a short product-specific closing line, then resolve to the actual logo and name on white. Keep the end card long enough to read.
- Sound: if available, use a suitable licensed Pixabay music bed with subtle click, pop or transition accents synchronized to actions. The reference audio was not separately analyzed; do not infer its exact instrumentation or reuse it.

## Measurement for higher fidelity

If the source file is available, probe fps/duration with ffprobe; find cuts and inspect consecutive frames around each entrance, exit, camera move, message and cut. Log frame numbers and positions, scale, opacity, crop, color and layer order; infer easing from measured positions. Validate with aligned renders and visual differences. A contact sheet alone cannot establish exact easing, one-frame cuts or audio synchronization. Different product UI, assets and copy prevent a meaningful pixel-identical match; report the differences.

## Motion observations from closer 4–6 fps sampling

- Around 7–10 s, a compact white control bar assembles in stages, followed by a hard cut to oversized blue text sweeping across a tinted background; the letters crop at both edges. This is a change of scale and scene, not a generic fade.
- Around 10–13 s, a small message arrives inside an expanding panel; the cut jumps directly to an extreme close-up of an admission button and cursor. A subsequent cut reveals the meeting grid. Each view shows an action and its consequence.
- Around 28–34 s, a message is enlarged until its text exits the frame; a reaction appears over it. The next centered title resets the visual scale, followed by an incremental message exchange and reaction.
- Around 44–59 s, the voice bar expands, a message appears, and a hard cut reveals an oversized document. A pointer moves along its graph, before returning to the voice panel and a response. Maintain visual continuity through color, subject and action, not identical framing.
- Production bar: choreograph a cause and effect in every UI sequence, use deliberate extreme crops and asymmetric jumps in scale, animate messages and controls independently, and include a licensed or original sound bed and synced accents when available. Reject a long sequence of static cards or a single screenshot with a slow zoom. Render, watch and revise at least once against the reference; log actual differences and do not claim exact fidelity without frame-level comparison.

## Timing reference: Google Labs Tabletop

Reference: https://x.com/GoogleLabs/status/2120549258692882702/video/1 (66.6 s, 24000/1001 fps). Inspected contact sheets sampled at 0.5 s; the values below are production starting points, not frame-exact measurements. The film progressively builds text, panels and cursor labels; cards expand into context and related visual elements persist while the next state assembles. Several shots hold for roughly 1–2 s while smaller items continue changing. Avoid treating every edit as a 0.1 s flash.

For similar work, budget approximately 0.5–0.9 s for a scene passage and 0.5–0.8 s for primary elements to settle, with ease-in-out or a gentle ease-out and no strong overshoot. Stagger subordinate elements approximately 0.1–0.2 s and allow the viewer a readable hold after they settle. Add restrained secondary motion tied to state: a cursor settles before activation, status chips pulse subtly, avatars or icons shift slightly, and a panel grows from its originating control. Vary these values with content and validate at native frame rate; do not claim an exact keyframe curve without measuring consecutive frames.

## Primary reference and user art direction

Primary reference: https://x.com/benjitaylor/status/2120590804695589251 — the same 79.15-second Grok Bot launch film as the earlier SpaceXSI post (matching scenes and duration), not a different film. Inspected contact sheets at 2 frames per second; this does not establish frame-exact easing. Its actual imagery mixes flat colored agent marks, pale backgrounds, UI, real video calls and photos. Per user direction, interpret the motion language as colorful 2D flat graphics: bold but brand-derived color fields, graphic shapes, simplified editable interface elements, and frequent purposeful microanimation. Do not misrepresent the reference as wholly flat animation.

Animate components individually: stagger a compact control bar and message expansion; overscale and crop a sentence or product detail to bridge scenes; move pointers to an actionable target, show the resulting state, and use a reaction to transition into the next context. Use eased starts and stops with deliberately stronger acceleration on selected transitions, then readable holds; vary scale, direction, density and background at each beat. Flat shapes may enter or exit as motivated transitions; avoid continuous drifting or motion for its own sake. Fit cuts to the selected licensed music while allowing a coherent visual action to complete. Preserve the product's actual logo, palette, type and factual features. Inspect consecutive frames around each cut before claiming precise timing.

For a circle wipe, position the circle fully outside the canvas before its entrance, then animate both its center and radius so its edge visibly travels across the frame. Keep it on a global transition layer spanning both scenes, calculate a radius large enough to cover the farthest corner before changing scenes, and match the circle color to the incoming background. Review consecutive frames from before entry through full coverage and reveal; a circle that grows in place and cuts away before coverage is not a completed transition.

## Revisão de quadros consecutivos — controles de voz

A cópia Benji disponível tem 2.373 quadros a 30 fps (79,1 s). Na inspeção de quadros consecutivos do trecho de aproximadamente 10–13,3 s, o painel permanece ancorado enquanto a bolha azul aparece e o indicador de voz muda de forma independentemente; a resposta textual se acrescenta no interior sem deslocamento global do canvas. Em seguida ocorre um corte direto para um recorte ampliado do controle de admissão, com o ponteiro sobre o botão. A diferença é estrutural: microanimação interna e montagem de conteúdo enquanto a câmera fica estável, seguida de uma mudança de enquadramento discreta e abrupta, não zoom contínuo. As folhas integrais foram geradas a 30 fps; esta observação não equivale a uma inspeção minuciosa de todos os 2.373 quadros.

### Recorte ampliado do indicador de voz

Na sequência examinada em quadros consecutivos, o indicador é uma fileira de pontos arredondados azuis: as marcas centrais alongam-se verticalmente em barras com alturas distintas, enquanto pontos laterais permanecem pequenos. A amplitude diminui até voltar à linha de pontos em alguns quadros. O ícone, a engrenagem e a bolha permanecem em suas posições; o movimento é local e não um pulso de escala de todo o componente. Implemente cada barra como camada independente com extremidades arredondadas, alturas escalonadas e retorno à linha de base. O recorte foi feito na fonte disponível, sem recuperar detalhes inexistentes na resolução original.

## Revisão em 1080p: construção de mensagens

A variante pública disponível em 1920×1080 e 30 fps permite verificar melhor ícones e tipografia que na cópia de 720p. Na sequência de colaboração observada aproximadamente aos 32–38 s, a composição começa com título isolado; a mensagem é construída progressivamente com avatar, nome, menção e corpo, preservando essas camadas quando a segunda resposta aparece. Uma reação pequena é acrescentada à mensagem; a cena seguinte usa um conjunto de avatares. Preserve os estados anteriores ao acrescentar novos elementos e dê tempo para a leitura, em vez de animar todas as camadas como um bloco único. Observação baseada em painel de visão geral a 2 fps: essa sequência ainda precisa de inspeção em quadros consecutivos para determinar timings finos e easing.
