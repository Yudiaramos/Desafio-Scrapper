# Desafio-Scrapper
Script que faz o scrapping de uma pagina e retira a imagem e sua descrição

# Desafio de Automação de Inferência de Imagem

Este repositório contém um script em Python (ou Jupyter Notebook) que automatiza o processo de:

- Scraping de uma imagem de uma página web;
- Inferência com o modelo `microsoft-florence-2-large`;
- Submissão automática da resposta JSON retornada.

## Explicação do desafio

Neste desafio você deve:

1. **Fazer scraping**  
   - Acesse a URL de scraping e baixe apenas a imagem disponível.

2. **Executar inferência**  
   - Envie a imagem para o endpoint de inferência (`/v1/chat/completions`).  
   - Use o modelo `microsoft-florence-2-large` com prompt `<DETAILED_CAPTION>`.  
   - Autentique-se com o token recebido por e-mail (Bearer token).

3. **Submeter resposta**  
   - Receba o JSON de resposta do modelo (sem alterações).  
   - Envie esse JSON para o endpoint de submissão (`/api/submit-response`) usando o mesmo token.

4. **Enviar script**  
   - Após submissão bem-sucedida via API, atualize a página principal (F5).  
   - Faça upload manual do seu script (`.py` ou `.ipynb`) quando a opção for habilitada.

---

## Passos rápidos

```bash
# 1. Baixar imagem
# 2. Enviar imagem para inferência
# 3. Receber e salvar JSON
# 4. Submeter JSON
# 5. Atualizar página e enviar script

