# Relatório de validação do acervo

Gerado em: 2026-07-12 01:23:42 UTC
Arquivo validado: `site/data/corpus-data-enriched.json`

## Resumo

- JSON válido: sim
- Schema válido: sim (validador: jsonschema)
- Itens no acervo: 95
- URLs de imagem verificadas: 124
- URLs acessíveis com status 200: 98
- Problemas encontrados: 26

## Itens quebrados ou inacessíveis

| Item | Campo | Status | Detalhe | URL |
|---|---|---:|---|---|
| `BE-002` Palais de Justice de Bruxelles (Joseph Poelaert) | `thumbnail_url` | 429 | GET retornou HTTP 429 | https://upload.wikimedia.org/wikipedia/commons/1/10/Bruxelles_-_Palais_de_Justice.jpg |
| `BR-005` Alegoria da República (Décio Villares) | `thumbnail_url` | 400 | GET retornou HTTP 400 | https://upload.wikimedia.org/wikipedia/commons/thumb/4/4b/D%C3%A9cio_Villares_-_A_Rep%C3%BAblica.jpg/800px-D%C3%A9cio_Villares_-_A_Rep%C3%BAblica.jpg |
| `EU-008` Allegory with Justizia, crowned by a putto | `url_image_download` | erro | GET falhou: URLError: <urlopen error [SSL: CERTIFICATE_VERIFY_FAILED] certificate verify failed: unable to get local issuer certificate (_ssl.c:1010)> | https://sammlungenonline.albertina.at/cc/imageproxy.ashx?server=localhost&port=15001&filename=images/30435.jpg&cache=yes |
| `EU-009` Female Allegory (Pierre Puvis de Chavannes) | `url_image_download` | erro | GET falhou: URLError: <urlopen error [SSL: CERTIFICATE_VERIFY_FAILED] certificate verify failed: unable to get local issuer certificate (_ssl.c:1010)> | https://sammlungenonline.albertina.at/cc/imageproxy.ashx?server=localhost&port=15001&filename=images/DG1918_7.jpg&cache=yes |
| `FR-012` La Liberté guidant le peuple (Eugène Delacroix) | `url_image_download` | 429 | GET retornou HTTP 429 | https://upload.wikimedia.org/wikipedia/commons/5/5d/Eug%C3%A8ne_Delacroix_-_Le_28_Juillet._La_Libert%C3%A9_guidant_le_peuple.jpg |
| `MX-001` [Virtudes cardinales: Justica] (La Patria Ilustrada) | `url_image_download` | 403 | GET retornou HTTP 403 | https://tile.loc.gov/storage-services/service/pnp/cph/3b10000/3b18000/3b18400/3b18453r.jpg |
| `UK-004` Lady Justice (F.W. Pomeroy, Old Bailey, London) | `thumbnail_url` | 429 | GET retornou HTTP 429 | https://upload.wikimedia.org/wikipedia/commons/f/f4/Old_Bailey_Lady_Justice.jpg |
| `UK-004` Lady Justice (F.W. Pomeroy, Old Bailey, London) | `url_image_download` | 429 | GET retornou HTTP 429 | https://upload.wikimedia.org/wikipedia/commons/f/f4/Old_Bailey_Lady_Justice.jpg |
| `UK-006` Women of Britain Say 'Go!' | `url_image_download` | 403 | GET retornou HTTP 403 | https://media.iwm.org.uk/ciim5/145/831/large_000000.jpg |
| `US-001` America pois'd in the balance of justice | `thumbnail_url` | 403 | GET retornou HTTP 403 | https://www.loc.gov/resource/cph.3a45724/ |
| `US-001` America pois'd in the balance of justice | `url_image_download` | 403 | GET retornou HTTP 403 | https://tile.loc.gov/storage-services/service/pnp/cph/3a40000/3a45000/3a45700/3a45724r.jpg |
| `US-002` Justice and History (plaster model for US Capitol) | `thumbnail_url` | 403 | GET retornou HTTP 403 | https://www.loc.gov/resource/ppmsca.87910/ |
| `US-002` Justice and History (plaster model for US Capitol) | `url_image_download` | 403 | GET retornou HTTP 403 | https://tile.loc.gov/storage-services/service/pnp/ppmsca/87900/87910v.jpg |
| `US-003` Justice (blindfolded woman with sword and scales) | `thumbnail_url` | 403 | GET retornou HTTP 403 | https://www.loc.gov/resource/cph.3b09379/ |
| `US-003` Justice (blindfolded woman with sword and scales) | `url_image_download` | 403 | GET retornou HTTP 403 | https://tile.loc.gov/storage-services/service/pnp/cph/3b00000/3b09000/3b09300/3b09379r.jpg |
| `US-004` Foire France-Américaine: Justice, Liberty, Demeter, Athena | `thumbnail_url` | 403 | GET retornou HTTP 403 | https://www.loc.gov/resource/cph.3f04023/ |
| `US-004` Foire France-Américaine: Justice, Liberty, Demeter, Athena | `url_image_download` | 403 | GET retornou HTTP 403 | https://tile.loc.gov/storage-services/service/pnp/cph/3f00000/3f04000/3f04000/3f04023r.jpg |
| `US-005` Behold! a fabric now to freedom rear'd (Constitutional allegory) | `url_image_download` | 403 | GET retornou HTTP 403 | https://tile.loc.gov/storage-services/service/pnp/cph/3a40000/3a45000/3a45700/3a45707r.jpg |
| `US-006` Die Wage der Macht / La balance de la puissance | `url_image_download` | 403 | GET retornou HTTP 403 | https://tile.loc.gov/storage-services/service/pnp/cph/3a40000/3a45000/3a45500/3a45590r.jpg |
| `US-007` Columbia presenting sword to Admiral Dewey | `thumbnail_url` | 403 | GET retornou HTTP 403 | https://www.loc.gov/resource/ppmsca.46404/ |
| `US-007` Columbia presenting sword to Admiral Dewey | `url_image_download` | 403 | GET retornou HTTP 403 | https://tile.loc.gov/storage-services/service/pnp/ppmsca/46400/46404v.jpg |
| `US-008` Hedwig Reicher as Columbia in suffrage pageant | `url_image_download` | 403 | GET retornou HTTP 403 | https://tile.loc.gov/storage-services/service/pnp/ppmsc/00000/00032v.jpg |
| `US-009` The Goddess of Liberty (woman in star-spangled cape) | `url_image_download` | 403 | GET retornou HTTP 403 | https://tile.loc.gov/storage-services/service/pnp/ppmsca/57600/57686v.jpg |
| `US-010` Temple of Liberty | `url_image_download` | 403 | GET retornou HTTP 403 | https://tile.loc.gov/storage-services/service/pnp/ppmsca/17500/17520v.jpg |
| `US-011` Wake up America! Civilization calls every man, woman and child! | `url_image_download` | 403 | GET retornou HTTP 403 | https://tile.loc.gov/storage-services/service/pnp/ppmsca/40900/40985v.jpg |
| `US-012` Columbia calls—Enlist now for U.S. Army | `url_image_download` | 403 | GET retornou HTTP 403 | https://tile.loc.gov/storage-services/service/pnp/ppmsca/50000/50012v.jpg |
