# Sistema de Barbearia

# Introdução

Uma barbearia está precisando de um sistema para organizar seu processo. Desta forma, faz-se necessário o cadastro de clientes, dos funcionários, dos procedimentos que são realizados por cada funcionário e o agendamento dos serviços que o cliente gostaria de realizar. No final, associar o pagamento, obtido com o total dos gastos dos procedimentos, com o agendamento realizado.

# Módulos

- *Clientes*: Um módulo para registrar clientes, com dados como nome, e-mail e telefone.

- *Funcionários*: Um módulo para gerenciar os funcionários, com informações como nome, cargo e uma breve descrição.

- *Procedimentos*: Um módulo para definir os procedimentos disponíveis na barbearia, como corte de cabelo usando máquina, corte de cabelo usando tesoura e aparar a barba. O dono da barbearia deverá informar o percentual que ele cobrará do profissional pelo procedimento.
  
- *Procedimentos do profissional*: Módulo utilizado para associar os procedimentos disponíveis aos funcionários. Cada procedimento pode ser realizado por um ou mais profissionais e contém um preço e uma duração estimada definido pelo funcionário que realiza o serviço.

- *Agendamento de Serviços*: O cliente seleciona os procedimentos desejados, o profissional e o sistema verifica a disponibilidade dos funcionários para confirmar o agendamento. Uma vez confirmado, deverá ser informado o valor total previsto para o agendamento.

- *Pagamento*: Após o agendamento e execução dos serviços, o módulo de pagamento calcula o total dos procedimentos realizados e associa o valor ao agendamento para finalizar a transação.
