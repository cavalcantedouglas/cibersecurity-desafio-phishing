# Phishing para captura de senhas do Facebook

Este é um projeto de engenharia social que o objetivo de criar um Phishing da pagina de login do Facebook e capturar credenciais

Para este método foi necessario criar um formulario HTML parecido com o Facebook.

Tomei essa decisão porque o metodo de copiar o site do setoolkit não estava funcionando corretamente, visto que o site do facebook tem muitas formas de segurança para evitar esse tipo de estratégia.

Como projeto de estudos funciona bem e tem espaço para muitas melhorias.

### Ferramentas

- Kali Linux
- setoolkit

### Configurando o Phishing no Kali Linux

- Acesso root: ``` sudo su ```
- Iniciando o setoolkit: ``` setoolkit ```
- Tipo de ataque: ``` Social-Engineering Attacks ```
- Vetor de ataque: ``` Web Site Attack Vectors ```
- Método de ataque: ```Credential Harvester Attack Method ```
- Método de ataque: ``` Custom Import ```
- Obtendo o endereço da máquina: ``` ifconfig ```
- Local onde o arquivo HTML está salvo: `Exemplo: /home/website/ (Tenha certeza que o caminho termina com /)`
- URL para clone: http://www.facebook.com

### Resutados

![image](https://github.com/user-attachments/assets/1ca0cc39-4f11-40a1-9f57-85a235cedeb7)
