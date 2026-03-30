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



## Licença

Distribuído sob a Licença MIT. Consulte o arquivo `LICENSE` para mais detalhes.


----------


## Contribuição

Se você gostou do projeto, não esqueça de:

-   ⭐ Deixar uma estrela no Repositório
    
-    Reportar bugs encontrados
    
-    Sugerir novas funcionalidades
    
-    Fazer um fork e contribuir
    

----------

## Dúvidas?

Se tiver alguma dúvida durante o processo, me chame no WhatsApp ou abra uma issue no GitHub.

---
<div align="center"> <sub> Feito por <strong>Prof. Max Muller - MMVonnSeek</strong></sub>

  
  

[![Stars](https://img.shields.io/github/stars/MMVonnSeek/Digispark-ATTiny85?style=social)](https://github.com/MMVonnSeek/Digispark-ATTiny85/stargazers)
[![Forks](https://img.shields.io/github/forks/MMVonnSeek/Digispark-ATTiny85?style=social)](https://github.com/MMVonnSeek/Digispark-ATTiny85/network/members)
[![Follow](https://img.shields.io/github/followers/MMVonnSeek?style=social)](https://github.com/MMVonnSeek)

<a href="https://wa.me/5561986194426?text=Olá%20tudo%20bem%20Max%3F%20Eu%20vim%20pelo%20seu%20repositorio%20do%20github.%20Podemos%20conversar%20sobre%3F" target="_blank">
  <img src="https://img.shields.io/badge/WhatsApp-Fale%20Comigo-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" />
</a>

<br>

  [Voltar ao topo](#-Digispark-ATTiny85)

</div>
