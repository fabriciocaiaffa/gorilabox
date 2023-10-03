# Gorilabox5.1 - aplicação Multiplataforma

![Gorilabox5.1 Logo] (link_para_o_logo.png)

O Gorilabox5.1 é uma máquina de música multiplataforma desenvolvida por Fabrício Caiaffa. Ela permite que os usuários acessem diferentes serviços de mídia, como Spotify, YouTube, Karaokê, e dispositivos Bluetooth (iOS, Android, Microsoft), além de oferecer equalização de áudio de 3 bandas e controle de volume.

## Estrutura de Diretórios do Projeto

O projeto é dividido em duas partes principais: o tema personalizado para WordPress (GORILABOX5_1) e o plugin "gorilabox-plugin" para incorporar as funcionalidades no site WordPress.

### Tema Personalizado (GORILABOX5_1)

```
wp-content/
│
└── themes/
    └── GORILABOX5_1/
        ├── assets/
        │   ├── css/
        │   │   ├── style.css  (Arquivo principal de estilos)
        │   │   ├── responsive.css  (Estilos para dispositivos móveis)
        │   │   └── ...
        │   ├── js/
        │   │   ├── main.js  (Arquivo principal de JavaScript)
        │   │   ├── custom.js  (Arquivo de scripts personalizados)
        │   │   └── ...
        │   ├── images/  (Pasta para imagens e recursos gráficos)
        │   └── ...
        ├── includes/
        │   ├── custom-widgets.php  (Arquivo para widgets personalizados)
        │   ├── custom-shortcodes.php  (Arquivo para shortcodes personalizados)
        │   └── ...
        ├── languages/
        │   └── gorilabox5_1.pot  (Arquivo de modelo para tradução)
        ├── templates/
        │   ├── custom-header.php  (Cabeçalho personalizado)
        │   ├── custom-footer.php  (Rodapé personalizado)
        │   ├── custom-single.php  (Modelo para posts individuais)
        │   ├── custom-page.php  (Modelo para páginas)
        │   └── ...
        ├── functions.php  (Arquivo de funções personalizadas)
        ├── page-templates/
        │   ├── template-full-width.php  (Modelo de página largura total)
        │   ├── template-contact.php  (Modelo de página de contato)
        │   └── ...
        ├── inc/
        │   ├── custom-post-types.php  (Definição de tipos de post personalizados)
        │   ├── custom-taxonomies.php  (Definição de taxonomias personalizadas)
        │   └── ...
        └── README.md
```

### Plugin "gorilabox-plugin"

```
wp-content/
│
└── plugins/
    └── gorilabox-plugin/
        ├── gorilabox-plugin.php
        ├── assets/
        │   ├── js/
        │   │   ├── gorilabox.js
        │   ├── css/
        │   │   ├── gorilabox.css
        ├── templates/
        │   ├── gorilabox-template.php
        ├── readme.txt
```

## Instalação

1. Clone este repositório para o diretório `/wp-content/themes/` no seu servidor WordPress para o tema personalizado.

2. Ative o tema personalizado "GORILABOX5_1" no painel de administração do WordPress.

3. Clone o repositório do plugin "gorilabox-plugin" para o diretório `/wp-content/plugins/` no seu servidor WordPress.

4. Ative o plugin "gorilabox-plugin" no painel de administração do WordPress.

## Uso

1. Crie uma página no WordPress utilizando o modelo de página personalizado "Gorilabox5.1 Template" para exibir as funcionalidades do Gorilabox5.1.

2. Personalize o estilo e os elementos de interface do usuário de acordo com as necessidades do seu projeto.

3. Configure as opções do plugin nas configurações do Gorilabox5.1.

## Requisitos

- WordPress 5.0 ou superior
- PHP 7.0 ou superior
- MySQL 5.6 ou superior

## Contribuições

Contribuições são bem-vindas! 

Sinta-se à vontade para abrir problemas (issues) e enviar solicitações de pull (pull requests) para melhorar este projeto.

## Licença

Este projeto é licenciado sob a Licença Pública Geral GNU v2 ou posterior. 
Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## Suporte

Para obter suporte ou relatar problemas, entre em contato conosco em [gorilabox5.1@ogorilao.com.br] ou visite [ https://ogorilao.com.br ].
# gorilabox
