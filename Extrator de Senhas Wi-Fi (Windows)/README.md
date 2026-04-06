# Extrator de Senhas Wi-Fi (Windows)

### AVISO EDUCACIONAL
Este código demonstra uma **vulnerabilidade de segurança real** do Windows.  
Use APENAS para:
- Testar a segurança do seu próprio computador
- Estudos de conscientização sobre segurança da informação
- Recuperar senhas de redes que você possui autorização

### Objetivo Educacional
Mostrar como o Windows armazena senhas Wi-Fi de forma acessível (com comando `netsh wlan show profiles`) e como um dispositivo USB pode extraí-las em segundos.

### Como funciona
1. O Digispark se conecta como teclado USB
2. Abre o Prompt de Comando
3. Executa comandos `netsh` para listar redes salvas
4. Extrai as senhas em texto puro
5. Salva em um arquivo .txt no Desktop

### Como se proteger
- **Desative o AutoRun** de dispositivos USB
- **Use BitLocker** para criptografar o sistema
- **Bloqueie portas USB** em computadores públicos
- **Nunca salve senhas** em redes desconhecidas

### Saída esperada
```
=== SENHAS WI-FI EXTRAÍDAS ===  
Rede: Minha Rede 2.4G  
Conteúdo da Chave: MinhaSenha123

Rede: Vizinho WiFi  
Conteúdo da Chave: 12345678
```
---

### Comandos explicados
| Comando | O que faz |
|---------|-----------|
| `netsh wlan show profiles` | Lista redes salvas |
| `key=clear` | Mostra senha em texto puro |
| `findstr "Conteudo da Chave"` | Filtra apenas a linha da senha |

### Variações do projeto
- **Versão stealth**: Fecha CMD automaticamente
- **Versão email**: Envia as senhas por email (requer conexão)
- **Versão USB rubber ducky**: Usa linguagem DuckyScript


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
<div align="center"> <sub> Feito por <strong>Prof. Max Muller - MMVonnSeek para a comunidade de segurança </strong></sub>

  
  

[![Stars](https://img.shields.io/github/stars/MMVonnSeek/Digispark-ATTiny85?style=social)](https://github.com/MMVonnSeek/Digispark-ATTiny85/stargazers)
[![Forks](https://img.shields.io/github/forks/MMVonnSeek/Digispark-ATTiny85?style=social)](https://github.com/MMVonnSeek/Digispark-ATTiny85/network/members)
[![Follow](https://img.shields.io/github/followers/MMVonnSeek?style=social)](https://github.com/MMVonnSeek)

<a href="https://wa.me/5561986194426?text=Olá%20tudo%20bem%20Max%3F%20Eu%20vim%20pelo%20seu%20repositorio%20do%20github.%20Podemos%20conversar%20sobre%3F" target="_blank">
  <img src="https://img.shields.io/badge/WhatsApp-Fale%20Comigo-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" />
</a>

<br>

  [Voltar ao topo](#-Digispark-ATTiny85)

</div>
