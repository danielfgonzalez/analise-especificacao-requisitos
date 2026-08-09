# Regras de Negócio (RN) — Sistema de Gestão de Eventos

As regras de negócio definem restrições e condições que orientam o funcionamento do sistema.

| ID | Regra de Negócio | Relacionada a | Status |
|----|------------------|---------------|--------|
| RN01 | O cancelamento de inscrição só é permitido se o evento estiver configurado pelo organizador como "permite cancelamento". | RF04, RF09 | Confirmada |
| RN02 | Existe um prazo limite para cancelamento da inscrição. Após esse prazo, o participante não poderá cancelar sua inscrição. | RF04 | Parâmetro em aberto |
| RN03 | O direito a reembolso depende das regras definidas pela organização do evento. | RF15 | Parâmetro em aberto |
| RN04 | Em eventos pagos, a inscrição somente será confirmada após a confirmação do pagamento. | RF13, RF14 | Confirmada |
| RN05 | Em eventos gratuitos não existe necessidade de validação de pagamento. | RF12 | Confirmada |
| RN06 | O controle da reserva de vagas durante o pagamento ainda necessita definição. | RF07, RF13 | Parâmetro em aberto |
| RN07 | Quando o limite de vagas for atingido, novos participantes devem ser direcionados para a lista de espera. | RF08 | Confirmada |
| RN08 | Um participante não pode possuir inscrições em atividades com horários conflitantes. | RF06, RF11 | Confirmada |
| RN09 | Workshops realizados simultaneamente exigem que o participante escolha apenas uma atividade por horário. | RF06, RF11 | Confirmada |
| RN10 | A emissão de certificados somente poderá ocorrer após a realização do evento. | RF05 | Confirmada |
| RN11 | O palestrante poderá visualizar apenas os participantes das atividades que ministra. | RF16 | Confirmada |
