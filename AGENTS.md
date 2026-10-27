# CONSECOM PREVIEW — AGENTS.md

## Missão
Vitrine exclusiva dos sites da Consecom Brasil. O usuário solicita criação/alterações pelo ChatGPT. A aplicação NÃO pode ter sidebar, formulário de Instagram, gerador automático, área de ferramentas ou telas de gestão fictícias.

## Padrão obrigatório de cada site entregue
- Pesquisar a empresa, analisar marca, serviços, público, mídias reais e diferenciais; não inventar provas sociais, números, contatos ou fotos atribuídas ao cliente.
- Projetar o site com identidade original, intenção editorial, narrativa comercial e composição visual personalizada. É proibida aparência genérica de “AI slop”: evitar gradientes gratuitos, muitas ilhas/cartões, microetiquetas repetidas, divisórias desnecessárias, ícones aleatórios e textos vagos.
- Entregar o site COMPLETO, não apenas hero: navegação, conteúdo coerente, serviços, diferenciais reais, contatos, CTAs, rodapé e SEO. Seções devem ser selecionadas conforme o negócio, jamais copiadas mecanicamente.
- Priorizar tipografia refinada, fotografia pertinente, espaçamento, hierarquia e interação de alta qualidade. Animações suaves e funcionais, respeitando prefers-reduced-motion.
- Responsividade verificada em 360px, 390px, 768px, 1280px e 1920px. Nenhuma sobreposição, corte de textos, scroll horizontal ou links sem destino.
- Acessibilidade: HTML semântico, headings estruturados, alt, foco visível e teclado, contraste. SEO: title/description apropriados, imagens otimizadas, performance.
- Ciclo obrigatório: planejar → implementar → executar/build → revisar no navegador desktop e mobile → corrigir → repetir. Nunca afirmar que testou algo não testado, nem chamar defeitos restantes de “perfeito”.
- Cada cliente isolado em `sites/<slug>/` com HTML/CSS/JS/imagens exportáveis, sem dependências remotas essenciais para export offline. Não sobrescrever outras entregas.

## Contrato de publicação
1. Criar `sites/<slug>/index.html` e assets, validando navegação e responsividade.
2. Produzir capturas reais desktop e mobile em PNG e ZIP funcional para exportação offline.
3. Adicionar registro ao `projects.json`: `slug`, `name`, `category`, `description`, `url`, `thumbnail`, `desktopPng`, `mobilePng`, `htmlZip`.
4. Campos de artefatos ainda ausentes devem ficar vazios, não apontar para arquivos fictícios.
5. Verificar URLs, downloads, cards, filtros, busca, publicação e regressão dos sites existentes.
6. Alterações somente após aprovação quando envolverem exclusão ou troca de projetos existentes.

## Critério de aceite
O projeto só está finalizado com arquivos íntegros, links verificados, capturas reais, versão mobile revisada e deploy comprovado. Preferir transparência sobre pendências.

## Diferencial obrigatório por cliente
- Cada site deve ter no mínimo UMA funcionalidade ou experiência diferenciadora, desenhada para a dor real daquele nicho; não basta mudar cor, imagem ou animação.
- O diferencial deve ser plenamente funcional e testado, não uma maquete inerte. Exemplos: configurador/briefing de orçamento, comparador pertinente, filtro inteligente de catálogo, consulta guiada, simulador apenas com critérios validados.
- Não criar preços, orçamentos automáticos, avaliações, números, obras ou depoimentos não verificados. Funcionalidades interativas devem esclarecer quando são ilustrativas.
- Preservar a identidade e as imagens fornecidas pelo cliente. Em restauração de imagem com texto, priorizar upscaling conservador e fidelidade em vez de inventar letras ou detalhes.
