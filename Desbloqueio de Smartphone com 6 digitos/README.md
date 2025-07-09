# Desbloqueio Automático de Smartphone com Digispark ATTiny85

Este projeto demonstra como utilizar o microcontrolador **Digispark ATTiny85** para **simular comandos USB** (como um teclado HID) e **desbloquear automaticamente a tela de um smartphone** Android, por meio de uma sequência programada de teclas.




https://github.com/user-attachments/assets/f072fe65-92c5-4f95-95a5-bcf149bdcdb8



---

## Objetivo

Automatizar o processo de desbloqueio de um smartphone via USB usando o Digispark ATTiny85. O projeto é didático, com finalidades **educacionais**, **exploratórias** e **experimentais** voltadas para:

- Introdução a dispositivos HID com microcontroladores.
- Demonstração de automação física de tarefas em dispositivos móveis.
- Estudo sobre segurança física e interface homem-máquina (HCI).

---

## Requisitos

- 1x Digispark ATTiny85
- 1x Adaptador OTG ou cabo USB-C/OTG compatível com seu celular
- Software Arduino IDE
- Placa Digispark configurada na IDE
- Sketch HID com os comandos de desbloqueio

---

## Instalação do Digispark na Arduino IDE

1. Abra a Arduino IDE
2. Vá em **Arquivo > Preferências** e adicione o seguinte link em "URLs adicionais para Gerenciadores de Placas":

http://digistump.com/package_digistump_index.json

3. Vá em **Ferramentas > Placa > Gerenciador de Placas**, procure por "Digistump AVR Boards" e instale.
4. Selecione **Digispark (Default - 16.5mhz)** como placa.

---

## Como usar

1. Abra o arquivo `.ino` deste repositório.
2. Faça os ajustes no script (como tempo de delay e sequência de teclas).
3. Compile e **envie o código para o Digispark**.
4. Após carregar o código, conecte o Digispark ao **celular via adaptador OTG**.
5. O microcontrolador executará os comandos de desbloqueio automaticamente.

---

## Exemplo de funcionalidade

O script pode simular:

- Pressionar o botão de energia
- Inserir um PIN usando comandos de teclado
- Confirmar com "Enter" (se aplicável)
- Aguardar delays específicos entre comandos

---

## Aviso Legal

Este projeto é **estritamente educacional** e **não deve ser utilizado para acessar dispositivos sem autorização**. Toda e qualquer aplicação deve respeitar os princípios da ética e da legalidade. O autor **não se responsabiliza** pelo uso indevido.

---

## Conceitos explorados

- Microcontroladores como dispositivos HID (teclado)
- Automação com delays e comandos encadeados
- Interação entre hardware físico e sistemas móveis
- Segurança física de dispositivos móveis

---


## Contribuições

Contribuições são bem-vindas! Sinta-se livre para fazer um fork, abrir issues ou enviar pull requests com melhorias, sugestões e testes em outros modelos de celular.

---

## Licença

Distribuído sob a Licença MIT. Consulte o arquivo `LICENSE` para mais detalhes.

---

## Autor

**Professor Max Müller**  
