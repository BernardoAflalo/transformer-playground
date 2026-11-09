# Transformer, peça por peça

Playground interativo e didático da arquitetura **Transformer**, seguindo o artigo
[*Attention Is All You Need*](https://arxiv.org/abs/1706.03762) (Vaswani et al., 2017).

**Acesse:** https://bernardoaflalo.github.io/transformer-playground/

## O que tem

18 passos que acompanham, com números reais, todas as transformações aplicadas ao embedding de cada token:

1. Visão geral · 2. Tokenização · 3. Embedding (× √d_model) · 4. Codificação posicional
5. Q, K, V · 6. Scaled dot-product attention · 7. Multi-head · 8. Add & Norm · 9. Feed-forward · 10. Pilha do encoder
11. Entrada do decoder (shifted right) · 12. Masked self-attention · 13. Cross-attention
14. Linear + Softmax · 15. Treinamento (loss, label smoothing, warmup) · 16. Geração token a token
17. A jornada de um token · 18. Teste rápido

O modelo é uma miniatura (d_model = 8, 2 cabeças, 2 camadas) com **pesos aleatórios**: ele não foi treinado,
mas executa exatamente as operações do paper, para que os alunos vejam formatos e cálculos de cada etapa.

Arquivo único (`index.html`), sem build. Fórmulas renderizadas com KaTeX.

Série: Transformer · [BERT](https://bernardoaflalo.github.io/bert-playground/) · [GPT](https://bernardoaflalo.github.io/gpt-playground/)
