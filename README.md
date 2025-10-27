# CupcakeOnline — Sistema de Vendas de Cupcakes Gourmet

**Projeto Integrador — Engenharia de Software II (PIT II)**

Este repositório documenta a entrega do projeto *CupcakeOnline*, implementado com **WordPress + WooCommerce** (abordagem *low-code/no-code*), seguindo o padrão arquitetural **MVC** conforme diretrizes do PIT II.

## 🔗 Link público do sistema
- URL: https://mrronyx.tech/

## 🧱 Arquitetura (MVC — mapeamento prático)
- **Model**: Tabelas MySQL gerenciadas pelo WordPress/WooCommerce para **produtos**, **usuários** e **pedidos**.
- **View**: Páginas e componentes construídos com o editor de blocos (Gutenberg) e templates do tema.
- **Controller**: Regras de fluxo de compra/autenticação/checkout providas pelo plugin WooCommerce (hooks, endpoints e actions).
  
## ✅ Funcionalidades implementadas (mapeadas às HUs)
- HU001/HU002 — **Cadastro/Login** via página *Minha Conta* (WooCommerce).
- HU003 — **Vitrine** de produtos (página Loja).
- HU004 — **Detalhe** do produto.
- HU005/HU006/HU007/HU008 — **Carrinho**: adicionar, visualizar, alterar quantidades e remover itens.
- HU009/HU010/HU011 — **Checkout**: endereço, seleção de pagamento (fictício) e confirmação de pedido.
- HU012 — **Acompanhamento de status** do pedido pelo cliente.
- HU013/HU014 — **Admin**: listagem e atualização de status de pedidos.
- HU015 — **Admin**: cadastro/edição de produtos.

## 🧪 Testes (verificação/validação)
Evidências visuais em `screenshots/`:
- fluxo completo do usuário (vitrine → carrinho → checkout → pedido concluído);
- acesso e cadastro;
- painel administrativo com pedidos.

## 🖼️ Screenshots
Consulte `SCREENSHOTS.md` para a lista de capturas e nomes de arquivos padronizados.

## 📄 Documentação complementar
- `feedback_form.md` — template para coleta dos 5 testes de usuários (Situação 3).
- `shotlist.csv` — planilha com a lista de capturas necessárias e mapeamento HU.

## 🛠️ Stack técnica
- WordPress (hospedado em nuvem) + WooCommerce
- Tema: (preencher)
- Plugins principais: WooCommerce (+ opcionais)

## 📚 Referência ao material do PIT II
O uso de *low-code/no-code* é recomendado pelo material oficial do PIT II, justificando a adoção de WordPress/WooCommerce para acelerar a entrega e focar em UX, testes e validação.

---
**Autor:** 
Rony Abdul
Estudante de Engenharia de Software
