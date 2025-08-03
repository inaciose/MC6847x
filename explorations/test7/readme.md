Testes do MC6847 - Circuito de teste 7 
S-video
Exibe os vários caracteres em ROM, em modo normal ou invertido, e também os semi gráficos.
Usa o MC1372, sem usar a saida de RF (pin 12), para:
- gerar o sinal de crominancia do s-video (pin 4), a partir da crominancia do MC1372 (pin 8), e
- gerar a luminancia do s-video com base no MC1372 (pin 9) e MC6847 (pin 28) 

Experimentei o circuito de svideo do pmig96

https://pmig96.wordpress.com/2022/04/07/mc6847-test-circuit-part-7/


Funcionou. 

No entanto tive muitas duvidas em colocar o sinal no monitor, pois as tensões na saida Y e C do circuito excedem muito os valores de referencia que vi na web (que nunca ultrapassavam 1V).
Por isso fiz divisores de tensão para colocar os valores maximos dentros dos limites. Experimentei e a imagem estava muito má.
Fui experimentando trocar brevemente o Y para o valor do circuito sem divisor, e a imagem melhorou ligeiramente. Se seguida coloquei o C também antes do divisor, e a imagem melhorou bastante. Ainda assim a imagem nãoé boa. 

Fiquei por aqui.
