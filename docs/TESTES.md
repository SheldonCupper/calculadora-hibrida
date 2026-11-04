# Plano de testes: calculadora híbrida

## Segurança e interface
- [ ] Inserir no nome de equipamento os caracteres `<`, `>`, aspas e `&`: devem aparecer somente como texto.
- [ ] Testar adição e remoção de equipamentos.
- [ ] Testar quantidades, potência, horas e minutos em limites e entradas vazias.
- [ ] Recalcular ao modificar seleção de bateria e rede.
- [ ] Confirmar o funcionamento da exportação em PDF.
- [ ] Conferir layout em celular e desktop.

## Casos de referência
- [ ] Um equipamento de 100 W, 1 unidade, 2 horas/dia, 7 dias/semana deve resultar em **0,20 kWh/dia**.
- [ ] Dois equipamentos de 100 W por 2 horas/dia devem resultar em **0,40 kWh/dia**.
- [ ] Um equipamento de 100 W por 2 horas, usado 3 dias/semana: média diária aproximadamente **0,0857 kWh/dia**.
- [ ] Entradas negativas, minutos acima de 59 e dias fora de 1 a 7 não devem gerar totais negativos nem infinidade.

## Revisão técnica pendente
- [ ] Confirmar fórmulas de autonomia, profundidade de descarga, fator de correção e capacidade.
- [ ] Separar potência (W) de energia (Wh/kWh) e revisar recomendações de inversores.
- [ ] Validar datasheets de baterias e dimensionamento real com profissional habilitado.
