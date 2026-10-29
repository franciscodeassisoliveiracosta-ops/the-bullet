# THE BULLET — site oficial · Website by Results.AG

## Estrutura

```
thebullet/
├── index.html            ← todo o HTML, CSS e JavaScript (a logo oficial está embutida como SVG)
└── assets/
    ├── bullet-logo.svg   ← logo oficial vetorizada (cópia avulsa, para uso em outros materiais)
    └── img/              ← 14 fotos + 1 imagem de projeto — nenhuma se repete
        └── covers/
```

O código está 100% em `index.html`; as fotos ficam em `assets/img/` com caminhos relativos.

## Curadoria (origem: Drive "Presskit The Bullet")

| Arquivo | Onde | Foto original |
|---|---|---|
| hero.jpg | Abertura | Fotos Estúdio — @gabriellrec-106 |
| about-01.jpg | Sobre (grande) | Fotos Estúdio — @gabriellrec-37 |
| about-02.jpg | Sobre (lateral) | Fotos Estúdio — @gabriellrec-98 |
| about-03.jpg | Sobre | Fotos Estúdio — @gabriellrec-63 |
| show-01 … 06.jpg | Carrossel Shows | IMG_0867, 8ef5313b, 9f6af0d7, IMG_2055, a3f58bb9, @gabriellrec-055 |
| frame-01 … 04.jpg | Scroll horizontal | adf91fab, 1ee6d961, IMG_6527, IMG_2188 |
| show-07 … 13.jpg | Carrossel Shows | IMG_6532, 3533ad7a, IMG_0356, IMG_2056, 85988286, @gabriellrec-29, 9c3082b0 |
| covers/pack-start.jpg | Lançamentos | Capa oficial de Pack Start (Deezer) |

Fotos redimensionadas (máx. 2000px) e comprimidas: 1,9 MB no total.

## Configuração (topo do `<script>` em index.html)

- `whatsappNumber` — WhatsApp de booking: 5581981184664 ((81) 98118-4664). Vazio = o botão
  "Solicitar booking" abre o Direct do Instagram @heythebullet.
- `genres` — gêneros exibidos na seção Sobre.
- Lançamentos, SoundCloud e Links oficiais estão escritos direto no HTML (seção `#lancamentos` e bloco `.links` no contato),
  com os links do Linktree oficial (linktr.ee/Thebulletdj).
- Legendas do carrossel: atributo `data-caption` de cada foto (evento/cidade/ano confirmados).

## Abrir e publicar

- **Abrir:** dois cliques em `index.html`.
- **Publicar:** envie a pasta inteira (`index.html` + `assets/`) para qualquer hospedagem estática —
  Netlify (arrastar a pasta em app.netlify.com/drop), Vercel, GitHub Pages, Cloudflare Pages ou FTP.
  Não há build nem instalação.
