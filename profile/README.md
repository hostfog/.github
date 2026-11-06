<div align="center">

<img src="hf.png" width="80" alt="HostFog">

# HostFog

**Software for running websites: on your own server, on your own computer and on the internet.**

[Website](https://hostfog.com) &nbsp;·&nbsp; [Docs](https://docs.hostfog.com) &nbsp;·&nbsp; [Downloads](https://hostfog.com/software/) &nbsp;·&nbsp; [YouTube](https://www.youtube.com/@hostfog) &nbsp;·&nbsp; [Contact](mailto:contact@hostfog.com)

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Windows](https://img.shields.io/badge/Windows-0078D4?style=flat-square&logo=windows&logoColor=white)
![macOS](https://img.shields.io/badge/macOS-000000?style=flat-square&logo=apple&logoColor=white)

</div>

---

## Products

<table>
<tr>
<td width="50%" valign="top">

### HF Panel
Web hosting control panel for Linux servers. **Server Admin**, **Reseller Panel** and **Control Panel**, with Mail, Files, DB Studio and a full API. Installs with one command and finishes setup in the browser.

[**hostfog.com →**](https://hostfog.com)

</td>
<td width="50%" valign="top">

### HF Local
Build websites on your own computer: web server, PHP, databases and more, ready in minutes. Windows, macOS and Linux.

**Free** · [**Download →**](https://hostfog.com/software/)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### HF Connect
SSH terminals, SFTP and FTP in one window, with saved hosts, keys and jump hosts.

**Free** · [**Download →**](https://hostfog.com/software/)

</td>
<td width="50%" valign="top">

### HF Tunnel
Put a website on your computer online in one click at `name.hostfog.io`. No account needed.

**Free** · [**Download →**](https://hostfog.com/software/)

</td>
</tr>
</table>

## Open source

| Project | What it is |
| :-- | :-- |
| [**hfee**](https://github.com/hostfog/hfee) | Run AI models on your own machine. A pure-Go inference engine with a simple command line and an Ollama- and OpenAI-compatible API. |
| [**hfee-ai**](https://github.com/hostfog/hfee-ai) | A self-hosted AI assistant built on hfee: chat, files, web search, images and voice, for servers, desktops, Docker and phones. |
| [**hfkv**](https://github.com/hostfog/hfkv) | A fast key-value and cache server that speaks the Redis protocol. Written in Go with no third-party libraries. |

### Go libraries

| Package | What it is | Docs |
| :-- | :-- | :-- |
| [**fog**](https://github.com/hostfog/fog) | A batteries-included web framework with a Laravel-style feel: routing, validation, query builder, migrations, sessions, auth and views. | [![Go Reference](https://pkg.go.dev/badge/github.com/hostfog/fog.svg)](https://pkg.go.dev/github.com/hostfog/fog) |
| [**frame**](https://github.com/hostfog/frame) | A pandas-style DataFrame with typed columns, CSV and JSON, group by and joins. | [![Go Reference](https://pkg.go.dev/badge/github.com/hostfog/frame.svg)](https://pkg.go.dev/github.com/hostfog/frame) |
| [**sigil**](https://github.com/hostfog/sigil) | JSON Web Tokens (JWS, JWE, JWKS) with the same API in Go, TypeScript, PHP and Python. | [![Go Reference](https://pkg.go.dev/badge/github.com/hostfog/sigil/go.svg)](https://pkg.go.dev/github.com/hostfog/sigil/go) |
| [**auth**](https://github.com/hostfog/auth) | Login for Go apps: passwords, 2FA, passkeys, magic links and social login. | [![Go Reference](https://pkg.go.dev/badge/github.com/hostfog/auth.svg)](https://pkg.go.dev/github.com/hostfog/auth) |
| [**money**](https://github.com/hostfog/money) | Money amounts and currencies without floating-point errors. | [![Go Reference](https://pkg.go.dev/badge/github.com/hostfog/money.svg)](https://pkg.go.dev/github.com/hostfog/money) |
| [**iso20022**](https://github.com/hostfog/iso20022) | Build and read ISO 20022 payment messages. | [![Go Reference](https://pkg.go.dev/badge/github.com/hostfog/iso20022.svg)](https://pkg.go.dev/github.com/hostfog/iso20022) |
| [**mjml**](https://github.com/hostfog/mjml) | Turn MJML templates into responsive HTML emails. | [![Go Reference](https://pkg.go.dev/badge/github.com/hostfog/mjml.svg)](https://pkg.go.dev/github.com/hostfog/mjml) |
| [**htmlpdf**](https://github.com/hostfog/htmlpdf) | Convert HTML to PDF. | [![Go Reference](https://pkg.go.dev/badge/github.com/hostfog/htmlpdf.svg)](https://pkg.go.dev/github.com/hostfog/htmlpdf) |
| [**docx**](https://github.com/hostfog/docx) | Create and read Word (.docx) documents. | [![Go Reference](https://pkg.go.dev/badge/github.com/hostfog/docx.svg)](https://pkg.go.dev/github.com/hostfog/docx) |
| [**webp**](https://github.com/hostfog/webp) | Encode and decode WebP images. | [![Go Reference](https://pkg.go.dev/badge/github.com/hostfog/webp.svg)](https://pkg.go.dev/github.com/hostfog/webp) |
| [**mp3**](https://github.com/hostfog/mp3) | Decode MP3 audio. | [![Go Reference](https://pkg.go.dev/badge/github.com/hostfog/mp3.svg)](https://pkg.go.dev/github.com/hostfog/mp3) |
| [**gguf**](https://github.com/hostfog/gguf) | Read GGUF model files. | [![Go Reference](https://pkg.go.dev/badge/github.com/hostfog/gguf.svg)](https://pkg.go.dev/github.com/hostfog/gguf) |
| [**tokenizer**](https://github.com/hostfog/tokenizer) | Tokenizers for running language models. | [![Go Reference](https://pkg.go.dev/badge/github.com/hostfog/tokenizer.svg)](https://pkg.go.dev/github.com/hostfog/tokenizer) |

Install any of them with `go get github.com/hostfog/<name>@latest`.

All MIT licensed. Issues and pull requests are welcome.

## Install HF Panel

```bash
curl -fsSL https://cdn.hostfog.com/latest | bash
```

Open the link it prints and the browser walks you through the rest: **server check → DNS → admin login → done.**

Supports Ubuntu, Debian, Rocky Linux, AlmaLinux and CentOS Stream. See the [install guide](https://docs.hostfog.com) for details.

## Get in touch

| | |
| :-- | :-- |
| Questions and sales | [contact@hostfog.com](mailto:contact@hostfog.com) |
| Security reports | [security@hostfog.com](mailto:security@hostfog.com) (please don't open public issues for security problems) |

---

<div align="center">
<sub>© 2026 HostFog Ltd · Hayes, London, UK</sub>
</div>
