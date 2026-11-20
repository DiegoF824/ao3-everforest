# 🌲 Everforest para AO3

Skin para o [Archive of Our Own](https://archiveofourown.org/) com a paleta
[Everforest Dark / Hard](https://everforest.vercel.app/palette).

Adaptação por **NeNekokun**. Repositório:
https://github.com/DiegoF824/ao3-everforest

## Arquivos

| Arquivo | Função |
| --- | --- |
| `base.css` | Layout em cartões e estilos dos componentes. |
| `theme_everforest.css` | Cores Everforest Dark / Hard. |
| `tags_everforest.css` | Estilo opcional de tags, com distinção de relações platônicas. |
| `tablet.css` | Ajustes para telas de até `62em`. |
| `mobile.css` | Ajustes para telas de até `42em`. |

## Paleta

| Uso | Cor |
| --- | --- |
| Fundo principal | `#272e33` |
| Fundo escurecido e sombras | `#1e2326` |
| Superfícies | `#2e383c`, `#374145`, `#414b50` |
| Texto | `#d3c6aa` |
| Verde | `#a7c080` |
| Vermelho | `#e67e80` |
| Amarelo | `#dbbc7f` |
| Azul | `#7fbbb3` |
| Aqua | `#83c092` |
| Roxo | `#d699b6` |
| Laranja | `#e69875` |

Sombras e bordas translúcidas usam cores da mesma paleta, mantendo suas opacidades.

## Instalação no AO3

1. Acesse **Dashboard → Skins → Create Site Skin**.
2. Crie skins separadas com nomes únicos para `base.css` e
   `theme_everforest.css`. Cole o conteúdo de cada arquivo no campo CSS e
   marque **Parent Only** nas opções avançadas.
3. Opcionalmente, crie outra skin **Parent Only** com `tags_everforest.css`.
4. Crie uma skin **Parent Only** com `tablet.css`. Em
   **Advanced → Choose @media**, selecione `only screen (max-width: 62em)`.
5. Faça o mesmo com `mobile.css`, selecionando
   `only screen (max-width: 42em)`.
6. Crie a skin final. Se o campo CSS exigir conteúdo, use
   `.everforest { opacity: 1; }`. Em **Parent Skins**, adicione as skins
   nesta ordem: base, tema, tags opcionais, tablet e mobile.
7. Salve e selecione **Use**.

**Atenção:** os arquivos mantêm o bloco original `.site-skin-metadata`, cujo
`content` contém uma string com quebras de linha literais, inválida em CSS
padrão. Ele foi preservado para não alterar a estrutura solicitada.
Se o AO3 rejeitar esse bloco, omita-o ao copiar o CSS para o site.
A instalação e a aparência no AO3 não foram verificadas nesta revisão.

## Escopo e dependências

- A adaptação altera cores, nomes, símbolos e links de repositórios nos
  metadados, sem modificar seletores, propriedades, layout ou filtros.
- Os ícones continuam hospedados externamente e dependem da disponibilidade
  desses arquivos. Os URLs das imagens foram preservados.
- As fontes declaradas no CSS precisam estar disponíveis no dispositivo;
  caso contrário, o navegador usa as alternativas especificadas.

## Créditos

- **NeNekokun** — adaptação Everforest.
- **Sainnhe Park** — paleta Everforest.
- **ZerafinaCSS** — base
  [neos](https://archiveofourown.org/works/65849527).
- Inspirações registradas nos arquivos: **Archive 2.0 skin**, por AO3;
  **Tide**, por ElectricAlice; e **Flat Squares Skin**, por milkfatzero.

Os metadados herdados indicam licença MIT. Essa indicação, isoladamente,
não estabelece a licença de todos os componentes e imagens externos;
verifique os termos das respectivas fontes antes de redistribuí-los.
