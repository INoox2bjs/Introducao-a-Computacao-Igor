# Aula 12 – Internet: História, Conceitos, Protocolos e Navegadores

## Integrantes do Grupo
- Nome 1
- Nome 2
- Nome 3
- Nome 4

---

# Objetivo

Este trabalho tem como objetivo compreender a origem e evolução da Internet, seus conceitos fundamentais, principais protocolos de comunicação e o papel dos navegadores, além de realizar uma análise prática de protocolos utilizando ferramentas de inspeção de rede.

---

# 1. História da Internet

A Internet surgiu a partir da ARPANET, criada no final da década de 1960 pela ARPA (Advanced Research Projects Agency), agência do governo dos Estados Unidos.

Inicialmente, a rede tinha fins militares e acadêmicos, permitindo a comunicação entre universidades e centros de pesquisa.

Durante as décadas de 1970 e 1980, a rede se expandiu e passou a utilizar o protocolo TCP/IP, tornando possível a comunicação entre diferentes redes.

Na década de 1990, ocorreu a comercialização da Internet, permitindo o crescimento de:
- sites;
- e-mails;
- comércio eletrônico;
- serviços online.

Em 1989, Tim Berners-Lee criou a World Wide Web (WWW), utilizando HTML, HTTP e navegadores para facilitar o acesso às informações.

---

# 2. Conceitos Fundamentais

## Internet vs. Web

### Internet
Rede mundial de computadores conectados.

### Web (WWW)
Sistema de páginas acessadas pela Internet.

### Diferença
- Internet = infraestrutura de rede.
- Web = serviço que utiliza a Internet.

---

## Arquitetura Cliente-Servidor

Modelo em que:
- o cliente faz uma solicitação;
- o servidor responde.

### Exemplo
Ao acessar um site:
1. o navegador envia uma requisição;
2. o servidor processa;
3. o servidor envia a resposta.

---

## Endereço IP

O IP identifica dispositivos em uma rede.

### Exemplo
```txt
192.168.0.1
```

### Função
- identificar dispositivos;
- permitir comunicação;
- localizar servidores.

---

# 3. Protocolos

## TCP/IP

### TCP
Garante a entrega correta dos dados.

### IP
Responsável pelo endereçamento e roteamento.

### Exemplo prático
Download de arquivos e acesso a sites.

---

## HTTP/HTTPS

### HTTP
Usado para transferência de páginas web.

### HTTPS
Versão segura com criptografia.

### Exemplo
```txt
https://www.google.com
```

---

## DNS

Traduz nomes de domínio em endereços IP.

### Exemplo
```txt
www.google.com → 142.250.190.14
```

---

## FTP

Protocolo utilizado para transferência de arquivos.

### Funções
- upload;
- download;
- gerenciamento remoto.

---

# 4. Navegadores

Os navegadores interpretam:
- HTML;
- CSS;
- JavaScript.

Transformando o código em páginas visuais.

---

## Motores de Renderização

| Motor | Navegadores |
|---|---|
| Blink | Chrome e Edge |
| Gecko | Firefox |
| WebKit | Safari |

---

# 5. Exercício Prático – Análise de Protocolos

## Ferramentas Utilizadas
- Wireshark
- Inspetor do Navegador (F12)

---

## Exemplo de Requisição

### Request
```txt
GET / HTTP/1.1
```

### Response
```txt
Content-Type: text/html
```

### Status Code
```txt
200 OK
```

---

## Exemplos de Status Code

| Código | Significado |
|---|---|
| 200 OK | Requisição bem-sucedida |
| 404 Not Found | Página não encontrada |
| 500 Internal Server Error | Erro no servidor |

---

# Organização dos Arquivos

```txt
Grupo1_Protocolos/
│
├── historia_internet.md
├── conceitos.md
├── protocolos.md
├── navegadores.md
├── analise_protocolos.pdf
└── README.md
```

---

# Conclusão

A Internet revolucionou a comunicação mundial, permitindo o compartilhamento rápido de informações e o desenvolvimento de diversos serviços digitais.

Protocolos como TCP/IP, HTTP, DNS e FTP são fundamentais para o funcionamento da rede, enquanto os navegadores permitem a interação dos usuários com páginas e aplicações web.

---

# Reflexão Individual

## Qual protocolo você considera mais essencial para o funcionamento da Internet e por quê?

O protocolo mais essencial para o funcionamento da Internet é o TCP/IP, pois ele é responsável pela comunicação entre dispositivos conectados em rede.

O IP identifica os dispositivos e define o caminho dos dados. Já o TCP garante que os pacotes sejam entregues corretamente e sem perdas.

Todos os outros protocolos dependem do TCP/IP para funcionar, tornando-o a base da Internet moderna.

---

# Referências

- https://www.w3.org
- https://www.cloudflare.com
- https://www.mozilla.org
- https://www.wireshark.org
