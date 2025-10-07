# Processador Mínimo Viável

CPU educacional de 8 bits construída no simulador Digital.

## Componentes

### Blocos Básicos
- `half-adder.dig` - Somador básico 1-bit
- `full-adder.dig` - Somador 1-bit com carry

### Operações 8-bit
- `adder-8bit.dig` - Adição 8 bits
- `subtractor-8bit.dig` - Subtração 8 bits
- `incrementor-8bit.dig` - A + 1
- `decrementor-8bit.dig` - A - 1

### Operações 4×4
- `multiplier-4x4.dig` - Multiplicação 4 bits
- `divisor-4x4.dig` - Divisão 4 bits (algoritmo restoring)
  - `adder-5bit.dig` - Componente auxiliar
  - `subtractor-5bit.dig` - Componente auxiliar
  - `divide-step.dig` - Componente auxiliar

### Componentes de Sistema
- `alu-8bit.dig` - ALU completa com 6 operações (opcode 3 bits)
- `register-8bit.dig` - Registrador 8 bits com enable
- `pc.dig` - Program Counter com auto-incremento, jump e reset

## Status

✅ ALU completa (6 operações)
✅ Registrador básico
✅ Program Counter
⏳ Unidade de controle (próximo)

