<div align="center">

<a href="./README.md">
  <img src="https://img.shields.io/badge/🇺🇸_Read_in_English-Click_here-4F8CFF?style=for-the-badge&labelColor=0d1117" alt="English version" />
</a>

<br />
<br />

<img src="https://readme-typing-svg.herokuapp.com/?font=JetBrains+Mono&size=42&duration=3500&pause=900&color=4F8CFF&center=true&vCenter=true&width=760&height=70&lines=SignLink+%F0%9F%A4%9F;L%C3%ADngua+de+sinais+em+tempo+real;Vis%C3%A3o+computacional+%2B+avatar+3D" alt="SignLink" />

<h3>🤟 Uma plataforma colaborativa para traduzir e catalogar a Língua Brasileira de Sinais (Libras)</h3>

<p>
  <em>Visão computacional + avatar 3D VRM + comunidade.</em><br/>
  <em>Acessibilidade, código aberto e impacto social — feito por estudantes para o Brasil e o mundo.</em>
</p>

<br />

<!-- Badges institucionais -->
<p>
  <img src="https://img.shields.io/badge/status-em%20desenvolvimento-yellow?style=flat-square" alt="status" />
  <img src="https://img.shields.io/badge/versão-0.6.0--alpha-blue?style=flat-square" alt="versão" />
  <img src="https://img.shields.io/badge/licença-MIT-green?style=flat-square" alt="licença" />
  <img src="https://img.shields.io/badge/IFSP-Birigui-red?style=flat-square" alt="IFSP" />
  <img src="https://img.shields.io/badge/PRs-bem--vindos-brightgreen?style=flat-square" alt="PRs bem-vindos" />
  <img src="https://img.shields.io/badge/feito%20com-%E2%9D%A4-ff69b4?style=flat-square" alt="feito com amor" />
</p>

<!-- Badges técnicas -->
<p>
  <img src="https://img.shields.io/badge/MediaPipe-0097A7?style=flat-square&logo=google&logoColor=white" alt="MediaPipe" />
  <img src="https://img.shields.io/badge/Kalidokit-FF6B6B?style=flat-square" alt="Kalidokit" />
  <img src="https://img.shields.io/badge/VRM-7C3AED?style=flat-square" alt="VRM" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=three.js&logoColor=white" alt="Three.js" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black" alt="Firebase" />
  <img src="https://img.shields.io/badge/Firestore-FFA000?style=flat-square&logo=firebase&logoColor=white" alt="Firestore" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3" />
</p>

<br />

<!-- Linha de destaque -->
<table>
  <tr>
    <td align="center" width="33%">
      <h3>👁️ Visão</h3>
      <sub>Rastreamento de mãos, rosto e pose<br/>com MediaPipe</sub>
    </td>
    <td align="center" width="33%">
      <h3>🧮 Lógica</h3>
      <sub>Landmarks → rig VRM<br/>via Kalidokit</sub>
    </td>
    <td align="center" width="33%">
      <h3>🕺 Avatar</h3>
      <sub>Reprodução 3D fiel<br/>com .vrm no Three.js</sub>
    </td>
  </tr>
</table>

</div>

---

## 📑 Sumário

