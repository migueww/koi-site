# koi-site

O site público do Koi, servido pelo GitHub Pages em https://migueww.github.io/koi-site/.

- `privacidade.html`: a política de privacidade (o app abre este link; a loja pede).
- `rules/detection_rules.json`: as regras de detecção que o app baixa (no máximo a cada 6 h).
- `copy/pt-BR.json`: o banco de falas do koi, baixado do mesmo jeito (vale se a `version` for maior que a do app).

**Não edite aqui.** A fonte é o repositório do app (`docs/privacidade.html`, `docs/rules/` e `docs/copy/`);
publique com `tools/publish_site.sh` de lá.
