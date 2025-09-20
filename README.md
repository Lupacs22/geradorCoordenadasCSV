# 🌍 Conversor de Coordenadas → CSV (ID;LAT;LON)

Este projeto é uma aplicação **HTML + JavaScript** que converte diferentes formatos de coordenadas geográficas para **graus decimais** e gera um arquivo **CSV** no formato:


---

## ✨ Funcionalidades

- Aceita múltiplos formatos de coordenadas:
  - Decimal:  
    `-22.40862, -41.68232`
  - Graus + Minutos (DM):  
    `17 4.433 S, 37 52.9 W`
  - Graus + Minutos + Segundos (DMS):  
    `22 24 31.03 S, 41 40 59.63 W`
  - Com símbolos:  
    `S 22° 26,710’, W 040° 02,303’`
    `24º 41.261’ S; 42º 24.036’ W`
  - Hemisfério antes ou depois (N/S/E/W).
- Linhas em branco são ignoradas automaticamente.
- IDs sempre começam em `1` e são sequenciais.
- Exporta CSV com **separador `;`** e 6 casas decimais.
- Pré-visualização das coordenadas antes do download.

---

## 🖼️ Exemplo de uso

1. Cole coordenadas no campo de texto (uma por linha):
2. Clique em **Pré-visualizar** para validar.
3. Clique em **Baixar CSV** para salvar um arquivo `coordenadas.csv` no formato:

---

## 🚀 Como executar

Basta abrir o link: https://lupacs22.github.io/geradorCoordenadasCSV/ 