1. [✨ Visão geral](#-visão-geral)
2. [🎯 Por que o SignLink?](#-por-que-o-signlink)
3. [🚀 Principais funcionalidades](#-principais-funcionalidades)
4. [🧠 Como funciona — pipeline técnico](#-como-funciona--pipeline-técnico)
5. [🏗️ Arquitetura](#️-arquitetura)
6. [🧰 Stack de tecnologias](#-stack-de-tecnologias)
7. [📐 A matemática por trás do avatar](#-a-matemática-por-trás-do-avatar)
8. [🗺️ Roadmap](#️-roadmap)
9. [👥 O time](#-o-time)
10. [🏫 Instituição](#-instituição)
11. [📜 Licença](#-licença)

---

## ✨ Visão geral

> O **SignLink** é uma plataforma web que traduz a Língua Brasileira de Sinais (Libras) em tempo real através da webcam do usuário, combinando **visão computacional** (MediaPipe), uma **ponte de rigging** (Kalidokit) e um **avatar 3D VRM** (Three.js). Também funciona como um **dicionário colaborativo**, permitindo que qualquer pessoa contribua cadastrando novos sinais — democratizando o acesso à Libras.

<div align="center">

```
 👋  Mão em quadro  ─►  🧠 MediaPipe  ─►  🔗 Kalidokit  ─►  🕺 Avatar VRM  ─►  💬 Tradução
```

</div>

---

## 🎯 Por que o SignLink?

| Problema | Como o SignLink ajuda |
| :--- | :--- |
| 🧏 Mais de **10 milhões** de brasileiros são surdos ou têm deficiência auditiva. | Tradução visual em tempo real, sem necessidade de intérprete humano para interações do dia a dia. |
| 📚 Os recursos de aprendizado de Libras são fragmentados e estáticos. | Um dicionário **colaborativo**, indexado e pesquisável, alimentado pela comunidade. |
| 💸 Soluções comerciais frequentemente exigem hardware caro e configurações complexas. | Arquitetura baseada na web: Acessível pela maioria dos navegadores padrão, eliminando a necessidade de equipamentos especializados e democratizando o acesso. |
| 🎓 Existem poucas ferramentas pedagógicas interativas. | Um avatar 3D que **reproduz** os sinais cadastrados — perfeito para quem aprende visualmente. |

---

## 🚀 Principais funcionalidades

- 🎥 **Captura de webcam em tempo real** via `getUserMedia`, com renderização sem corte da imagem da câmera. ✅
- ✋✋ **Rastreamento de duas mãos** simultaneamente (`maxNumHands: 2`) através do MediaPipe Hands. ✅
- 🙂 **Rastreamento de rosto e cabeça/pescoço** para espelhamento expressivo do avatar. ✅
- 💪 **Estimativa de pose** de braços e parte superior do corpo controlando o rig VRM. ✅
- 🔗 **Ponte Kalidokit** que converte landmarks do MediaPipe em rotações compatíveis com VRM. ✅
- 🕺 **Avatar 3D VRM** espelhando o usuário em tempo real (≈90% do rig da parte superior concluído). 🟡
- 🔍 **Busca textual** no dicionário de sinais cadastrados. ✅
- 📹 **Gravação de sinais** através do MediaPipe para capturar e salvar novos sinais a partir da webcam. ✅
- 👤 **Perfis de usuário** com conquistas, sinais salvos e histórico de contribuições. 🟡
- 📖 **Aba "Sobre o projeto" / histórico** descrevendo motivação, time e trajetória. 🟡
- ✅ **Fluxo de aprovação pela comunidade** para manter as entradas com alta qualidade. 🟡
- 🔐 **Autenticação** via Firebase, com perfis de contribuidores. ✅
- ♿ **Acessibilidade em primeiro lugar**: contraste WCAG AA, navegação por teclado, rótulos ARIA. 🟡

> Legenda: ✅ concluído · 🟡 em andamento · ⏳ planejado

---

## 🧠 Como funciona — pipeline técnico

```mermaid
flowchart LR
    A[📷 Webcam<br/>getUserMedia] --> B[🧩 MediaPipe<br/>Mãos + Rosto + Pose]
    B --> C[🗺️ Landmarks<br/>mãos, rosto, corpo]
    C --> D[🔗 Kalidokit<br/>Landmarks → rig VRM]
    D --> E[🦴 Avatar VRM<br/>Three.js]
    E --> F[🕺 Render 3D<br/>WebGL]
    C --> G[💾 Firestore<br/>Banco de sinais]
    G --> H[🔍 Busca / Correspondência<br/>Dicionário]
    H --> I[💬 Tradução textual]
```

### Pipeline em 5 etapas

1. **Captura** — o quadro da webcam é desenhado em um `<canvas>` preservando a proporção (sem corte).
2. **Inferência** — o MediaPipe retorna landmarks das mãos (até 2), do rosto e da pose da parte superior do corpo.
3. **Normalização** — os landmarks são reposicionados em relação às articulações de referência e reescalados.
4. **Rigging com Kalidokit** — o Kalidokit converte os landmarks do MediaPipe nos valores de rotação/blendshape que um modelo `.vrm` espera, evitando a matemática manual de quatérnios.
5. **Aplicação do rig** — o Three.js aplica as rotações de ossos e os morph targets resultantes ao avatar VRM a cada quadro.

---

## 🏗️ Arquitetura

```mermaid
graph TB
    subgraph Client["🌐 Cliente (navegador)"]
        UI[Interface do Usuário<br/>HTML + CSS]
        VIS[Módulo de Visão<br/>MediaPipe]
        RIG[Ponte de Rigging<br/>Kalidokit]
        AVT[Módulo de Avatar<br/>Three.js + VRM]
        STATE[Gerenciamento de<br/>Estado e UI]
    end

    subgraph Backend["☁️ Backend serverless"]
        AUTH[Firebase Auth]
        DB[(Firestore<br/>Dicionário de sinais)]
        STG[Cloud Storage<br/>Vídeos / Mídia]
        RULES[Regras de<br/>Segurança]
    end

    UI <--> STATE
    STATE <--> VIS
    STATE <--> AVT
    VIS -.landmarks.-> RIG
    RIG -.rotações VRM.-> AVT
    STATE <--> AUTH
    STATE <--> DB
    STATE <--> STG
    DB --> RULES
    STG --> RULES

    style Client fill:#1f2937,stroke:#4F8CFF,color:#fff
    style Backend fill:#1f2937,stroke:#FFCA28,color:#fff
```

### Modularização (princípio de design)

A arquitetura do cliente segue uma separação rígida de responsabilidades:

| Módulo | Responsabilidade | Por que é isolado? |
| :--- | :--- | :--- |
| 👁️ **Visão** | Captura de webcam + MediaPipe | Pode ser trocado (ex.: outro modelo) sem mexer na UI. |
| 🔗 **Rigging** | Conversão landmark → VRM do Kalidokit | Isola a ponte de matemática/formato tanto da visão quanto da renderização. |
| 🕺 **Avatar** | Cena Three.js, rig VRM, rotações | A renderização 3D tem seu próprio loop e perfil de custo. |
| 🎨 **UI** | DOM, eventos, formulários, busca | Mantém a interface previsível e testável. |
| 🔌 **Estado** | Conecta os módulos via eventos | Ponto único de integração — evita acoplamento. |

---

## 🧰 Stack de tecnologias

<div align="center">

### Front-end
![JavaScript](https://img.shields.io/badge/JavaScript-ES2022-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

### Visão computacional
![MediaPipe](https://img.shields.io/badge/MediaPipe-0097A7?style=for-the-badge&logo=google&logoColor=white)
![WebGL](https://img.shields.io/badge/WebGL-990000?style=for-the-badge&logo=webgl&logoColor=white)

### Ponte de rigging
![Kalidokit](https://img.shields.io/badge/Kalidokit-FF6B6B?style=for-the-badge)

### 3D & animação
![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white)
![VRM](https://img.shields.io/badge/VRM-7C3AED?style=for-the-badge)
![GLTF](https://img.shields.io/badge/glTF-87C540?style=for-the-badge)

### Back-end / infraestrutura
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![Firestore](https://img.shields.io/badge/Firestore-FFA000?style=for-the-badge&logo=firebase&logoColor=white)

### Ferramentas
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)

</div>

---

## 📐 A matemática por trás do avatar

Controlar um rig humanoide a partir de uma câmera 2D exige transformar cada conjunto de landmarks na rotação que um osso deve ter. Em vez de calcular manualmente os quatérnios de cada articulação, o SignLink delega essa etapa ao **[Kalidokit](https://github.com/yeemachine/kalidokit)**, que consome os landmarks de mãos / rosto / pose do MediaPipe e emite exatamente os dados de rotação e blendshape que um humanoide **VRM** espera.

Em resumo, a conversão ainda segue a receita clássica por osso:

```
v        = normalize(p_end - p_start)
axis     = cross(v_rest, v)
angle    = acos(dot(v_rest, v))
rotation = quaternionFromAxisAngle(axis, angle)
```

…mas o Kalidokit cuida da suavização, das restrições biomecânicas e das convenções de eixos específicas do VRM para nós. A saída é aplicada diretamente aos ossos do humanoide VRM a cada quadro via Three.js.

> 💡 **Por que VRM + Kalidokit?**
> O VRM padroniza rigs humanoides entre avatares, e o Kalidokit nos dá um mapeamento testado em produção do MediaPipe para esse rig — permitindo que o time foque na lógica específica de Libras em vez de reinventar a cinemática inversa.

---

## 🗺️ Roadmap

```mermaid
gantt
    title Cronograma SignLink 2026
    dateFormat YYYY-MM-DD
    section Fase 1 — Visão central
    Detecção de uma mão           :done,    f1a, 2026-02-01, 30d
    Modularização do código       :done,    f1b, 2026-03-01, 20d
    Detecção de duas mãos         :done,    f1c, 2026-03-15, 25d
    Correção do corte da câmera   :done,    f1d, 2026-03-20, 15d
    section Fase 2 — Rigging
    Integração do Kalidokit       :done,    f2a, 2026-04-01, 25d
    Avatar VRM (mãos/braços/rosto) :active,  f2b, 2026-04-15, 40d
    section Fase 3 — Produto
    Funcionalidade de gravação    :done,    f3b, 2026-04-15, 35d
    Sistema de usuário e conquistas :active, f3a, 2026-05-10, 35d
    Aba "Sobre o projeto"         :active,  f3c, 2026-05-15, 25d
    Dicionário colaborativo       :         f3d, 2026-07-15, 30d
    section Fase 4 — Lançamento
    Beta fechado                  :         f4a, 2026-09-01, 30d
    Lançamento público            :milestone, f4b, 2026-11-01, 0d
```

| Marco | Status | Meta |
| :--- | :---: | :--- |
| Detecção de uma mão | ✅ Concluído | — |
| Modularização (`vision.js`, `avatar.js`, `ui.js`) | ✅ Concluído | — |
| Rastreamento de duas mãos (`maxNumHands: 2`) | ✅ Concluído | — |
| Correção do corte da câmera | ✅ Concluído | — |
| **Integração do Kalidokit (MediaPipe → VRM)** | ✅ Concluído | — |
| **Avatar VRM — mãos, braços, cabeça/pescoço/rosto** | 🟡 ~90% concluído | Mai/2026 |
| **Gravação de sinais pela webcam** | ✅ Concluído | — |
| **Sistema de usuário (perfil, conquistas, dados salvos)** | 🟡 Em andamento | Jun/2026 |
| **Aba "Sobre o projeto" / histórico** | 🟡 Em andamento | Jul/2026 |
| CRUD colaborativo de sinais | ⏳ Planejado | Jul/2026 |
| Fluxo de aprovação pela comunidade | 🟡 Em andamento | Ago/2026 |
| Beta fechado | ⏳ Planejado | Set/2026 |
| Lançamento público | 🎯 Objetivo | Nov/2026 |

---

## 👥 O time

<div align="center">

<table>
  <tr>
    <td align="center" width="25%">
      <img src="https://avatars.githubusercontent.com/u/0?v=4&s=120" width="100" style="border-radius: 50%;" alt="avatar" /><br/>
      <strong>Gabriel Feltrin Emilio</strong><br/>
      <sub>🧭 Tech Lead &<br/>Arquitetura de Software</sub>
    </td>
    <td align="center" width="25%">
      <img src="https://avatars.githubusercontent.com/u/0?v=4&s=120" width="100" style="border-radius: 50%;" alt="avatar" /><br/>
      <strong>Arthur Leite Ferreira</strong><br/>
      <sub>🛠️ Engenheiro de<br/>Dados e Back-end</sub>
    </td>
    <td align="center" width="25%">
      <img src="https://avatars.githubusercontent.com/u/0?v=4&s=120" width="100" style="border-radius: 50%;" alt="avatar" /><br/>
      <strong>João Vitor Santos Silva</strong><br/>
      <sub>🛠️ Engenheiro de<br/>Dados e Back-end</sub>
    </td>
    <td align="center" width="25%">
      <img src="https://avatars.githubusercontent.com/u/0?v=4&s=120" width="100" style="border-radius: 50%;" alt="avatar" /><br/>
      <strong>Gustavo Ferreira Santos</strong><br/>
      <sub>🎨 Front-end &<br/>Designer UX/UI</sub>
    </td>
  </tr>
</table>

</div>

---

## 🏫 Instituição

<div align="center">

**Instituto Federal de São Paulo — Campus Birigui**

🎓 Engenharia de Computação | 📍 Birigui, SP — Brasil | 📅 2026

</div>

---

## 📜 Licença

Distribuído sob a licença **MIT**. Veja `LICENSE` para mais detalhes.

---

<div align="center">

<sub>Feito com 🤟 por estudantes do IFSP — porque acessibilidade é um direito, não um favor.</sub>

<br /><br />

<a href="./README.md">
  <img src="https://img.shields.io/badge/🇺🇸_Read_in_English-Open-4F8CFF?style=for-the-badge&labelColor=0d1117" alt="English version" />
</a>

</div>
