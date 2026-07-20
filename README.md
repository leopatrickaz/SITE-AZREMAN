# AZ Remanufaturados — Site institucional

Site estático (HTML/CSS/JS puro, sem build) para a AZ Remanufaturados, empresa
especializada em remanufatura de motores de partida e alternadores para linha
pesada.

## Objetivo do site

Gerar contato direto via WhatsApp para os dois serviços principais:
- Remanufatura de Motor de Partida
- Remanufatura de Alternador

Além disso, apresenta a empresa, o processo de remanufatura, diferenciais e
informações de contato.

## Estrutura

```
index.html      página única
css/style.css   estilos
js/script.js    menu mobile e ano do rodapé
assets/         ícones/imagens
```

## Como rodar localmente

Basta abrir `index.html` no navegador, ou servir a pasta com qualquer
servidor estático, por exemplo:

```
python3 -m http.server 8080
```

## Como editar

- **WhatsApp**: o número está nos links `https://wa.me/55...` em `index.html`.
  Para trocar, substitua o número em todas as ocorrências.
- **Logo**: atualmente é texto ("AZ" + "REMANUFATURADOS"). Para usar um logo
  em imagem, substitua o bloco `.logo` em `index.html` e ajuste `css/style.css`.
- **Cores**: definidas em variáveis CSS no topo de `css/style.css`
  (`--color-primary` etc.).
