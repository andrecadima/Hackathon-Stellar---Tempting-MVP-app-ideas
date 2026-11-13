# Ecosistema Stellar: estado actual, prioridades estratégicas y necesidades no cubiertas (corte: 10 de noviembre de 2026)

Nota metodológica: todas las fuentes se consultaron el 10-nov-2026. Salvo que se indique lo contrario, los datos son de 2026 (menos de 12 meses). Lo marcado como **[secundaria]** proviene de prensa cripto o agregadores y no se pudo contrastar con el documento primario de SDF. Lo marcado como **[posiblemente desactualizado]** tiene más de 12 meses o procede de una versión anterior de una página que ya cambió.

## 1. Prioridades estratégicas y roadmap de SDF para 2026 (y adelanto de 2027)

### Takeaway
La estrategia 2026 de SDF se titula "Accelerating growth" y busca "scale what already works": +$1.000M de valor de activos en la red, 15 empresas "transformacionales" firmadas (5 desplegadas), más throughput y un upgrade de protocolo por trimestre. Para H2 2026 los focos técnicos explícitos son confidential tokens / privacidad, pagos agénticos (x402 / MPP), preparación post-cuántica y escalabilidad (Protocol 30 "Bell", Project Thruput). No se encontró un roadmap 2027 formal.

