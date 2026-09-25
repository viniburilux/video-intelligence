# Applied Intelligence

## Infraestrutura experimental de engenharia e P&D aplicada

**Transformamos dados operacionais em inteligência aplicável.**

Applied Intelligence é uma infraestrutura experimental para investigar problemas operacionais e industriais que ainda não têm uma solução tecnológica pronta. O projeto combina engenharia, experimentação e avaliação para transformar uma pergunta real em evidência suficiente para decidir o que vale desenvolver.

```text
Problema → Hipótese → Experimento → Evidência → Decisão → Sistema
```

A pergunta de partida não é qual modelo, framework ou algoritmo usar. É: **qual problema precisa ser resolvido, em qual contexto operacional e com quais dados disponíveis?** A tecnologia é escolhida em função do problema.

## Demonstrated capability: Video Intelligence

Video Intelligence é uma capacidade experimental já construída e demonstrada dentro de Applied Intelligence — não o limite do projeto. A capacidade pública inclui:

- **Detecção:** percepção de objetos com YOLO.
- **Tracking:** manutenção de tracks com ByteTrack.
- **Eventos e métricas:** transformação de observações em dados estruturados.
- **Dwell time e trajetória:** métricas operacionais derivadas do movimento.
- **Embeddings e busca semântica:** CLIP, Qdrant e diagnósticos de `recall@k`.
- **Experimentação e avaliação:** pipelines executáveis, evidências e limites explícitos.

## Evidências públicas

| Experimento | Evidência | Status |
|---|---:|---|
| Flow Intelligence | 62 frames · 55 tracks · 2.377 eventos | Demonstrated |
| Semantic Video Search | 499 objetos indexados · 100% Recall@10 em 3 queries diagnósticas | Demonstrated |

Esses resultados usam footage proxy público. São evidências técnicas e demonstrações de infraestrutura experimental, não benchmark industrial, case comercial ou alegação de performance em qualquer ambiente específico de cliente.

## Modalidades e espaços de aplicação

A abordagem pode explorar vídeo, imagem, documentos, sensores, dados estruturados, séries temporais e linguagem. Essas modalidades representam o horizonte arquitetural de investigação; este repositório não afirma que todas estejam implementadas.

Os espaços possíveis incluem operações, inspeção, segurança, logística, processos industriais, ativos e conhecimento operacional. São possibilidades de investigação, não uma lista de casos realizados.

## Arquitetura conceitual

```text
Problema → Hipótese → Experimento → Evidência → Decisão → Sistema
```

A capacidade de vídeo demonstrada mantém uma cadeia técnica específica:

```text
Video → Detection → Tracking → Events → Representation → Evaluation → Decision
```

Consulte [`docs/architecture.md`](docs/architecture.md) para o desenho, [`docs/experiments.md`](docs/experiments.md) para os experimentos públicos e [`docs/limitations.md`](docs/limitations.md) para os limites conhecidos.

## Reprodutibilidade e licenças

O repositório público contém material explicativo e exemplos sanitizados. Não redistribui pesos de modelos, datasets ou vídeos de terceiros. Dependências e dados externos devem ser obtidos conforme suas respectivas licenças. Revise os termos de Ultralytics, OpenCLIP, Qdrant e de cada dataset antes de qualquer uso comercial.
