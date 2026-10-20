# Balcão Rápido

Protótipo acadêmico de assistente de balcão farmacêutico com TensorFlow.js e Teachable Machine.

A câmera do celular identifica caixas de medicamentos básicos e a interface aplica regras de negócio: aviso de tarja e receita, alerta de interação e duplicidade, extrato, pagamento com troco e desconto, histórico, estoque simulado e QR code do resumo.

## Como usar

- É uma página estática (`index.html`). Não precisa de build.
- A câmera exige HTTPS. Publique na Vercel ou no GitHub Pages.
- O link do modelo do Teachable Machine está pré-configurado na aba **Ajustes**. Para trocar, cole outro link e toque em **Carregar modelo**.
- Classes do modelo: Dipirona, Paracetamol, Ibuprofeno, Loratadina, Amoxicilina, Clonazepam e Nenhum.

## Aviso

Dados de preço, estoque, interações e regras de receita são fictícios ou simplificados. O projeto é didático e não substitui a bula nem o farmacêutico.