### Cited Findings
- La página de estrategia define 4 "north stars": (1) "Open participation, innovation and governance for a future-proof and sustainable Stellar"; (2) "Prioritizing everyday financial services to achieve our mission"; (3) "A trustworthy technology stack that advances adoption for everyday financial services"; (4) "Outcome-oriented execution to achieve SDF's goals". — [stellar.org/strategy](https://stellar.org/strategy)
- Meta numérica de adopción de activos: "$1 billion in growth for network asset value on Stellar"; áreas de foco: business development, ecosystem expansion, organic wallet growth, liquidity depth. — [stellar.org/strategy](https://stellar.org/strategy)
- Meta empresarial: "sign 15 new transformational enterprises" y "deploy at least 5 in 2026"; áreas de foco: enterprise partner success, institutional wallets & ramps, enterprise awareness, **privacy**. — [stellar.org/strategy](https://stellar.org/strategy)
- Infraestructura: "Increase Mainnet transactions per second across the stack", "Deliver a data-driven, medium-term scaling plan to raise throughput and reduce latency", "Improve close times, end-to-end latency and validator capacity", "Emergency deployment readiness for protocol upgrades", y el objetivo declarado de "establishing Stellar as the best platform for competitive DeFi protocols". La página no da cifras de TPS ni de latencia. — [stellar.org/strategy](https://stellar.org/strategy)
- El informe Q2 2026 de SDF fija como focos de H2 2026: confidential tokens, pagos agénticos (x402), preparación post-cuántica y el siguiente upgrade trimestral; cadencia declarada de un upgrade mayor por trimestre. — [SDF Q2 2026](https://stellar.org/blog/foundation-news/q2-2026-what-stellar-was-built-for-has-arrived)
- Stellar se unió a la x402 Foundation con asiento en el board. — [SDF Q2 2026](https://stellar.org/blog/foundation-news/q2-2026-what-stellar-was-built-for-has-arrived)
- Foco regional: LATAM (remesas y acceso; MGUSD, YLDS, Stellar House Ciudad de México), Europa (emisión regulada), África (acceso a pagos; enviar dinero cuesta 8,8% de media), APAC (credibilidad institucional), Medio Oriente y Turquía. Crecimiento concentrado en Nigeria, India, Turquía y Brasil. — [SDF Q2 2026](https://stellar.org/blog/foundation-news/q2-2026-what-stellar-was-built-for-has-arrived)
- Q1 2026: hackathon de pagos agénticos con 591 hackers y 288 entregas, "el mayor de la historia de Stellar"; spec y SDK de x402 publicados; SDK completo de MPP entregado una semana después del anuncio de Stripe y Tempo. — [SDF Q1 2026](https://stellar.org/blog/foundation-news/q1-2026-execution-at-network-scale)
- Quantum Preparedness Plan (9-jun-2026): plan en tres etapas hacia criptografía post-cuántica; la primera etapa está prevista para 2026. — [SDF: Quantum Preparedness Plan](https://stellar.org/blog/foundation-news/introducing-the-quantum-preparedness-plan)
- Project Thruput (28-oct-2026, anunciado en Meridian): technology preview en FutureNet de un modelo de ejecución paralela donde el cómputo crece añadiendo máquinas; benchmark solo del motor de ejecución: de 1,18M a 7,02M pagos/segundo al pasar de 1 a 8 máquinas; sin fees por transacción (el scheduling se reparte según saldo nativo desbloqueado). SDF pide a los developers: probarlo, traer contratos "caros" y agentes que necesiten ejecución gratuita. No da metas de TPS de red ni calendario. — [SDF: Project Thruput](https://stellar.org/blog/foundation-news/introducing-stellar-project-thruput)
- Mandato de SDF reorganizado en 4 cubos de XLM: SDF Development, Stellar Growth (el mayor; programas de developers, hackathons, Enterprise Fund), Product and Innovation ("high-impact tools the ecosystem needs") y Assets and Liquidity (emisión de activos, market making, on/off-ramps, bridges y compliance). Sin fecha visible en el artículo. — [SDF: updated mandate](https://stellar.org/blog/foundation-news/an-updated-mandate-for-a-growing-stellar-ecosystem)
- Freighter fue renombrada a **Varial** el 29-oct-2026 ("Your wallet for discovering Stellar"). — [SDF blog](https://stellar.org/blog/foundation-news/freighter-is-now-varial)
- Chainlink (Data Feeds y Data Streams) está en vivo en Stellar desde el 14-oct-2026; USDT0 desde el 2-sep-2026. — [SDF: Chainlink](https://stellar.org/blog/foundation-news/chainlink-is-now-live-on-stellar-unleashing-a-new-wave-of-defi-innovation); [SDF: USDT0](https://stellar.org/blog/foundation-news/usdt0-is-now-live-on-stellar)
- **[secundaria]** En Meridian 2026 (Lisboa, 28-29 oct, lema "Made to Move") la dirección de SDF presentó una visión a 10 años (2036) centrada en pasar de infraestructura a utilidad real. — [coinalertnews](https://coinalertnews.com/news/2026/10/02/stellar-2036-vision-meridian-2026); [cryptobriefing](https://cryptobriefing.com/stellar-meridian-2026-lisbon-conference/)
- HackMeridian se celebró el 25-26 oct-2026 en Lisboa; la página no publica tracks, premios ni ganadores. — [meridian.stellar.org/hackmeridian](https://meridian.stellar.org/hackmeridian)

### Inferences
- Los cuatro temas que SDF repite en fuentes primarias de H2 2026 son: (a) privacidad compatible con compliance, (b) pagos agénticos, (c) smart accounts / C-addresses como modelo de cuenta por defecto, (d) utilidad y distribución de RWA y stablecoins (no más emisión, sino uso). Un MVP alineado con dos o más de ellos encaja con el discurso oficial.
- "Scale what already works" y el énfasis en "organic wallet growth" y "liquidity depth" sugieren que SDF valora más uso on-chain real sobre activos existentes (USDC, EURC, BENJI, Spiko, MGUSD) que protocolos nuevos aislados.
- La meta de $1.000M de crecimiento de valor de activos ya se habría superado ampliamente solo con RWA (de ~$785M a fin de 2025 a >$4.000M), por lo que el cuello de botella actual es utilidad/composabilidad DeFi de esos activos, no la emisión.

### Gaps
- No se localizó el informe Q3 2026 de SDF en stellar.org (solo cobertura secundaria); tampoco un recap oficial de anuncios de Meridian 2026 ni la lista de ganadores/tracks de HackMeridian.
- No existe (o no se encontró) un roadmap 2027 publicado; lo único con horizonte 2027+ es el plan cuántico y las pistas de Bell sobre ledgers más rápidos.
- La visión "2036" solo aparece en sitios secundarios de baja calidad; no se verificó en fuente primaria.

## 2. Estado de Soroban: upgrades de protocolo, madurez del tooling y puntos de dolor

### Takeaway
Soroban ha recibido en 2026 primitivas ZK completas (BN254 + Poseidon en Protocol 25; MSM y aritmética Fr en Protocol 26), delegación de autenticación para smart accounts (Protocol 27) y, con Protocol 30 "Bell" (voto de mainnet el 23-nov-2026), direcciones de contrato muxed "W", verificación post-cuántica ML-DSA y tiempos de ledger en milisegundos. El tooling de smart accounts y relayers se ha consolidado en torno a OpenZeppelin, pero la privacidad sigue en testnet sin auditar y el soporte de C-addresses en wallets, anchors y exchanges sigue siendo un punto de fricción reconocido.

### Cited Findings
Upgrades de protocolo (fuente primaria salvo nota):
- Protocol 22 (5-dic-2024): constructores (CAP-58) y BLS12-381 (CAP-59). **[más de 12 meses]** — [developers.stellar.org: software versions](https://developers.stellar.org/docs/networks/software-versions)
- Protocol 23 "Whisk" (3-sep-2025): eventos unificados (CAP-67) y state archival (CAP-62, CAP-66). **[más de 12 meses]** Protocol 24 (22-oct-2025): upgrade de estabilidad (CAP-76). **[más de 12 meses]** — [software versions](https://developers.stellar.org/docs/networks/software-versions)
- Protocol 25 "X-Ray" (22-ene-2026): operaciones de curva BN254 (CAP-74) y permutaciones Poseidon/Poseidon2 (CAP-75). — [software versions](https://developers.stellar.org/docs/networks/software-versions)
- Protocol 26 "Yardstick" (6-may-2026): congelación de ledger entries por configuración de red (CAP-77), SAC puede crear balances de cuentas G (CAP-73), host functions de extensión de TTL limitada (CAP-78), conversión strkey de direcciones muxed (CAP-79), funciones BN254 para ZK: G1 MSM, aritmética Fr, on-curve checks (CAP-80), aritmética checked de 256 bits (CAP-82). — [software versions](https://developers.stellar.org/docs/networks/software-versions); [skills.stellar.org standards](https://skills.stellar.org/skills/standards/SKILL.md)
- Protocol 27 "Zipper" (8-jul-2026): delegación de autenticación y credenciales Soroban ligadas a dirección (CAP-71), para evitar replay de firmas entre cuentas. — [software versions](https://developers.stellar.org/docs/networks/software-versions); [blockchain.news](https://blockchain.news/news/stellar-protocol-27-zipper-upgrade)
- Protocol 28 (16-sep-2026; la prensa lo llama "Adapter"): voto de validadores para descartar el transaction set del ledger actual (CAP-83), ejecutables de contrato gestionados externamente (CAP-85; "atomic fleet upgrades" según prensa), host functions para mapas dispersos con claves symbol (CAP-86; "migration-friendly contract data"). — [software versions](https://developers.stellar.org/docs/networks/software-versions); [edgex **[secundaria]**](https://pro.edgex.exchange/en-US/news/article/stellar-xlm-protocol-28-adapter)
- Protocol 28 redujo el tiempo de cierre de ledger en mainnet a ~5 segundos. — [SDF: Introducing Bell](https://stellar.org/blog/developers/introducing-bell-protocol-30-on-stellar)
- Protocol 29 (listado con fecha 1-oct-2026): solo correcciones de seguridad de Stellar Core, "introduces no new CAPs". — [software versions](https://developers.stellar.org/docs/networks/software-versions)
- Protocol 30 "Bell": CAP-84 (direcciones de contrato muxed con ID de 64 bits, formato nuevo que empieza por **W**; permite modelo omnibus sobre smart accounts sin desplegar un contrato por cliente), CAP-87 (verificación de firmas post-cuánticas ML-DSA dentro de contratos), CAP-88 (timing de ledger en milisegundos; elimina el suelo de un ledger por segundo). Stellar Core v30.0.0 estable el 16-oct-2026; voto de testnet el 3-nov-2026; **voto de mainnet el 23-nov-2026 a las 17:00 UTC** (fechas sujetas a cambio). — [SDF: Introducing Bell](https://stellar.org/blog/developers/introducing-bell-protocol-30-on-stellar)
- Acciones requeridas por Bell: wallets y explorers deben aceptar direcciones W; indexers que decodifican XDR sin SDK deben actualizar definiciones o sus decoders se romperán. Pista del siguiente protocolo: signer post-cuántico nativo para cuentas clásicas y ledgers más rápidos. — [SDF: Introducing Bell](https://stellar.org/blog/developers/introducing-bell-protocol-30-on-stellar)
- secp256r1 (CAP-51, base criptográfica de passkeys) está listado como estándar "high-value" para flujos de smart wallet junto con SEP-10. **[CAP-51 es de 2024; más de 12 meses]** — [skills.stellar.org standards](https://skills.stellar.org/skills/standards/SKILL.md)

Versiones y tooling:
- Versiones actuales: Stellar CLI 28.1.0, soroban-sdk (Rust) 28.0.0, Stellar RPC v29.0.0. — [software versions](https://developers.stellar.org/docs/networks/software-versions)
- Launchtube (servicio experimental de fee sponsorship) está siendo reemplazado por **OpenZeppelin Relayer / Stellar Channels Service**: infraestructura para enviar transacciones Soroban con procesamiento paralelo automático; versión open source autoalojada y Relayer Service alojado por OpenZeppelin. — [developers.stellar.org: OpenZeppelin Relayer](https://developers.stellar.org/docs/tools/openzeppelin-relayer); [OpenZeppelin, 24-mar-2026](https://www.openzeppelin.com/news/expanding-stellar-support-with-relayer-service)
- **Smart Account Kit**: SDK TypeScript para desplegar y gestionar contratos OpenZeppelin Smart Account en Soroban con autenticación WebAuthn/passkeys; usa el Relayer automáticamente si está configurado; última versión vista v0.2.9 (es decir, pre-1.0). — [pkgstats: smart-account-kit](https://www.pkgstats.com/pkg:smart-account-kit)
- La colaboración OpenZeppelin–Stellar abarca de enero de 2025 a diciembre de 2026 e incluye auditorías y bug bounty. — [OpenZeppelin](https://www.openzeppelin.com/news/expanding-stellar-support-with-relayer-service)
- Pagos agénticos: x402 (un pago por request HTTP 402, liquidación en menos de 5 s) y MPP (sesiones con límite de gasto preautorizado, canales off-chain de alta frecuencia, liquidación vía transferencias SAC) se describen como "now live on Stellar mainnet"; el SDK gestiona fees patrocinados por el servidor (el agente no necesita XLM). USDC, PYUSD y USDY se citan como "first-class native assets — not bridged, not wrapped". OpenZeppelin opera el facilitator de x402 y aporta smart accounts auditadas con "programmable spending limits and guardrails". — [Stellar dev meeting 16-abr-2026](https://developers.stellar.org/meetings/2026/04/16); [docs: Agentic Payments](https://developers.stellar.org/docs/build/agentic-payments); [stellar.org/x402](https://stellar.org/x402)
- Herramientas para desarrollo asistido por IA: plugin "Stellar Dev Skill" y `llms.txt` en developers.stellar.org/docs/tools/ai. — [Stellar dev meeting 16-abr-2026](https://developers.stellar.org/meetings/2026/04/16)
- Privacidad, capa 1 — **Stellar Private Payments (SPP)** de Nethermind (developer preview, 24-ago-2026): privacy pool con Groth16 verificado on-chain con BN254/BLS12-381 y Poseidon; pools de XLM y EURC en testnet; **contratos sin auditar, no aprobado para mainnet**. Compliance integrado: Association Set Providers (block-list / allow-list), global view keys para auditor, selective disclosure. SDK TS/JS `stellar-private-payments@alpha`, SDK Rust y CLI `spp`. — [SDF: Developer Preview SPP](https://stellar.org/blog/developers/developer-preview-stellar-private-payments)
- Limitaciones declaradas de SPP: selective disclosure es por nota y "no prueba origen de fondos ni historial completo"; el etiquetado y trazado de depósitos a nivel de nota sigue en diseño; el CLI no soporta todas las funciones. Se buscan "design partners" para soluciones de privacidad con foco en compliance. — [SDF: Developer Preview SPP](https://stellar.org/blog/developers/developer-preview-stellar-private-payments)
- Privacidad, capa 2 — **Confidential Tokens**: ocultan importes y balances entre contrapartes conocidas, usan verificador UltraHonk (Nethermind); developer preview en testnet, no aprobado para mainnet; estándar compatible con ERC-7984 en desarrollo con OpenZeppelin. — [SDF: Developer Preview SPP](https://stellar.org/blog/developers/developer-preview-stellar-private-payments); [Nansen Q2 2026](https://nansen.ai/post/stellar-q2-2026-report); [SDF Q1 2026](https://stellar.org/blog/foundation-news/q1-2026-execution-at-network-scale)
- Otros proyectos de privacidad nombrados por SDF: Boundless y Arcane; post "Practical Confidential Stablecoins: An Issuer-Controlled Architecture" (24-sep-2026). — [SDF Q1 2026](https://stellar.org/blog/foundation-news/q1-2026-execution-at-network-scale); [SDF blog](https://stellar.org/blog/developers/practical-confidential-stablecoins-an-issuer-controlled-architecture)
- Oráculos: Chainlink Data Feeds y Data Streams en vivo (oct-2026). — [SDF: Two ways to read Chainlink prices](https://stellar.org/blog/developers/ways-to-read-chainlink-prices-on-stellar-data-feeds-and-data-streams)
- Bridges: Circle CCTP en vivo desde el 19-may-2026 (conecta 23 cadenas); LayerZero añadido a la lista de integración de SCF en sep-2026. — [SDF Q2 2026](https://stellar.org/blog/foundation-news/q2-2026-what-stellar-was-built-for-has-arrived); [SCF Handbook](https://stellar.gitbook.io/scf-handbook)

Puntos de dolor documentados:
- Los RFP de SCF de Q1 2026 nombran carencias concretas: API de precios, API de posiciones DeFi, tooling y onboarding de C-addresses (financiar una C-address directamente desde una G-address o desde un retiro de CEX) y un block explorer "Soroban-first". — [SCF Handbook: RFP Track](https://stellar.gitbook.io/scf-handbook/scf-awards/scf-build/rfp-track) (listado visto en una versión anterior de la página; hoy muestra "coming soon")
- Un proyecto premiado (OctoPos, SCF #41) describe el problema así: "Wallets do not consistently display positions", las posiciones de deuda suelen ser invisibles y la fragmentación bloquea estrategias de yield, apps de finanzas personales y agentes de IA que rebalancean. — [communityfund.stellar.org: OctoPos](https://communityfund.stellar.org/submissions/recOh9tgSDRC3elBf)
- Autenticación dual: SEP-45 cubre cuentas de contrato (C...) y SEP-10 cubre G... y M...; "Services wishing to support all account types should implement both SEPs", y SEP-45 exige integración con Stellar RPC para simular transacciones. — [Anchor Platform: SEP-45](https://developers.stellar.org/docs/platforms/anchor-platform/sep-guide/sep45)
- El Flutter SDK 3.2.1 sustituyó un delay fijo por polling del RPC para la visibilidad de cuenta/contrato durante la creación de wallet (indicio de problemas de timing en el alta de smart accounts). — [pub.dev changelog](https://pub.dev/packages/stellar_flutter_sdk/versions/3.2.1/changelog)
- Hack de Blend (22-feb-2026) clasificado por DefiLlama como manipulación de oráculo, $10,97M. — [DefiLlama: Blend Pools V2](https://defillama.com/protocol/blend-pools-v2); cifra contradictoria de $717K en [coin-turk **[secundaria]**](https://en.coin-turk.com/stellar-defi-tvl-plunges-60yuzde-after-717k-blend-exploit-xlm-holds-0-18/)

### Inferences
- "Parallel execution" como tal no figura en ningún CAP activado en mainnet en la tabla oficial de versiones; lo que existe es Project Thruput en FutureNet (preview). Un MVP de hackathon no debe depender de Thruput.
- Las primitivas ZK (BN254, Poseidon, MSM) están en mainnet, pero las aplicaciones de privacidad de referencia (SPP, Confidential Tokens) siguen en testnet y sin auditar: hay espacio claro para casos de uso ZK de aplicación (pruebas de solvencia, KYC selectivo, credenciales, compliance attestations) que SDF y Nethermind declaran como pendientes.
- El stack "passkey smart account + OpenZeppelin Relayer + x402/MPP" es el camino feliz que SDF promueve; Smart Account Kit en v0.2.x indica API todavía inestable, lo que supone riesgo técnico y a la vez oportunidad de tooling.
- CAP-84 (direcciones W) crea una necesidad inmediata y fechada (voto el 23-nov-2026): wallets, explorers, indexers, ramps y SDKs deben soportar W; herramientas de migración, validación o demostraciones del modelo omnibus sobre smart accounts serían oportunas.
- El hack de oráculo de Blend más la llegada de Chainlink en octubre sugieren demanda de infraestructura de precios y gestión de riesgo (coincide con el RFP "Prices API").

### Gaps
- No se encontró una encuesta formal de developers ni un listado oficial de "pain points" de Soroban; la evidencia de fricción es indirecta (RFPs, changelogs, propuestas premiadas).
- No se verificó el estado actual de Scaffold Stellar ni de Stellar Wallets Kit (versiones, soporte de smart accounts / direcciones W); no aparecieron en fuentes fechadas en 2026 durante esta búsqueda.
- No se encontraron cambios de fees de Soroban en 2026 en la tabla oficial de versiones; el dato disponible es solo "fees medios de ~una centésima de centavo" (SDF Q1/Q2).
- No está claro si las smart accounts auditadas de OpenZeppelin y el facilitator de x402 tienen limitaciones de disponibilidad o cuotas en mainnet; las notas de la reunión no lo detallan.
- Estado del issue stellar-protocol #1928 (manejo de C-addresses en `getAddress` de wallets) no verificado.

## 3. Qué financia hoy el Stellar Community Fund (SCF) y qué RFPs / wishlists existen

### Takeaway
SCF 7.0 (desde enero de 2026) financia hasta $150K en XLM por proyecto mediante el Build Award con tres tracks: Open (casos de uso novedosos), Integration (integrar piezas existentes) y RFP (dev tools que responden a un RFP activo). A 10-nov-2026 **no hay RFPs abiertos publicados**: la página dice "October 2026: New Q4 RFPs are coming soon". Los últimos RFPs con nombre conocido son los de Q1 2026: Prices API, DeFi Positions API, C-Address Tooling & Onboarding y Soroban-first Block Explorer.

### Cited Findings
- Tracks del Build Award: Open Track "for experienced teams building novel usecases"; Integration Track "for teams looking to incorporate existing ecosystem solutions into their products"; RFP Track "for dev tools that respond to an active SCF Request for Proposals". — [SCF Handbook](https://stellar.gitbook.io/scf-handbook)
- Financiación: "up to a total of $150,000 worth of XLM in funding" por proyecto; tope vitalicio de $300.000 caso a caso para proyectos ya financiados; pago en 4 tramos de 10%, 20%, 30% y 40%. — [SCF Handbook](https://stellar.gitbook.io/scf-handbook)
- Otros programas: Instaward (vía Ambassador Chapters), Public Goods Award, Audit Bank, Liquidity Award, Growth Hack, aceleradoras. — [SCF Handbook](https://stellar.gitbook.io/scf-handbook)
- Criterios de revisión: valor potencial para el ecosistema Stellar/Soroban, alineación con objetivos de SCF y capacidad del equipo; SCF "relies heavily on referral signals" de actores del ecosistema; todo proyecto nuevo empieza por el Interest Form. — [SCF Handbook](https://stellar.gitbook.io/scf-handbook)
- Estado de RFPs: "October 2026: New Q4 RFPs are coming soon"; secciones marcadas "Coming Soon". Los RFPs los eligen los Delegates en el SCF Quarterly Process y se publican al inicio de cada trimestre. "There will be no open RFPs for the SCF #43 submission window"; los RFPs de Q2 se movieron a SCF #44. — [SCF Handbook: RFP Track](https://stellar.gitbook.io/scf-handbook/scf-awards/scf-build/rfp-track); [SCF Handbook](https://stellar.gitbook.io/scf-handbook)
- RFPs de Q1 2026 (según una versión indexada de la página, ya no visible): **Prices API**; **DeFi Positions API** ("aggregation service and API to normalize and display a user's total DeFi exposure across multiple, supported Stellar protocols", acepta G-address o C-address); **C-Address Tooling & Onboarding** (financiar una C-address directamente desde una G-address o un retiro de CEX, haciendo el paso por G-address transparente o innecesario); **Soroban-first Block Explorer**. — [SCF Handbook: RFP Track](https://stellar.gitbook.io/scf-handbook/scf-awards/scf-build/rfp-track)
- Respuestas ya presentadas o premiadas a esos RFPs: OctoPos ("DeBank for Stellar", premiado, $120K; cubre Blend, Aquarius, Soroswap, Phoenix Hub y Untangled Vault; datos exigidos por el RFP: valor total, valor depositado, valor prestado, retorno actual y health factor) — [OctoPos](https://communityfund.stellar.org/submissions/recOh9tgSDRC3elBf); Orion (otra API de posiciones DeFi) — [submission](https://communityfund.stellar.org/submissions/rec0QBqMONJbGabzq); una propuesta de Prices API — [submission](https://communityfund.stellar.org/submissions/recPt6cTMzx8XmiNj); Lazee Kit (onboarding de C-addresses, SCF #44, track RFP) — [lazee-kit-site](https://lazee-kit-site.pages.dev/).
- Integration Track: bloques a integrar = wallets de Stellar, anchors u on/off-ramps, DEXs y protocolos DeFi; los ejemplos de presupuesto mencionan SDP, MGI (MoneyGram), on-ramp, anchor, DEX y despliegue de bridge cross-chain. Presupuestos sugeridos: $25K–$50K (una integración simple), $50K–$100K, $100K–$150K. — [SCF Handbook: Integration Track](https://stellar.gitbook.io/scf-handbook/scf-awards/scf-build/integration-track)
- Filosofía explícita del Integration Track: "combine ecosystem pieces, not build new ones"; "The point is to prove real usage"; el último tramo (40%) se paga al alcanzar una métrica on-chain comprometida; prohibidos incentivos pagados, airdrops y campañas de volumen. No es para apps nuevas sin tracción, protocolos nuevos ni dev tools. — [SCF Handbook: Integration Track](https://stellar.gitbook.io/scf-handbook/scf-awards/scf-build/integration-track)
- Volumen de financiación: las rondas SCF #42 y #43 pusieron $5,5M detrás de 55 empresas. — [SDF Q2 2026](https://stellar.org/blog/foundation-news/q2-2026-what-stellar-was-built-for-has-arrived)
- Canal oficial para proponer ideas no listadas: página Stellarlight Ideas (ideas.stellarlight.xyz) y Stellar Dev Discord. — [SCF Handbook: RFP Track](https://stellar.gitbook.io/scf-handbook/scf-awards/scf-build/rfp-track)

### Inferences
- Los cuatro RFPs de Q1 2026 ya tienen respondedores (al menos uno premiado), así que repetirlos tal cual es poco diferencial; pero señalan la familia de problemas que los Delegates priorizan: **capa de datos y lectura (precios, posiciones, explorer) y UX de C-addresses**. Capas adyacentes aún no cubiertas por un RFP conocido (alertas de riesgo / health factor, historial y contabilidad de smart accounts, soporte de direcciones W, onramp directo a C-address) son candidatas naturales.
- Para un equipo de hackathon sin tracción, la ruta realista de financiación es Instaward u Open Track; el Integration Track exige tracción previa. Diseñar el MVP sobre bloques existentes (Blend, Aquarius, Soroswap, anchors, SDP, MoneyGram, CCTP, LayerZero, Chainlink) facilita una solicitud posterior.
- La exigencia de métricas on-chain reales indica que SCF penaliza demos sin usuarios ni transacciones verificables.

### Gaps
- **RFPs de Q4 2026 no publicados** a la fecha de corte; conviene revisar la página del RFP Track y el Discord antes del hackathon.
- No se pudieron obtener los RFPs de Q2/Q3 2026 (SCF #44 en adelante) ni el texto completo de los RFPs de Q1 (requisitos y presupuestos); la versión actual de la página ya no los muestra.
- ideas.stellarlight.xyz devolvió 404 al intentar leerla; no se pudo extraer la wishlist comunitaria.
- No se pudo leer la "Integration List" oficial ni el Airtable de partners.
- No se encontró ningún texto de SCF que nombre categorías excluidas o "saturadas" de forma explícita.

## 4. Categorías saturadas frente a categorías poco construidas

### Takeaway
No hay una lista oficial de categorías saturadas; la evidencia es indirecta. El DeFi de Stellar está muy concentrado (Blend ~57% del TVL), los AMM genéricos adicionales no ganan tracción (Soroswap ~$1,2M de TVL) y SCF pide combinar piezas existentes en lugar de crear protocolos nuevos. Lo poco construido, según lo que SDF y SCF nombran, es: utilidad DeFi para los >$4.000M de RWA, capa de datos/portfolio, UX de C-addresses y smart accounts, privacidad con compliance a nivel de aplicación y comercio agéntico.

### Cited Findings
- TVL de Stellar en DefiLlama: ~$204,7M (API consultada el 10-nov-2026). — [DefiLlama API](https://api.llama.fi/v2/chains)
- Blend Pools V2: $117,65M de TVL (8-nov-2026), por debajo de su máximo de $173,14M (1-oct-2026). — [DefiLlama: Blend Pools V2](https://defillama.com/protocol/blend-pools-v2)
- Soroswap AMM: $1,17M de TVL (23-oct-2026), -5,7% en 30 días. — [DefiLlama: Soroswap AMM](https://defillama.com/protocol/soroswap-amm)
- RWA on-chain: $4.620M de valor distribuido, 84 activos, pero solo 25.359 holders. — [rwa.xyz: Stellar](https://app.rwa.xyz/networks/stellar)
- Nansen: la distribución es "the main constraint on tokenized asset adoption"; el bajo número de direcciones activas frente al volumen se atribuye a uso institucional. — [Nansen Q2 2026](https://nansen.ai/post/stellar-q2-2026-report)
- Capitalización de stablecoins en Stellar de $496M frente a $25.100M de volumen trimestral de transferencias (Q3 2026). **[secundaria, citando informe de SDF]** — [cryptobriefing, 29-oct-2026](https://cryptobriefing.com/stellar-ranks-second-active-developers/)
- SCF: "combine ecosystem pieces, not build new ones"; el Integration Track excluye "net-new protocols". — [SCF Handbook: Integration Track](https://stellar.gitbook.io/scf-handbook/scf-awards/scf-build/integration-track)
- Wallets: la wallet de referencia de SDF (Freighter) se relanzó como Varial con foco en "discovering Stellar". — [SDF blog](https://stellar.org/blog/foundation-news/freighter-is-now-varial)
- Remesas/pagos: ya cubiertos por actores grandes (MoneyGram con MGUSD para más de 60 millones de clientes; Movantis con liquidación USDC en el corredor EE. UU.–El Salvador). — [SDF Q2 2026](https://stellar.org/blog/foundation-news/q2-2026-what-stellar-was-built-for-has-arrived); [SDF press: Movantis](https://stellar.org/press/movantis-integrates-with-the-stellar-network-to-expand-its-cross-border-payments-infrastructure)
- Emisión de RWA: muy poblada por instituciones (Spiko $2.100M, Franklin Templeton $1.200M, Ondo $538,8M, Realiz $500M, Circle $353,2M, Galaxy $75,1M, WisdomTree $39,5M, Centrifuge $30M). — [rwa.xyz: Stellar](https://app.rwa.xyz/networks/stellar)
- Gap de portfolio/datos reconocido por SCF (RFP DeFi Positions API, Prices API, explorer Soroban-first). — [SCF Handbook: RFP Track](https://stellar.gitbook.io/scf-handbook/scf-awards/scf-build/rfp-track)
- Perpetuos: Noether (perp DEX) estaba en fase MVP en abril de 2026 con mainnet a 2–3 meses tras auditoría. — [Stellar dev meeting 16-abr-2026](https://developers.stellar.org/meetings/2026/04/16)

### Inferences
- **Saturado o con poco margen para un MVP** (inferencia): DEX/AMM genéricos (Aquarius, Soroswap, Phoenix y el order book nativo ya existen y los pequeños no captan liquidez), lending genérico (dominio de Blend), wallets de propósito general (Varial, Lobstr y el kit de smart accounts), apps de remesas genéricas (MoneyGram y anchors establecidos), emisión de RWA (dominada por instituciones reguladas), y las APIs de precios/posiciones tal como las definieron los RFPs de Q1.
- **Poco construido** (inferencia apoyada en lo anterior):
  1. Utilidad DeFi de RWA: $4.600M en RWA frente a ~$205M de TVL DeFi (ratio ~22:1) y solo ~25K holders; colateralización, vaults (SEP-56), distribución minorista y productos de yield sobre BENJI/Spiko/USDY/YLDS.
  2. Herramientas de riesgo y monitoreo (health factor, alertas, simulación de liquidaciones, salud de oráculos) tras el hack de oráculo de Blend y la llegada de Chainlink.
  3. UX de C-addresses y smart accounts: onramp directo, recuperación, políticas de gasto, soporte de direcciones W, modelo omnibus.
  4. Privacidad con compliance a nivel de app sobre primitivas ZK ya en mainnet (attestations, selective disclosure completa, ASPs).
  5. Comercio agéntico: servicios de pago por uso con x402/MPP, wallets de agentes con límites de gasto, marketplaces de APIs.
  6. Velocidad frente a stock de stablecoins: mucha rotación (~33x) y poca oferta retenida; faltan productos que retengan saldo (ahorro, yield, tesorería para pymes).
- El cálculo de concentración (Blend $117,65M sobre $204,7M ≈ 57%) es propio, a partir de las dos cifras de DefiLlama citadas.

### Gaps
- No se pudo abrir defillama.com/chain/stellar (HTTP 403); no hay ranking completo de protocolos ni volumen DEX verificado. Cifras de Aquarius (~$39,5M–$39,9M de TVL, atribuidas a Messari Q1 2026 y a prensa de octubre) aparecieron solo en resúmenes de búsqueda sin URL verificable.
- No se encontró un mapa de ecosistema actualizado con conteo de proyectos por categoría, ni un análisis crítico independiente y riguroso sobre saturación.
- La afirmación de prensa de que el TVL DeFi cayó 60% tras un exploit de Blend de $717K contradice las cifras posteriores de DefiLlama; no se pudo reconciliar.

## 5. Cifras clave del ecosistema e integraciones institucionales

### Takeaway
A noviembre de 2026 Stellar tiene ~$4.600M en RWA tokenizados (crecimiento de ~6x en el año), ~$420M–$500M en stablecoins, ~$205M de TVL DeFi y 3.922 developers activos mensuales (segundo puesto tras Ethereum según la cifra citada). El perfil es institucional: mucho valor y volumen, pocos holders y pocas direcciones activas diarias.

### Cited Findings
RWA:
- Valor distribuido de RWA: $4.620M (+30,48% en 30 días); valor representado: $77,58M; holders de RWA: 25.359; volumen de transferencias de RWA a 30 días: $635,14M; 84 activos. Fecha del dato: 10-nov-2026. — [rwa.xyz: Stellar](https://app.rwa.xyz/networks/stellar)
- Hitos: $785M a fin de 2025, $1.000M en enero, $2.000M en abril, $3.000M en junio de 2026. — [SDF Q1 2026](https://stellar.org/blog/foundation-news/q1-2026-execution-at-network-scale); [SDF Q2 2026](https://stellar.org/blog/foundation-news/q2-2026-what-stellar-was-built-for-has-arrived)
- $4.100M en RWA al cierre de Q3 2026 (+36% trimestral, +548% interanual). **[secundaria]** — [cryptobriefing](https://cryptobriefing.com/stellar-ranks-second-active-developers/)
- Principales emisores por valor: Spiko $2.100M (9 activos), Franklin Templeton Benji $1.200M (3), Ondo $538,8M (1), Realiz $500M (1), Circle $353,2M (2), Galaxy Digital $75,1M, WisdomTree $39,5M (16), Centrifuge $30M (4), NYALA $26,9M (12), Figure $25,3M. — [rwa.xyz: Stellar](https://app.rwa.xyz/networks/stellar)

Stablecoins:
- Capitalización de stablecoins: $421,55M (-3,46% en 30 días); holders: 495,73K (-32,37%); volumen de transferencias a 30 días: $21.360M (+98,56%). — [rwa.xyz: Stellar](https://app.rwa.xyz/networks/stellar)
- Dato alternativo: $496M de capitalización al cierre de Q3 2026. **[secundaria]** — [cryptobriefing](https://cryptobriefing.com/stellar-ranks-second-active-developers/). Las dos cifras difieren por fecha y metodología.
- Volumen de transferencias de stablecoins: $5.500M en Q1 2026, $11.400M en Q2 2026 (velocidad ~33x), $25.100M en Q3 2026 (+121% trimestral, **[secundaria]**). — [SDF Q1 2026](https://stellar.org/blog/foundation-news/q1-2026-execution-at-network-scale); [SDF Q2 2026](https://stellar.org/blog/foundation-news/q2-2026-what-stellar-was-built-for-has-arrived); [cryptobriefing](https://cryptobriefing.com/stellar-ranks-second-active-developers/)
- Stablecoins y dólares digitales nombrados en 2026: USDC (con CCTP nativo desde el 19-may-2026), EURC (pool en SPP testnet), EURAU de AllUnity (mainnet en abril de 2026), MGUSD de MoneyGram, YLDS de Figure ("first SEC-registered yield-bearing dollar product on Stellar"), USDT0 (2-sep-2026), PYUSD y USDY (citados como activos nativos para x402/MPP), y un stablecoin emitido por un banco en uso real (post del 9-sep-2026). — [SDF Q2 2026](https://stellar.org/blog/foundation-news/q2-2026-what-stellar-was-built-for-has-arrived); [SDF Q1 2026](https://stellar.org/blog/foundation-news/q1-2026-execution-at-network-scale); [SDF: USDT0](https://stellar.org/blog/foundation-news/usdt0-is-now-live-on-stellar); [dev meeting 16-abr-2026](https://developers.stellar.org/meetings/2026/04/16); [SDF: bank-issued stablecoin](https://stellar.org/blog/ecosystem/a-bank-issued-stablecoin-moves-real-money-on-stellar)
- El volumen EUR en stablecoins creció 12x interanual (Q1 2026). — [SDF Q1 2026](https://stellar.org/blog/foundation-news/q1-2026-execution-at-network-scale)

DeFi y actividad:
- TVL: ~$204,7M. — [DefiLlama API](https://api.llama.fi/v2/chains)
- Volumen total de red en Q3 2026: $33.200M (+71% trimestral). **[secundaria]** — [cryptobriefing](https://cryptobriefing.com/stellar-ranks-second-active-developers/)
- 10,7 millones de cuentas activas (Q2 2026); 10,6 millones de direcciones únicas y 22.500 millones de operaciones procesadas (Q1 2026). — [SDF Q2 2026](https://stellar.org/blog/foundation-news/q2-2026-what-stellar-was-built-for-has-arrived); [SDF Q1 2026](https://stellar.org/blog/foundation-news/q1-2026-execution-at-network-scale)
- Media diaria en Q2 2026: ~4,9M transacciones y ~63.000 direcciones activas (rango 44.000–113.000). — [Nansen Q2 2026](https://nansen.ai/post/stellar-q2-2026-report)
- Uptime >99,99%, fee medio de ~una centésima de centavo, cero incidentes de seguridad del protocolo base. — [SDF Q2 2026](https://stellar.org/blog/foundation-news/q2-2026-what-stellar-was-built-for-has-arrived)
- Validadores Tier 1: 10 tras sumar tres en Q3 2026, MoneyGram entre ellos. **[secundaria]** — [cryptobriefing](https://cryptobriefing.com/stellar-ranks-second-active-developers/)

Developers:
- 3.922 developers activos mensuales al 30-sep-2026 (+125% interanual), segundo puesto tras Ethereum; 475 developers a tiempo completo de media. **[secundaria]** — [cryptobriefing](https://cryptobriefing.com/stellar-ranks-second-active-developers/)
- 2.968 developers activos mensuales al 30-jun-2026 según Electric Capital. — [SDF Q2 2026](https://stellar.org/blog/foundation-news/q2-2026-what-stellar-was-built-for-has-arrived)

Integraciones institucionales (2026):
- DTCC seleccionó Stellar como una de las primeras blockchains públicas para su DTC Tokenization Service (DTCC supervisa más de $114 billones en mercados de capitales de EE. UU.). — [SDF Q2 2026](https://stellar.org/blog/foundation-news/q2-2026-what-stellar-was-built-for-has-arrived)
- MoneyGram: MGUSD, más de 60 millones de clientes, 475.000+ puntos de efectivo, validador Tier 1. — [SDF Q2 2026](https://stellar.org/blog/foundation-news/q2-2026-what-stellar-was-built-for-has-arrived); [Nansen Q2 2026](https://nansen.ai/post/stellar-q2-2026-report)
- Franklin Templeton (BENJI; Tokinvest lo distribuye en Medio Oriente), U.S. Bank, Amundi, Société Générale, AllUnity, Kenanga (primeros money market funds tokenizados de Malasia), Marketnode (SGX y Temasek), Etherfuse, TopNod de Ant Digital, Bitkub, Cashlink, Matrixdock (oro XAUm), Centrifuge, Janus Henderson. — [SDF Q1 2026](https://stellar.org/blog/foundation-news/q1-2026-execution-at-network-scale); [SDF Q2 2026](https://stellar.org/blog/foundation-news/q2-2026-what-stellar-was-built-for-has-arrived)
- Bermuda eligió Stellar para su plan de convertirse en la primera economía nacional totalmente on-chain. — [SDF Q2 2026](https://stellar.org/blog/foundation-news/q2-2026-what-stellar-was-built-for-has-arrived)
- Archax anunció €GOVY (letras del tesoro tokenizadas en euros) en Meridian 2026. — [SDF press: Archax](https://stellar.org/press/archax-announces-eurgovy-on-the-stellar-network-bringing-its-perpetual-tokenised-government-bill-product-to-the-eurozone)
- Spiko: el EU T-Bill pasó de ~$520M a ~$970M en Q1 2026, mayoritariamente en Stellar. — [SDF Q1 2026](https://stellar.org/blog/foundation-news/q1-2026-execution-at-network-scale)

### Inferences
- Relación RWA/TVL de ~22:1 y solo ~25K holders de RWA: el valor está "aparcado" en pocos balances institucionales y casi no circula por DeFi.
- La caída del 32% en holders de stablecoins en 30 días junto con el volumen duplicándose sugiere que el flujo se concentra en menos actores, más grandes (pagos B2B, tesorería); la base minorista no crece al mismo ritmo.
- ~63K direcciones activas diarias frente a 10,7M de cuentas indica que la adquisición y retención de usuarios finales es una carencia real para apps de consumo.

### Gaps
- No se encontraron en fuentes de 2026 datos de oferta por stablecoin (USDC, EURC, PYUSD, USDT0) ni detalles de integración de **PayPal (PYUSD)** o **Visa** en Stellar; PYUSD solo aparece citado como activo nativo en las notas de x402. Lo que se sepa de PayPal/Visa de 2025 o antes debe tratarse como posiblemente desactualizado.
- La tabla de rwa.xyz no etiqueta si los valores por plataforma son "distributed" o "represented"; los porcentajes de cuota de mercado requieren login.
- No se consultaron Artemis ni Messari directamente; no hay cifra verificada de volumen DEX ni de usuarios de Soroban frente a operaciones clásicas.
- Las cifras de Q3 2026 provienen de una única fuente secundaria que cita el informe de SDF del 19-oct-2026.

## 6. Estándares relevantes (SEPs / CAPs) y sus carencias

### Takeaway
El stack de anchors (SEP-1, 6, 10, 12, 24, 31) sigue siendo la base para fiat on/off-ramp y pagos transfronterizos, y SEP-41 la interfaz de tokens en Soroban. Las carencias están en la frontera entre el mundo clásico y el de contratos: autenticación duplicada (SEP-10 frente a SEP-45), tokens regulados aún en borrador (SEP-57), ausencia de un estándar de smart wallet con nombre propio y la llegada de las direcciones W.

### Cited Findings
- Estándares "high-value" para developers de apps según el skill oficial: contratos y tokens (SEP-41 interfaz de token Soroban, SEP-46 metadata en Wasm, SEP-48 especificación de interfaz, SEP-49 guía de contratos actualizables, SEP-50 NFT, SEP-55 verificación de build, SEP-56 productos tipo vault, **SEP-57 tokens regulados T-REX, en Draft**, SEP-8 activos clásicos regulados con approval server); autenticación y metadata (SEP-10, SEP-23, SEP-1 `stellar.toml`); anchors y fiat (SEP-6, SEP-24, SEP-31, SEP-12 KYC). — [skills.stellar.org standards](https://skills.stellar.org/skills/standards/SKILL.md)
- Mapeo recomendado: tokens fungibles = SEP-41 (más SEP-8 o SEP-57 si son regulados); contratos actualizables = SEP-49 más CAP-58; flujos de smart wallet = SEP-10 más CAP-51; anchors fiat = SEP-6, 24, 31 y 12. La página se autodefine como "routing map, not a source of final governance/status truth". — [skills.stellar.org standards](https://skills.stellar.org/skills/standards/SKILL.md)
- Para smart wallets la página no nombra ningún estándar; solo indica "align wallet UX and signing payloads with current SDK guidance". — [skills.stellar.org standards](https://skills.stellar.org/skills/standards/SKILL.md)
- SEP-45 (Web Authentication for Contract Accounts) permite a smart wallets autenticarse ante anchors probando control de una cuenta C...; SEP-10 cubre G... y M...; para soportar todos los tipos hay que implementar ambos; SEP-45 exige Stellar RPC para simular transacciones; el endpoint se descubre vía `stellar.toml`. — [Anchor Platform: SEP-45](https://developers.stellar.org/docs/platforms/anchor-platform/sep-guide/sep45)
- El Stellar Disbursement Platform (SDP) soporta SEP-45 para que wallets de contrato (C-addresses) se autentiquen e interactúen con la plataforma. — [deepwiki: SDP backend, SEP-45](https://deepwiki.com/stellar/stellar-disbursement-platform-backend/5.4-sep-45-smart-contract-authentication)
- Anchor Platform es el producto de SDF para implementar los SEPs de anchor. — [developers.stellar.org: Anchor Platform](https://developers.stellar.org/docs/platforms/anchor-platform)
- CAP-73 (Protocol 26) permite que el SAC cree balances de cuentas G; CAP-79 añade conversiones strkey de direcciones muxed; CAP-84 (Protocol 30) introduce direcciones de contrato muxed "W" que wallets, explorers y ramps deben soportar. — [software versions](https://developers.stellar.org/docs/networks/software-versions); [SDF: Introducing Bell](https://stellar.org/blog/developers/introducing-bell-protocol-30-on-stellar)
- Estándar de token confidencial compatible con ERC-7984 en desarrollo con OpenZeppelin (no finalizado). — [SDF Q1 2026](https://stellar.org/blog/foundation-news/q1-2026-execution-at-network-scale)
- CAP-77 (freeze gobernado por consenso) se presenta como el mecanismo de congelación de activos comprometidos por voto de validadores. — [SDF Q1 2026](https://stellar.org/blog/foundation-news/q1-2026-execution-at-network-scale); [SDF Q2 2026](https://stellar.org/blog/foundation-news/q2-2026-what-stellar-was-built-for-has-arrived)
- Estándares de pago agéntico: x402 y MPP con identificador de red CAIP-2 (`stellar:pubnet` para mainnet). — [docs: Agentic Payments](https://developers.stellar.org/docs/build/agentic-payments)
- Existe un issue abierto en stellar-protocol (#1928) que propone cambiar cómo las respuestas `getAddress` de las wallets manejan C-addresses. — [GitHub (mirror)](https://github.ddaodan.workers.dev/stellar/stellar-protocol/issues/1928)

### Inferences
- Carencias concretas en la capa de estándares, deducidas de lo anterior:
  1. **Onboarding fiat a smart accounts**: los anchors deben implementar SEP-45 además de SEP-10 y operar RPC; es probable que muchos anchors solo soporten cuentas G, de ahí el RFP de "C-Address Tooling & Onboarding".
  2. **Tokens regulados en Soroban**: SEP-57 en borrador implica que emisores de RWA carecen de un estándar estable de compliance on-chain (allowlists, transfer rules), lo que dificulta la composabilidad RWA–DeFi.
  3. **KYC reutilizable**: SEP-12 intercambia datos de KYC anchor por anchor; con BN254/Poseidon en mainnet, una credencial de KYC verificable con ZK y reutilizable entre anchors es técnicamente viable, y no se encontró un estándar que la cubra.
  4. **Vaults (SEP-56)** como puente estándar para envolver RWA con yield y usarlos en Blend u otros protocolos.
  5. **Direcciones W**: necesidad inmediata de soporte en SDKs, wallets, explorers y ramps a partir del voto del 23-nov-2026.
  6. **Políticas de gasto para agentes**: x402/MPP dependen de smart accounts con límites; no se encontró un estándar SEP de permisos o session keys.
- SDP (pagos masivos) con soporte SEP-45 abre el caso de desembolsos (ayuda humanitaria, nómina) directamente a wallets con passkey sin que el receptor gestione seed phrases ni XLM.

### Gaps
- No se verificó el estado actual (Draft/Active/Final) de cada SEP en el repositorio stellar-protocol; el skill oficial solo marca SEP-57 como Draft.
- No se encontró el número de anchors que soportan SEP-45 ni una lista de exchanges que aceptan depósitos/retiros a C-addresses.
- No se encontraron datos de 2026 sobre adopción de SEP-31 ni de SEP-38 (quotes); SEP-38 no aparece en el mapa oficial consultado.
- No se encontró información de 2026 sobre limitaciones concretas del Stellar Disbursement Platform (países, wallets soportadas, costes) más allá del soporte SEP-45.
