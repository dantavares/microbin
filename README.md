![Screenshot](.github/index.png)

# MicroBin

![Build](https://github.com/szabodanika/microbin/actions/workflows/rust.yml/badge.svg)
[![crates.io](https://img.shields.io/crates/v/microbin.svg)](https://crates.io/crates/microbin)
[![Docker
Image](https://github.com/szabodanika/microbin/actions/workflows/release.yml/badge.svg)](https://hub.docker.com/r/danielszabo99/microbin)
[![Docker
Pulls](https://img.shields.io/docker/pulls/danielszabo99/microbin?label=Docker%20pulls)](https://img.shields.io/docker/pulls/danielszabo99/microbin?label=Docker%20pulls)

O MicroBin é uma aplicação web de pastebin extremamente leve, rica em
recursos, configurável, autocontida e auto-hospedável. É muito fácil de
configurar e usar, exigindo apenas alguns megabytes de memória e
armazenamento em disco. Leva apenas alguns minutos para colocar em
funcionamento --- por que não experimentar agora?

### Confira o servidor público de testes em [pub.microbin.eu](https://pub.microbin.eu)!

### Ou hospede o MicroBin você mesmo

Puxe a imagem do Docker
([DockerHub](https://hub.docker.com/r/44934045/microbin)):

No nosso site [microbin.eu](https://microbin.eu), você encontrará o
seguinte:

-   [Screenshots](https://microbin.eu/screenshots/)
-   [Guide and Documentation](https://microbin.eu/docs/intro)
-   [Donations and Sponsorships](https://microbin.eu/sponsorship)
-   [Roadmap](https://microbin.eu/roadmap)

## Recursos

-   Executável totalmente autocontido --- o MicroBin é um único arquivo!
-   Criptografia no lado do servidor e no lado do cliente
-   Envio de arquivos (ex.: `server.com/file/pig-dog-cat`)
-   Disponibilização de texto bruto (ex.: `server.com/raw/pig-dog-cat`)
-   Suporte a QR Code
-   Encurtamento e redirecionamento de URLs
-   Nomes de animais em vez de números aleatórios para identificadores
    de envio (64 animais)
-   Suporte a banco de dados SQLite e JSON
-   Envios privados e públicos, editáveis ou não, com expiração
    automática ou permanente
-   Modo escuro automático e suporte a estilos personalizados com
    pouquíssimo CSS e apenas JavaScript puro (see
    [`water.css`](https://github.com/kognise/water.css))
-   E muito mais!

## O que é um envio?

No MicroBin, um envio pode ser:

-   Um texto que você deseja copiar de uma máquina para outra, por
    exemplo, um código,
-   Um arquivo que você deseja compartilhar, por exemplo, um vídeo
    grande demais para o Discord, um .zip com um projeto de código ou
    uma imagem,
-   Um redirecionamento de URL.

## Quando o MicroBin é útil?

Você pode usar o MicroBin:

-   Para enviar textos longos para outras pessoas,
-   Para enviar arquivos grandes para outras pessoas,
-   Para compartilhar segredos ou documentos sensíveis com segurança,
-   Como serviço de encurtamento/redirecionamento de URLs,
-   Para disponibilizar conteúdo na web, por exemplo, arquivos de
    configuração para testes, imagens ou qualquer outro tipo de arquivo
    usando a funcionalidade Raw,
-   Para mover arquivos entre seu desktop e um servidor acessado via
    console,
-   Como um serviço de "caixa postal", onde pessoas podem enviar
    arquivos ou textos, mas não podem ver ou remover o que outros
    enviaram a você,
-   Ou até mesmo para fazer anotações rápidas.

...e muitas outras coisas --- use a criatividade!

O MicroBin e o MicroBin.eu estão disponíveis sob a [BSD 3-Clause
License](LICENSE).
