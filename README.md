# KXP Emulador

> **Emulador Android Gamer de baixa latência para Windows — desenvolvido pela INSANIX STUDIO.**  
> **Versão atual:** `v1.0.0` • **Licença:** Gratuito (Freeware)

O **KXP Emulador** é uma plataforma desktop para jogos e aplicativos Android no Windows 10 e Windows 11 (64-bit), projetada do zero para entregar resposta rápida de teclado e mouse, interface PC Gaming limpa e mapeamento multitouch avançado sem bloqueios de anúncio ou dependências externas complicadas.

---

## Principais Recursos

* **Pacote 100% portátil e autocontido:** basta extrair e abrir o `KxpLauncher.exe` — não exige instalação separada de .NET, motor de virtualização ou ferramentas Android.
* **Arquitetura Dual-Channel Anti-Bug de Analógico:** canais virtuais separados para movimentação (`Analógico 360°`) e câmera/tiro (`Mira 360°`), evitando travamentos de movimento durante troca de tiro.
* **Mapeador Pro com 11 tipos de controle e física calibrada:**
  * **Toque Simples**, **Atirar (FPS)**, **Mirar / ADS** e **Mira 360°** (com trava rápida por tecla configurável, padrão `F1`, e reset anti-borda automático).
  * **Analógico 360°** (`WASD` ou Setas) com rampa micro-interpolada, normalização circular corrigida para telas widescreen e tecla de caminhada lenta.
  * **Deslizar (`A → B`)** com curva suavizada, duração em milissegundos e opção para segurar no ponto final.
  * **Turbo / Rajada** com taxa de cliques configurável por segundo.
  * **Zoom (2 Dedos)** por teclas ou roda do mouse (*Scroll*).
  * **Olhar Livre (Olho)** em dedo virtual dedicado sem mover a mira principal.
  * **Skill Direcional** guiada pelo movimento do mouse estilo MOBA/Arena.
  * **Macro Duplo (`1 → 2`)** para combos com atraso configurável entre toques.
* **HUD limpo por padrão:** os botões virtuais ficam ocultos fora de configuração e só aparecem sobre a tela quando você marcar explicitamente a opção **"Exibir no jogo"**.
* **Tela Cheia Real (`F11`) & Janela sem Bordas:** alternância rápida mantendo barras do sistema ocultas e preenchimento total do monitor.
* **KXP Gaming Desktop & Kulefi Ofertas:** inicialização rápida com área de trabalho gamer, Play Store e app **Kulefi Ofertas** (`kulefi.com.br`) já disponível no sistema, além de botão direto para instalar arquivos `.apk`.

---

## Requisitos Mínimos

* **Sistema Operacional:** Windows 10 ou Windows 11 (64-bit)
* **Processador:** CPU x64 com suporte a virtualização de hardware (`Intel VT-x` ou `AMD-V` ativada na BIOS)
* **Memória RAM:** 4 GB livres mínimos (recomendado 8 GB+ no computador)
* **Armazenamento:** ~3,5 GB livres em disco após extrair o pacote
* **Gráficos:** GPU com suporte OpenGL / Direct3D atualizado
* **Recomendado para desempenho máximo (Modo TURBO):** ativar o recurso opcional do Windows **Plataforma de Hipervisor do Windows** (*Windows Hypervisor Platform*) e manter a **Aceleração Gráfica HD 3D** ligada nas configurações do launcher.

---

## Tutorial Passo a Passo — Instalação e Uso

1. **Baixe o pacote oficial:**  
   Faça o download de `KXP-Emulador-v1.0.0.zip` na pasta de entrega / página oficial de lançamentos.
2. **Extraia o arquivo completo:**  
   Clique com o botão direito sobre o `.zip` e escolha **Extrair Tudo...** para uma pasta fora de *Arquivos de Programas* (exemplo: `C:\Jogos\KXP-Emulador`).  
   > **Importante:** nunca execute o `KxpLauncher.exe` diretamente de dentro do `.zip` sem extrair primeiro.
3. **Inicie o KXP Emulador:**  
   Entre na pasta extraída e dê um duplo clique em **`KxpLauncher.exe`**.  
   No painel principal, escolha a memória RAM, resolução, FPS e modo de exibição desejados e clique em **`INICIAR ANDROID 17`**.
4. **Configure seu Mapeamento:**
   * Clique em **Mapeador** (barra superior ou lateral) para abrir o editor.
   * Escolha um perfil pronto (**Free Fire (FPS)**, **MOBA / Arena**, **Arcade / Deslizar**) ou adicione controles pela paleta lateral esquerda.
   * Ajuste teclas, duração, taxa de turbo, opacidade e clique em **Salvar e Fechar**.
   * Marque **Exibir no jogo** apenas se quiser visualizar as legendas das teclas sobre a tela durante a partida.

### Atalhos Principais

| Tecla / Comando | Função |
| :--- | :--- |
| `F1` | Trava / destrava a mira 360° com o mouse (cursor livre x modo FPS) |
| `F11` | Alterna entre Tela Cheia 100% e Janela sem Bordas |
| Barra Lateral | Voltar, Home, Recentes, Volume, Captura de Tela, Instalar APK e Ajustes |

---

## Verificação de Integridade (SHA-256)

Antes de executar, você pode conferir se o arquivo baixado está íntegro e original comparando o hash:

* **Arquivo:** `entrega/KXP-Emulador-v1.0.0.zip`
* **Tamanho:** `1.58 GB` (`1.698.538.293 bytes`)
* **SHA-256:** `D1378D6CCD9C32725B3B10765F40208C22F15DFC8296EA4F48B5E34D2A143F33`

Comando para conferir no Windows (Prompt de Comando ou PowerShell):

```cmd
certutil -hashfile KXP-Emulador-v1.0.0.zip SHA256
```

---

## Histórico de Versões (Changelog)

* **`v1.0.0`** *(2026-11-18)* — Lançamento oficial portátil: KXP Desktop Gaming com tela cheia real (`F11`), janela sem bordas DPI-aware, tela de carregamento dedicada, Mapeador Pro completo com 11 tipos de controle e física multitouch dual-channel, presets prontos (`Free Fire`, `MOBA`, `Arcade`), HUD oculto por padrão, instalador rápido de `.apk` e app **Kulefi Ofertas** integrado.

---

## Créditos e Aviso Legal

* **Desenvolvido e distribuído por:** **INSANIX STUDIO** (`https://insanixstudio.com.br`)
* **Licença:** Software gratuito (*Freeware*, pacote fechado para uso do usuário final).
* **Aviso:** Marcas e nomes de jogos citados como referência de compatibilidade e presets pertencem aos seus respectivos proprietários. Este projeto não possui vínculo oficial com terceiros.
