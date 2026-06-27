# TJ Maps — App

[![GitHub release (latest by date)](https://img.shields.io/github/v/release/igor-rl/tjmaps-app?style=flat-square&color=blue)](https://github.com/igor-rl/tjmaps-app/releases/latest)

Página de download e releases do aplicativo desktop **TJ Maps** — ferramenta para gestão de mapas e territórios das Testemunhas de Jeová.

## 📥 Download

Acesse a página de download ou baixe diretamente pela página de releases:

| Sistema | Arquivo |
|---|---|
| **macOS** (Apple Silicon) | `TJ-Maps-macOS-x.x.x-arm64.dmg` |
| **macOS** (Intel) | `TJ-Maps-macOS-x.x.x-x64.dmg` |
| **Windows** (instalador) | `TJ-Maps-windows-installer-x.x.x.exe` |
| **Windows** (portátil) | `TJ-Maps-windows-portable-x.x.x.exe` |

👉 **[Ver todas as versões](https://github.com/igor-rl/tjmaps-app/releases)**

### macOS

1. Abra o `.dmg` e arraste o app para **Aplicativos**
2. Como o app não é assinado pela App Store, o macOS irá bloqueá-lo na primeira abertura. Para liberar, abra o **Terminal** e rode:

```bash
xattr -rd com.apple.quarantine '/Applications/TJ Maps.app' && open '/Applications/TJ Maps.app'
```

Ou vá em **Ajustes do Sistema → Privacidade e Segurança** e clique em **"Abrir mesmo assim"**.

### Windows

1. Execute o instalador `.exe` e siga os passos
2. O app criará um atalho na Área de Trabalho e no Menu Iniciar
3. Se preferir não instalar, use a versão **portátil** — basta executar o `.exe` diretamente

> Os arquivos `.yml` e `.blockmap` são usados internamente para atualizações automáticas — não é necessário baixá-los.

---

<br/>
<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-Igor_Lage-blue?style=social&logo=github)](https://github.com/igor-rl)

</div>
