<p align="center">
  <img src="https://raw.githubusercontent.com/h4ckf0r0day/obscura/main/assets/icon.png" alt="Obscura" width="80" />
</p>
<h2 align="center">Obscura</h2>
<p align="center">
  <a href="https://trendshift.io/repositories/25837?utm_source=trendshift-badge&amp;utm_medium=badge&amp;utm_campaign=badge-trendshift-25837" target="_blank" rel="noopener noreferrer"><img src="https://trendshift.io/api/badge/trendshift/repositories/25837/daily" alt="h4ckf0r0day%2Fobscura | Trendshift" width="250" height="55"/></a>
</p>
<p align="center">
  <a href="https://github.com/h4ckf0r0day/obscura/tree/main/docs"><img src="https://img.shields.io/badge/Docs-1a1a1a?style=for-the-badge" alt="Documentação" /></a>
  <a href="https://obscura.sh"><img src="https://img.shields.io/badge/Website-1a1a1a?style=for-the-badge&logoColor=white" alt="Website" /></a>
  <a href="https://x.com/obscura_sh" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/TWITTER%20%2F%20X-1a1a1a?style=for-the-badge&logo=x&logoColor=white" alt="Obscura no Twitter/X" /></a>
  <a href="https://cal.com/obscura/quick-chat"><img src="https://img.shields.io/badge/Agendar_Demo-1a1a1a?style=for-the-badge&logo=googlecalendar&logoColor=white" alt="Agendar uma demonstração" /></a>
  <a href="https://github.com/h4ckf0r0day/obscura/releases"><img src="https://img.shields.io/badge/Releases-1a1a1a?style=for-the-badge&logo=github&logoColor=white" alt="Releases" /></a>
</p>
<p align="center">
  <strong>O navegador headless open source para agentes de IA e web scraping.</strong><br>
  Leve, furtivo e construído em Rust.
</p>
<h3 align="center">A renderização nativa chegou. Sem necessidade de Chromium. 🎉 </h3>
<p align="center">
  Capture screenshots, faça screencast de páginas ao vivo e exporte PDFs diretamente com o Obscura.
</p>

---

O Obscura é um motor de navegador headless escrito em Rust, criado para web scraping e automação de agentes de IA. Ele executa JavaScript real via V8, suporta o Chrome DevTools Protocol e funciona como substituto direto do Chrome headless com Puppeteer e Playwright.

### Por que Obscura em vez do Chrome headless?

| Métrica          | Obscura        | Chrome Headless |
|------------------|----------------|-----------------|
| Memória          | **30 MB**      | 200+ MB         |
| Tamanho do binário | **~70 MiB**  | 300+ MB         |
| Anti-detecção    | **Integrada**  | Nenhuma         |
| Carregamento de página | **85 ms** | ~500 ms        |
| Inicialização    | **Instantânea** | ~2s            |
| Puppeteer        | **Sim**        | Sim             |
| Playwright       | **Sim**        | Sim             |

<table>
  <tr>
    <td width="90" align="center">
      <a href="https://blog.cloudflare.com/kitesurf/">
        <img
          src="https://cdn.simpleicons.org/cloudflare/F38020"
          alt="Cloudflare"
          width="54"
        />
      </a>
    </td>
    <td>
      <strong>O Obscura inspirou o primeiro protótipo do Kitesurf, da Cloudflare</strong>
      <br>
      A Cloudflare começou portando o Obscura para o Workers enquanto desenvolvia seu
      novo navegador voltado para agentes.
      <br>
      <a href="https://blog.cloudflare.com/kitesurf/">
        Leia a história de engenharia da Cloudflare →
      </a>
    </td>
  </tr>
</table>

## Obscura Cloud

Estamos trabalhando no **Obscura Cloud**, a versão hospedada, com infraestrutura gerenciada, proxies residenciais e suporte dedicado. Para quem quer o motor sem precisar operá-lo por conta própria.

O motor open source continua sob Apache-2.0, com todos os recursos. Sem bloqueio de funcionalidades, nunca.

