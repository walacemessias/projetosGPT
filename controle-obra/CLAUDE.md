# Controle da Obra

## Objetivo
Sistema estático em HTML/CSS/JS para controlar os gastos da obra da casa.

## Regras do projeto
- Manter o projeto sem backend enquanto não houver pedido explícito para sincronizar dados entre dispositivos.
- Persistência local via `localStorage`.
- As notas começam com 15% de desconto, mas o percentual pode ser alterado por pedido ou em massa.
- Itens repetidos devem ser agrupados por código + descrição + unidade, somando quantidades.
- Itens e gastos extras podem ser excluídos/restaurados pelo usuário.
- O pedido 4705266 possui duas fotos, mas deve ser contabilizado apenas uma vez.
- Gastos extras iniciais: Pedreiro R$ 3.565,00; Servente R$ 1.425,00; Areia R$ 60,00; Lixa 100 R$ 30,00; Pedra para o muro acima do portão R$ 310,00.

## Hospedagem
Este projeto fica em `walacemessias/projetosGPT`, pasta `controle-obra/`, pensado para GitHub Pages.

## Manutenção
A cada ajuste relevante, atualizar este arquivo e subir a alteração ao GitHub.
