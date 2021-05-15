![Ecoluz Logo](images/ecoluz-logo.png)

# EcoLuz

EcoLuz é um projeto desenvolvido pelos integrantes da Guilda Maker com objetivo de evitar o desperdício de energia de dispositivos elétricos e eletrônicos, emitindo avisos sonoros de uso e podendo ser controlado por infravermelho e/ou wi-fi. Além disso, um relatório de tempo de uso e consumo pode ser consultado no webapp, bem como customizar seu funcionamento.


**TODO List:**
- [x] Criar documentação inicial
- [ ] Elaborar esquema do circuito 
- [ ] Codificar funcionamento básico (aviso sonoro, desativação, infravermelho)
- [ ] Construir uma POC na protoboard e testar
- [ ] Criar interface web embarcada no dispositivo
- [ ] Desenvolver PCB
- [ ] Modelar case para impressão 3d

---

**Requisitos funcionais:**
- Emitir um aviso sonoro após um tempo de uso
- Deve possuir um receptor infravermelho que funcione com qualquer controle remoto, permitindo ligar e desligar o dispositivo controlado
- Configurações na interface web
  - Hora inicial e final de atuação
  - Tempo do aviso sonoro
  - Customização do infravermelho
- Relatório com estatísticas de uso na interface web
  - Permitir inserir o consumo do dispositivo controlado, assim será possível calcular o consumo em watt/hora
  - Exibir o tempo que o dispositivo ficou ligado
  - Quantas vezes o aviso sonoro foi acionado


**Requisitos não-funcionais:**
- Usar o microcontrolador ESP-01
- Usar um led RGB WS2812 para fornecer status do dispositivo
- Externalizar os IOs do MCU para extensão
- Deve caber dentro de uma tomada na parede


