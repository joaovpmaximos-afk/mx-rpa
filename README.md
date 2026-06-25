# MX RPA — Sistema de Recibo de Pagamento a Autônomo

App web (HTML único) da **MÁXIMOS Soluções Empresariais**.

- O **cliente** entra, cadastra os autônomos e lança o mês (dia trabalhado + valor).
- O **escritório** entra, vê tudo e exporta a planilha `.xlsx` (16 colunas, idêntica à do cliente).

Backend: **Supabase** (Postgres + Auth + RLS). Publicado via **GitHub Pages** (deploy automático a cada push).

> Modo demonstração: abra o site com `?demo=1` para testar a interface sem login (dados só no navegador).
