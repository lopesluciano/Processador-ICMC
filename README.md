# Novas Funcionalidades do Processador ICMC

**Link do vídeo de apresentação**: [Clique Aqui!](https://drive.google.com/file/d/19HXNUUkNI4NPgB30n9Sc1M5647xieVC4/view?usp=drive_link)

## Autores
- Leonardo Gueno Rissetto (13676482)
- Lucas Lima Romero (13676325)
- Luciano Gonçalves Lopes Filho (13676520)
- Thiago Kashivagui Gonçalves (13676579)
  
## Professor
- Eduardo do Valle Simões

# Processador da Universidade de São Paulo - São Carlos

Este repositório contém implementações relacionadas ao processador desenvolvido como parte da disciplina "Organização e Arquitetura de Computadores" na Universidade de São Paulo - São Carlos.

## Novas Funcionalidades

### Instrução XNOR

#### Descrição

Para melhorar as capacidades do processador, uma nova instrução, XNOR, foi adicionada. A instrução XNOR realiza uma operação lógica "ou exclusivo negado" (XNOR) entre dois registradores e armazena o resultado em um terceiro registrador.

#### Implementação

A implementação da instrução XNOR foi realizada no arquivo `montador.c`. Aqui está uma visão geral da lógica implementada:

1. **Obtenção dos Registradores:**
   - São obtidos os nomes dos registradores Rx, Ry e Rz.

2. **Verificação das Vírgulas:**
   - Garantimos que há uma vírgula após cada registrador.

3. **Conversão para Binário:**
   - Os valores dos registradores são convertidos em representações binárias.

4. **Lógica Específica da Instrução XNOR:**
   - Realiza a operação lógica XNOR entre os valores de Ry e Rz e armazena o resultado em Rx.

5. **Construção da Instrução XNOR:**
   - A instrução XNOR é construída em formato binário.

6. **Escrita no Arquivo de Saída:**
   - A instrução XNOR é escrita no arquivo de saída do montador.

### Instrução NAND

#### Descrição

A instrução NAND realiza uma operação lógica "não e" (NAND) entre dois registradores e armazena o resultado em um terceiro registrador.

#### Implementação

A implementação da instrução NAND segue uma lógica semelhante à instrução XNOR no arquivo `montador.c`. Aqui estão os detalhes principais:

1. **Obtenção dos Registradores:**
   - São obtidos os nomes dos registradores Rx, Ry e Rz.

2. **Verificação das Vírgulas:**
   - Garantimos que há uma vírgula após cada registrador.

3. **Conversão para Binário:**
   - Os valores dos registradores são convertidos em representações binárias.

4. **Lógica Específica da Instrução NAND:**
   - Realiza a operação lógica NAND entre os valores de Ry e Rz e armazena o resultado em Rx.

5. **Construção da Instrução NAND:**
   - A instrução NAND é construída em formato binário.

6. **Escrita no Arquivo de Saída:**
   - A instrução NAND é escrita no arquivo de saída do montador.

### Instrução NOR

#### Descrição

A instrução NOR realiza uma operação lógica "não ou" (NOR) entre dois registradores e armazena o resultado em um terceiro registrador.

#### Implementação

A implementação da instrução NOR segue uma abordagem semelhante à instrução XNOR. Aqui estão os principais detalhes:

1. **Obtenção dos Registradores:**
   - São obtidos os nomes dos registradores Rx, Ry e Rz.

2. **Verificação das Vírgulas:**
   - Garantimos que há uma vírgula após cada registrador.

3. **Conversão para Binário:**
   - Os valores dos registradores são convertidos em representações binárias.

4. **Lógica Específica da Instrução NOR:**
   - Realiza a operação lógica NOR entre os valores de Ry e Rz e armazena o resultado em Rx.

5. **Construção da Instrução NOR:**
   - A instrução NOR é construída em formato binário.

6. **Escrita no Arquivo de Saída:**
   - A instrução NOR é escrita no arquivo de saída do montador.

### Como Utilizar

Para utilizar a nova instrução XNOR, siga os passos abaixo:

   ```assembly
   ; Exemplo de XNOR
   XNOR R1, R2, R3
    
   ; Exemplo de NAND
   NAND R4, R5, R6
    
   ; Exemplo de NOR
   NOR R7, R8, R9