**[Entre na lista de espera →](https://tally.so/r/gDWzdD)**
<br>
**[📅 Agende uma demonstração →](https://cal.com/obscura/quick-chat)**

### Apoio ao Open Source

<a href="https://vercel.com/open-source-program">
  <img alt="Vercel OSS Program" src="https://vercel.com/oss/program-badge-2026.svg" />
</a>

## Patrocinadores

O **Obscura** é apoiado por organizações que nos ajudam a construir uma infraestrutura de navegador open source independente.

Quer patrocinar? Envie um e-mail para [hello@obscura.sh](mailto:hello@obscura.sh).

<table>
   <tr>
    <td width="200" align="center" valign="middle">
      <a href="https://go.nodemaven.com/obscurareadmeoctober" target="_blank">
        <img alt="NodeMaven" src="assets/sponsors/nodemaven4.png" width="180"/>
      </a>
    </td>
    <td valign="middle">
      <a href="https://go.nodemaven.com/obscurareadmeoctober" target="_blank"><b>NodeMaven</b></a>: O provedor de proxies mais eficiente para Web Scraping e Automação, com IPs da mais alta qualidade do mercado.<br><br>
      <b>Por que <a href="https://go.nodemaven.com/obscurareadmeoctober" target="_blank">NodeMaven</a>?</b><br>
      Segmentação por CEP (ZIP)<br>
      99,9% de uptime<br>
      Filtragem de IPs: todos os proxies têm fraud score &lt;97%<br>
      Sem necessidade de KYC<br>
      Confira o novo GitHub da NodeMaven para mais soluções de web scraping e automação - https://github.com/nodemaven<br>
      Ferramentas gratuitas exclusivas: Proxy Bandwidth Checker, Meta Tag Checker, IP Lookup e outras!<br><br>
      🎁 <b>Códigos especiais para usuários do Obscura:</b><br>
      <b>OBSCURA35</b> - 35% de desconto em Proxies Móveis e Residenciais<br>
      <b>OBSCURA40</b> - 40% de desconto em Proxies ISP (Estáticos) <br>
      <b>OBSCURA2X</b> - 2X de tráfego na Black Friday
    </td>
</table>

## Instalação

### Download

Baixe o binário mais recente em [Releases](https://github.com/h4ckf0r0day/obscura/releases):

```bash
# Linux x86_64
curl -LO https://github.com/h4ckf0r0day/obscura/releases/latest/download/obscura-x86_64-linux.tar.gz
tar xzf obscura-x86_64-linux.tar.gz
./obscura fetch https://example.com --eval "document.title"

# Linux ARM64 (aarch64)
curl -LO https://github.com/h4ckf0r0day/obscura/releases/latest/download/obscura-aarch64-linux.tar.gz
tar xzf obscura-aarch64-linux.tar.gz

# NixOS
nix-env -iA nixpkgs.obscura

# macOS Apple Silicon
curl -LO https://github.com/h4ckf0r0day/obscura/releases/latest/download/obscura-aarch64-macos.tar.gz
tar xzf obscura-aarch64-macos.tar.gz

# macOS Intel
curl -LO https://github.com/h4ckf0r0day/obscura/releases/latest/download/obscura-x86_64-macos.tar.gz
tar xzf obscura-x86_64-macos.tar.gz
```

### Windows

Somente Windows x86_64 (sem build de 32 bits).

Baixe `obscura-x86_64-windows.zip` em
[Releases](https://github.com/h4ckf0r0day/obscura/releases),
extraia e adicione a pasta ao seu PATH. Mantenha as DLLs de runtime incluídas ao lado
dos dois executáveis. Não são necessárias ferramentas de build C++.

Como alternativa, com o [Scoop](https://scoop.sh/) instalado:

```powershell
# Instalação direta pelo manifesto (disponível assim que esta mudança for mesclada na main):
scoop install https://raw.githubusercontent.com/h4ckf0r0day/obscura/main/scoop/obscura.json
```

Sem Chrome, sem Node.js, sem dependências. Os arquivos de release incluem tanto
`obscura` quanto `obscura-worker`: em instalações manuais via zip, mantenha ambos no
mesmo diretório para o comando `scrape` paralelo; o Scoop cuida do posicionamento
automaticamente (ambos os binários ficam no diretório do app, com shims
no PATH).

| Sufixo do arquivo | Renderização | Transporte stealth |
|-------------------|--------------|--------------------|
| nenhum | Sim | Não |
| `-stealth` | Sim | Sim |
| `-no-render` | Não | Não |
| `-no-render-stealth` | Não | Sim |

A instalação via Scoop baixa a variante padrão (com renderização, sem stealth). Para
usar stealth no Windows, baixe manualmente o arquivo `-stealth`.

Os builds de release para Linux têm como alvo o Ubuntu 22.04, para que o binário baixado continue
utilizável em servidores LTS comuns com glibc 2.35+.

### Docker

```bash
export OBSCURA_CDP_TOKEN="$(openssl rand -hex 32)"
docker run -d --name obscura -p 127.0.0.1:9222:9222 \
  -e OBSCURA_CDP_TOKEN \
  h4ckf0r0day/obscura
```

Imagem no [Docker Hub](https://hub.docker.com/r/h4ckf0r0day/obscura). Build multi-stage sobre `distroless/cc:nonroot` — sem shell, sem gerenciador de pacotes, executa como uid 65532, ~57 MB compactada. Um `--storage-dir` montado deve ter permissão de escrita para o uid 65532. Publique no loopback do host, como acima; `-p 9222:9222` expõe a porta em todas as interfaces.

### Compilar a partir do código-fonte

```bash
git clone https://github.com/h4ckf0r0day/obscura.git
cd obscura

# Com renderização
cargo build --release -p obscura-cli --bins --features render

# Com renderização e stealth
cargo build --release -p obscura-cli --bins --features render,stealth

# Sem renderização
cargo build --release -p obscura-cli --bins --no-default-features

# Sem renderização, com stealth
cargo build --release -p obscura-cli --bins --no-default-features --features stealth
```

Requer o Rust estável mais recente ([rustup.rs](https://rustup.rs)). O primeiro build leva ~5 min (o V8 é compilado a partir do código-fonte e fica em cache depois).
O build com stealth também compila o BoringSSL e gera bindings, portanto precisa de
CMake, Clang e as bibliotecas de desenvolvimento libclang/LLVM. No Ubuntu/Debian:

```bash
sudo apt-get install build-essential cmake clang libclang-dev llvm-dev
```

O build com renderização usa rustls. O build com renderização e stealth usa
wreq/BoringSSL e, por isso, precisa das ferramentas de build adicionais acima.

## Início Rápido

### Buscar uma página

```bash
# Obter o título da página
obscura fetch https://example.com --eval "document.title"

# Extrair todos os links
obscura fetch https://example.com --dump links

# Renderizar JavaScript e exportar o HTML
obscura fetch https://news.ycombinator.com --dump html

# Gravar a saída do dump ou do eval em um arquivo
obscura fetch https://example.com --dump text --output page.txt

# Transmitir o corpo bruto da resposta sem alterações (seguro para binários; ignora a camada JS/DOM).
# Use para imagens, JSON, JS, CSS ou qualquer recurso que não seja HTML.
obscura fetch https://picsum.photos/200/300 --dump original > photo.jpg

# Listar a URL de cada sub-recurso que a página buscaria (NDJSON; um registro por recurso)
obscura fetch https://example.com --dump assets

# Buscar através de um proxy HTTP ou SOCKS
obscura --proxy socks5://127.0.0.1:1080 fetch https://example.com --dump text

# Aguardar conteúdo dinâmico
obscura fetch https://example.com --wait-until networkidle0

# Limitar o tempo de navegação para páginas lentas ou quebradas
obscura fetch https://example.com --timeout 10

# Capturar a página já estabilizada como PNG
obscura fetch https://example.com --screenshot page.png

# A flag de screenshot também tem uma forma curta
obscura fetch https://example.com -s page.png
```

### Testando com servidores de desenvolvimento em localhost / LAN

Por padrão, o Obscura bloqueia requisições para IPs privados/internos (proteção contra SSRF).
Para apontá-lo para um servidor de desenvolvimento local, passe `--allow-private-network` (ou defina
`OBSCURA_ALLOW_PRIVATE_NETWORK=1`):

```bash
obscura fetch http://127.0.0.1:3000 --allow-private-network --dump text

# Funciona em qualquer subcomando, por exemplo, o servidor CDP para Puppeteer/Playwright local:
obscura serve --port 9222 --allow-private-network
```

Consulte [docs/Environment-variables.md](docs/Environment-variables.md) para as
regras completas de permissão/bloqueio (incluindo as verificações no momento da resolução de DNS).

## Renderização

Os arquivos oficiais de release e a imagem Docker incluem o motor de renderização.
Ele oferece layout e pintura de CSS, screenshots da viewport e da página inteira,
geometria fixed e sticky com suporte a scroll, screencast CDP orientado por atividade e
exportação de PDF raster sem iniciar o Chromium.

```javascript
await page.setViewport({ width: 1440, height: 1000 });
await page.goto('https://example.com', { waitUntil: 'load' });
await page.screenshot({ path: 'page.png', fullPage: true });
await page.pdf({ path: 'page.pdf', format: 'A4', printBackground: true });
```

A implementação atual cobre os caminhos de block, inline, flex, grid, table, float,
positioning, overflow, transform, texto, imagem, SVG, canvas, background, border
e animação. Ela continua sendo um motor independente em evolução: CSS de cauda longa,
algumas Web APIs, reprodução de mídia, efeitos de compositor e a rasterização de fontes
da plataforma podem diferir do Chromium. Os guias existentes de
[Puppeteer](docs/Use-with-Puppeteer.md),
[Playwright](docs/Use-with-Playwright.md) e
[MCP](docs/Use-the-MCP-server.md) cobrem suas APIs de captura e limitações.

### Iniciar o servidor CDP

```bash
obscura serve --port 9222

# Com modo stealth (anti-detecção + bloqueio de trackers)
obscura serve --port 9222 --stealth
```

### Scraping em paralelo

```bash
obscura scrape url1 url2 url3 ... \
  --concurrency 25 \
  --eval "document.querySelector('h1').textContent" \
  --format json

# Suprimir o progresso do scrape no stderr para uma saída amigável a scripts
obscura scrape https://example.com --quiet --format json

# Os workers do scrape herdam o proxy global
obscura --proxy http://127.0.0.1:8080 scrape https://example.com https://news.ycombinator.com
```

## Puppeteer / Playwright

A [emulação de preferências de mídia](docs/CDP-media.md) cobre as sobreposições de esquema de cores e de movimento reduzido.

### Puppeteer

```bash
npm install puppeteer-core
```

```javascript
import puppeteer from 'puppeteer-core';

const browser = await puppeteer.connect({
  browserWSEndpoint: 'ws://127.0.0.1:9222/devtools/browser',
});

const page = await browser.newPage();
await page.goto('https://news.ycombinator.com');

const stories = await page.evaluate(() =>
  Array.from(document.querySelectorAll('.titleline > a'))
    .map(a => ({ title: a.textContent, url: a.href }))
);
console.log(stories);

await browser.disconnect();
```

### Playwright

```bash
npm install playwright-core
```

```javascript
import { chromium } from 'playwright-core';

const browser = await chromium.connectOverCDP({
  endpointURL: 'ws://127.0.0.1:9222',
});

const page = await browser.newContext().then(ctx => ctx.newPage());
await page.goto('https://en.wikipedia.org/wiki/Web_scraping');
console.log(await page.title());

await browser.close();
```

### Envio de formulários e login

```javascript
await page.goto('https://quotes.toscrape.com/login');
await page.evaluate(() => {
  document.querySelector('#username').value = 'admin';
  document.querySelector('#password').value = 'admin';
  document.querySelector('form').submit();
});
// O Obscura cuida do POST, segue o redirecionamento 302 e mantém os cookies
```

## Benchmarks

Carregamento de página:

| Página | Obscura | Chrome |
|--------|---------|--------|
| HTML estático | **51 ms** | ~500 ms |
| JS + XHR + fetch | **84 ms** | ~800 ms |
| Scripts dinâmicos | **78 ms** | ~700 ms |

A suíte completa de benchmarks (conformidade WPT, obstacle course, corpus do mundo real e velocidade vs. Chrome) fica em um repositório separado: https://github.com/h4ckf0r0day/obscura-benchmark

## Modo Stealth

Compile com `--features render,stealth` e depois ative o stealth em tempo de execução com a
flag global `--stealth`. O build com stealth inclui o motor de renderização completo;
ativar o stealth não remove as funcionalidades de screenshot, screencast, PDF, CDP ou
MCP.

### Anti-fingerprinting
- Randomização de fingerprint por sessão (GPU, tela, canvas, áudio, bateria)
- `navigator.userAgentData` realista (Chrome 145, valores de alta entropia)
- `event.isTrusted = true` para eventos disparados
- Propriedades internas ocultas (`Object.keys(window)` seguro)
- Mascaramento de funções nativas (`Function.prototype.toString()` → `[native code]`)
- `navigator.webdriver = false`

### Bloqueio de Trackers
- 3.520 domínios bloqueados
- Bloqueia scripts de analytics, anúncios, telemetria e fingerprinting
- Impede que os trackers sejam carregados
- Ativado automaticamente com `--stealth`

## API CDP

O Obscura implementa o Chrome DevTools Protocol para compatibilidade com Puppeteer/Playwright.

| Domínio | Métodos |
|---------|---------|
| **Target** | createTarget, closeTarget, attachToTarget, createBrowserContext, disposeBrowserContext |
| **Page** | navigate, getFrameTree, lifecycleEvents, captureScreenshot, start/stopScreencast, printToPDF |
| **Runtime** | evaluate, callFunctionOn, getProperties, addBinding |
| **DOM** | getDocument, querySelector, querySelectorAll, getOuterHTML, resolveNode |
| **Network** | enable, setCookies, getCookies, setExtraHTTPHeaders, setUserAgentOverride |
| **Fetch** | enable, continueRequest, fulfillRequest, failRequest (interceptação ao vivo), takeResponseBodyAsStream |
| **IO** | read, close (transmite o corpo de uma resposta grande em blocos) |
| **Storage** | getCookies, setCookies, deleteCookies |
| **Input** | dispatchMouseEvent, dispatchKeyEvent |
| **LP** | getMarkdown (conversão de DOM para Markdown) |

A interceptação via Fetch pausa as requisições HTTP do documento principal que correspondem ao filtro, antes do transporte. O fulfillment fornece o corpo do documento sem contatar o servidor; as substituições de URL, método, corpo e cabeçalhos na continuação se aplicam somente a essa requisição.

Para baixar um recurso grande sem um único blob gigante de `Network.getResponseBody`, chame `Fetch.takeResponseBodyAsStream` e depois leia em blocos com `IO.read` / `IO.close`. Corpos de resposta acima do limite de cache (`OBSCURA_NETWORK_BODY_BUFFER_BYTES`, padrão 2 MiB) não são retidos; portanto, aumente esse limite quando pretender transmitir downloads grandes.

## Referência da CLI

### Ajustando o V8

O Obscura embute o V8 diretamente. Use `--v8-flags` para repassar flags brutas ao V8, com a mesma sintaxe do `--js-flags` do Chromium e das flags de linha de comando do Node. O uso mais comum é aumentar o limite de heap para corrigir `JavaScript heap out of memory` em páginas com muito JS:

```bash
obscura --v8-flags "--max-old-space-size=4096" fetch https://example.com
```

### SPAs pesadas (orçamento de execução de scripts)

O Obscura limita a fase de execução de scripts da página para que uma página lenta ou travada não paralise um worker. O orçamento padrão é de 30s; páginas que terminam antes retornam imediatamente, então o limite só afeta páginas que continuam executando. Uma SPA React/Vue/Angular muito pesada em uma rede lenta pode precisar de mais tempo para inicializar antes de disparar suas requisições de dados. Aumente o orçamento com `OBSCURA_SCRIPT_DEADLINE_MS` (em milissegundos) e combine com um timeout de navegação equivalente no seu cliente CDP:

```bash
OBSCURA_SCRIPT_DEADLINE_MS=60000 obscura serve --port 9222
```

Módulos que complementam uma página já renderizada têm um orçamento separado de 3s por módulo, para que um módulo não essencial não mantenha a navegação aberta. Aumente-o para módulos legítimos de longa duração, como um cliente HMR do Vite:

```bash
OBSCURA_MODULE_BUDGET_MS=10000 obscura serve --port 9222
```

Um shell de SPA não montado já concede aos módulos do app o orçamento completo de `OBSCURA_SCRIPT_DEADLINE_MS`. `OBSCURA_FETCH_TIMEOUT_MS` controla a requisição de rede do módulo, não o tempo de avaliação. Consulte [Variáveis de ambiente](docs/Environment-variables.md) para o modelo completo de timeouts.

### `obscura serve`

Inicia um servidor WebSocket CDP.

| Flag | Padrão | Descrição |
|------|--------|-----------|
| `--port` | `9222` | Porta do WebSocket |
| `--proxy` | — | URL de proxy HTTP/SOCKS5 |
| `--stealth` | desativado | Ativa anti-detecção + bloqueio de trackers |
| `--workers` | `1` | Número de processos worker paralelos |
| `--worker-max-connections` | desativado | Recicla um worker após N conexões CDP (requer `--workers` > 1) |
| `--worker-max-rss` | desativado | Recicla um worker acima desta quantidade de MB residentes (Linux) |
| `--worker-max-age` | desativado | Recicla um worker após este número de segundos |
| `--worker-drain-timeout` | `120` | Segundos que um worker substituído pode usar para concluir suas conexões ativas antes de ser encerrado |
| `--font-dir` | — | Carrega fontes recursivamente uma vez por worker (repetível; build com renderização) |
| `--obey-robots` | desativado | Respeita o robots.txt |

Com múltiplos workers, os processos filhos que saem são recolhidos e reiniciados. Novas conexões
usam apenas workers prontos; se nenhum estiver pronto, o balanceador retorna HTTP 503. Uma falha
ainda encerra as sessões existentes daquele worker, e os clientes precisam se reconectar.

As opções `--worker-max-*` reciclam workers de forma graciosa: uma substituição é iniciada
primeiro, as novas conexões vão apenas para ela, e o worker antigo continua atendendo as
conexões que já possui até que sejam fechadas (ou o tempo de drenagem expire), e então
encerra. Cada reciclagem é registrada em log com o motivo.
Os erros dos workers continuam visíveis no stderr.

### `obscura fetch <URL>`

Busca e renderiza uma única página.

| Flag | Padrão | Descrição |
|------|--------|-----------|
| `--dump` | `html` | Saída: `html`, `text`, `links`, `markdown`, `assets` (NDJSON de cada URL de sub-recurso referenciada pela página) ou `original` (corpo bruto da resposta) |
| `--eval` | — | Expressão JavaScript a ser avaliada |
| `--wait-until` | `load` | Espera: `load`, `domcontentloaded`, `networkidle0`. O network idle conta requisições normais e stealth e exige uma janela de 500 ms de silêncio dentro de `--timeout`; um prazo expirado é um erro. |
| `--timeout` | `30` | Tempo máximo de navegação em segundos |
| `--wait` | adaptativo, até `5` | Estabilização pós-carregamento; um valor explícito é um atraso fixo em segundos |
| `--selector` | — | Aguarda por um seletor CSS |
| `-s`, `--screenshot` | — | Grava um screenshot PNG (URL única; build com renderização) |
| `--stealth` | desativado | Modo anti-detecção |
| `--output` | — | Grava a saída do dump ou do eval em um arquivo |
| `--quiet` | desativado | Suprime o banner |
| `--proxy` | — | URL de proxy HTTP/SOCKS5 global herdada |

### `obscura scrape <URL...>`

Faz scraping de várias URLs em paralelo com processos worker.

`scrape` e `fetch --file ... --dump original` mantêm no máximo `--concurrency`
jobs ativos, iniciando a próxima URL assim que uma vaga fica disponível. Os resultados
permanecem na ordem de entrada. A entrada de URLs e os resultados concluídos ainda são mantidos na memória.

| Flag | Padrão | Descrição |
|------|--------|-----------|
| `--concurrency` | `10` | Workers paralelos |
| `--eval` | — | Expressão JS por página |
| `--format` | `json` | Saída: `json` ou `text` |
| `--quiet` | desativado | Suprime o progresso do scrape no stderr |
| `--proxy` | — | URL de proxy HTTP/SOCKS5 global herdada para todos os workers |

## MCP (Model Context Protocol)

O Obscura inclui um servidor MCP que expõe ferramentas de automação de navegador para agentes de IA (Claude Desktop, Cursor etc.).

### Iniciar

**stdio** (padrão) — para o Claude Desktop e clientes MCP que iniciam um subprocesso:

```bash
obscura mcp
```

**HTTP** — para clientes que se conectam pela rede:

```bash
obscura mcp --http --port 8080
# endpoint: http://127.0.0.1:8080/mcp
```

Flags opcionais (ambos os transportes):

| Flag | Descrição |
|------|-----------|
| `--proxy <URL>` | Proxy HTTP/SOCKS5 |
| `--user-agent <UA>` | String de User-Agent personalizada |
| `--font-dir <DIR>` | Carrega fontes adicionais antes de renderizar (repetível; build com renderização) |
| `--stealth` | Ativa o modo anti-detecção |

### Configuração do Claude Desktop

```json
{
  "mcpServers": {
    "obscura": {
      "command": "obscura",
      "args": ["mcp"]
    }
  }
}
```

### Ferramentas

| Ferramenta | Descrição |
|------------|-----------|
| `browser_navigate` | Navega para uma URL (`url`, `waitUntil` opcional: `load` / `domcontentloaded` / `networkidle0`) |
| `browser_snapshot` | Retorna a URL atual da página, o título, o texto legível do corpo e as referências de elementos |
| `browser_screenshot` | Retorna a página atual como uma imagem PNG do MCP (build com renderização) |
| `browser_pdf` | Retorna a página atual como um recurso PDF embutido (build com renderização) |
| `browser_click` | Clica por referência do snapshot atual ou seletor CSS |
| `browser_fill` | Define o valor de um input por referência ou seletor (dispara `input` + `change`) |
| `browser_type` | Acrescenta texto a um input |
| `browser_press_key` | Dispara um evento de teclado (`key`, `selector` opcional) |
| `browser_select_option` | Seleciona uma `<option>` por valor ou texto |
| `browser_evaluate` | Avalia uma expressão JavaScript e retorna o resultado |
| `browser_wait_for` | Aguarda um seletor CSS aparecer (`selector`, `timeout` opcional em segundos) |
| `browser_network_requests` | Lista as requisições de rede feitas pela página atual |
| `browser_console_messages` | Retorna as mensagens de console registradas pela página |
| `browser_close` | Fecha a página e reinicia o estado do navegador |

O servidor MCP expõe saída de imagem estática e PDF. Use o CDP quando precisar do
protocolo de streaming `Page.startScreencast`.

## Integrações

- **[Plugin para o agente Hermes](https://github.com/SGavrl/hermes-plugin-obscura)**: execute tarefas de navegador do agente [Hermes](https://github.com/NousResearch/hermes-agent) no Obscura. O plugin inicia `obscura serve` por sessão (ou se conecta a um servidor já em execução) e o controla via CDP, com `--stealth` opcional.

## Licença

Apache 2.0

---
