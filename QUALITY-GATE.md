# Auditoria Final — Rafaella Martins

Data: 06/10/2026

## Método de validação

- Chromium real via Playwright, com viewports emulados de 320, 360, 375, 390, 768, 1024 e 1440 px.
- Não foi alegado teste em aparelho físico.
- Menu mobile, Escape, bloqueio do body, FAQ e ausência de overflow horizontal foram testados.
- Vídeo foi validado separadamente em Chromium: readyState 4, autoplay ativo e botão alternando corretamente entre pausar e retomar.
- Páginas Privacidade, Termos, Obrigado, 404 e Atendimento foram testadas em 390 e 1440 px, sem overflow horizontal e sem erros JavaScript.

## Site Quality Gate — 72 itens

1. **CTA principal na primeira dobra** — **APROVADO**  
   Agendamento é a ação principal do hero.
2. **CTAs claros e consistentes** — **APROVADO**  
   A mesma ação de agendamento é repetida nos pontos principais.
3. **CTA fixo no mobile** — **NÃO APLICÁVEL**  
   Não foi usado para evitar encobrir conteúdo.
4. **Promessa de tempo de resposta** — **NÃO APLICÁVEL**  
   Não existe prazo confirmado.
5. **Página de obrigado** — **NÃO APLICÁVEL**  
   Não há formulário próprio ativo; página preparada para futura integração.
6. **Formulários com validação** — **NÃO APLICÁVEL**  
   Não há formulário próprio ativo.
7. **Links e URLs amigáveis** — **APROVADO**  
   Arquivos locais e âncoras usam nomes claros.
8. **Cases/resultados autorizados** — **NÃO APLICÁVEL**  
   Nenhum case foi inventado.
9. **Avaliações reais e verificáveis** — **NÃO APLICÁVEL**  
   Não foram publicadas avaliações sem fonte textual direta.
10. **Mapas, endereço e rotas** — **APROVADO**  
   Endereço público e link de rota foram incluídos.
11. **Responsividade completa** — **APROVADO**  
   Testes em 320, 360, 375, 390, 768, 1024 e 1440 px sem overflow horizontal.
12. **Meta title único** — **APROVADO**  
   Homepage e páginas auxiliares possuem titles próprios.
13. **Meta description única** — **APROVADO**  
   Homepage possui descrição específica; páginas legais são noindex.
14. **H1 único e hierarquia** — **APROVADO**  
   Estrutura semântica revisada.
15. **Conteúdo sem duplicações desnecessárias** — **APROVADO**  
   Narrativa revisada e específica.
16. **Alt text contextual** — **APROVADO**  
   Imagens de conteúdo possuem texto alternativo.
17. **Breadcrumbs** — **NÃO APLICÁVEL**  
   Estrutura curta/one-page.
18. **FAQ + dados estruturados quando aplicáveis** — **ATENÇÃO**  
   FAQ implementada; schema de FAQ não foi adicionado nesta demo.
19. **URLs amigáveis** — **APROVADO**  
   Slugs e arquivos legíveis.
20. **Canonical tags** — **ATENÇÃO**  
   Dependem do domínio final.
21. **robots.txt** — **APROVADO**  
   Demo bloqueada para indexação.
22. **sitemap.xml** — **ATENÇÃO**  
   Arquivo preparado; URLs finais dependem do domínio.
23. **Página 404 personalizada** — **APROVADO**  
   Página criada e testada.
24. **Favicon** — **APROVADO**  
   Favicon próprio implementado.
25. **Open Graph** — **APROVADO**  
   Metadados de compartilhamento incluídos.
26. **Imagem social** — **APROVADO**  
   Imagem OG própria criada.
27. **Dados estruturados** — **APROVADO**  
   Schema Dietitian incluído.
28. **Search Console** — **ATENÇÃO**  
   Depende do domínio/verificação.
29. **Links quebrados** — **APROVADO**  
   Referências locais verificadas; nenhuma ausente.
30. **Indexabilidade** — **APROVADO**  
   Demo em noindex,nofollow.
31. **Compressão de imagens** — **APROVADO**  
   WebP/JPEG otimizados.
32. **Formatos modernos** — **APROVADO**  
   WebP com fallback JPEG.
33. **Lazy loading** — **APROVADO**  
   Imagem não crítica usa lazy loading.
34. **PageSpeed/Lighthouse** — **ATENÇÃO**  
   Executar na URL publicada; Lighthouse não foi usado nesta sessão.
35. **Core Web Vitals** — **ATENÇÃO**  
   Métricas de campo exigem publicação e tráfego real.
36. **Otimização de fontes/CSS/JS** — **APROVADO**  
   Estrutura leve e sem framework pesado.
37. **HTTPS/SSL** — **ATENÇÃO**  
   Depende da hospedagem final.
38. **Headers de segurança** — **ATENÇÃO**  
   Dependem da infraestrutura final.
39. **Proteção anti-spam** — **NÃO APLICÁVEL**  
   Sem formulário próprio.
40. **Tratamento seguro de dados** — **APROVADO**  
   Demo não coleta dados diretamente.
41. **Política de Privacidade** — **APROVADO**  
   Página criada; deve ser revisada conforme stack final.
42. **Cookies/consentimento** — **NÃO APLICÁVEL**  
   Sem analytics/pixels opcionais ativos na demo.
43. **Dados profissionais no rodapé** — **APROVADO**  
   Nome, registro e localização profissional incluídos.
44. **Analytics** — **ATENÇÃO**  
   Não ativado sem ID real.
45. **Eventos de conversão** — **ATENÇÃO**  
   Hooks preparados; falta plataforma real.
46. **Cliques em WhatsApp monitoráveis** — **NÃO APLICÁVEL**  
   WhatsApp não foi confirmado e não foi inventado.
47. **Envios de formulário monitoráveis** — **NÃO APLICÁVEL**  
   Sem formulário próprio.
48. **Origem/campanha preservada** — **ATENÇÃO**  
   Sem backend/CRM nesta demo.
49. **LeadPilot CRM** — **ATENÇÃO**  
   Integração não conectada.
50. **Teste real de eventos** — **ATENÇÃO**  
   Requer analytics/CRM real.
51. **Logo e identidade visual** — **APROVADO**  
   Wordmark RM e paleta bordô/creme/dourado coerentes com a identidade observada.
52. **Informações reais do negócio** — **APROVADO**  
   Conteúdo factual cruzado entre Instagram, LinkedIn e Doctoralia.
53. **Telefone/WhatsApp conferidos** — **NÃO APLICÁVEL**  
   Nenhum número foi confirmado; o site usa Linktree/Instagram.
54. **Endereço e horários conferidos** — **ATENÇÃO**  
   Endereço confirmado; horários não foram publicados por falta de fonte segura.
55. **Serviços/especialidades conferidos** — **APROVADO**  
   Nutrição esportiva e clínica confirmadas.
56. **Fotos reais autorizadas** — **ATENÇÃO**  
   Retrato é reconstrução/melhoria baseada no print enviado; recomenda-se substituir por arquivo original na produção.
57. **Informações da profissional conferidas** — **APROVADO**  
   Formação e atuação cruzadas com fontes públicas.
58. **Avaliações reais sem fabricação por IA** — **APROVADO**  
   Nenhuma avaliação fictícia foi criada.
59. **Conteúdo adaptado ao segmento/local** — **APROVADO**  
   Copy específica para nutrição esportiva/clínica no Rio.
60. **Revisão de conteúdo regulamentado** — **ATENÇÃO**  
   Revisão final pela nutricionista recomendada antes da produção.
61. **Teste desktop** — **APROVADO**  
   Chromium emulado em 1024 e 1440 px.
62. **Teste mobile** — **APROVADO**  
   Chromium emulado em 320, 360, 375, 390 e 768 px.
63. **Teste de formulários** — **NÃO APLICÁVEL**  
   Sem formulário próprio.
64. **Teste de CTAs** — **APROVADO**  
   Destinos estruturais revisados.
65. **Teste de links externos** — **ATENÇÃO**  
   URLs verificadas estruturalmente; navegação externa completa depende da rede/serviço.
66. **Teste de WhatsApp, telefone e e-mail** — **NÃO APLICÁVEL**  
   Esses canais não foram confirmados.
67. **Auditoria SEO** — **ATENÇÃO**  
   Estrutura revisada; domínio/canonical/sitemap final pendentes.
68. **Auditoria de acessibilidade básica** — **APROVADO**  
   Foco visível, teclado, Escape, semântica e reduced motion testados.
69. **Auditoria de performance** — **ATENÇÃO**  
   Assets otimizados; Lighthouse em URL publicada ainda pendente.
70. **Auditoria de segurança** — **ATENÇÃO**  
   Front-end sem segredos; headers/HTTPS dependem da hospedagem.
71. **Verificação domínio/SSL** — **ATENÇÃO**  
   Domínio final ainda não informado.
72. **Site Quality Score final** — **APROVADO**  
   Calculado com base nos itens aplicáveis.

## Totais
- Aprovados: **37**
- Atenção: **21**
- Falhou: **0**
- Não aplicável: **14**
- Itens aplicáveis: **58**
- Site Quality Score: **81.9%**

## Status
**PRONTO PARA DEMONSTRAÇÃO**

**NÃO READY FOR PRODUCTION**

## Bloqueadores para READY FOR PRODUCTION
1. Definir domínio final e atualizar canonical/sitemap.
2. Publicar em HTTPS e validar SSL.
3. Executar Lighthouse desktop/mobile na URL publicada.
4. Configurar Search Console.
5. Conectar analytics/CRM apenas se forem realmente usados e testar eventos reais.
6. Substituir o retrato reconstruído por arquivo original da cliente, se disponível.
7. Revisão profissional/regulatória final pela nutricionista.