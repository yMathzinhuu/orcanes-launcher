# 🐋 Changelog - Orcanes Launcher

Todas as mudanças e notas de lançamento do projeto estão documentadas neste arquivo.

---

## 🚀 [v0.4.35 Alpha]

### 🔐 Modo Offline Repaginado
* **Novo Modal Interativo**: Janela modal interna e personalizada para inserção/alteração do nickname no modo offline.
* **Alternância de Contas Rápida**: Transição simplificada entre conta Microsoft e conta Offline.

### 🕹️ Otimização do Minigame da Orca
* **Pausa Automática em Segundo Plano**: O loop do minigame e o consumo de processamento/memória param imediatamente ao trocar de aba no launcher.
* **Física de Bordas Ajustada**: Tocar o teto ou o chão não causa mais *Game Over* instantâneo; a orca apenas encosta e perde velocidade.
* **Spawn Limpo de Obstáculos**: Margens de espaço garantem que os obstáculos nunca nasçam colados nas extremidades superior/inferior.

### 🛡️ Interface e Segurança
* **DevTools Bloqueado**: Desativado o menu de contexto (clique com botão direito) e os atalhos de depuração (`F12`, `Ctrl+Shift+I`, `Ctrl+Shift+J`, `Ctrl+U`).
* **Limpeza Visual**: Removido o card de status com IP fixo da tela inicial e revisados todos os textos da interface.

---

## 📦 [v0.4.23 Alpha]

* Sincronizador automático de mods para a pasta `.orcanes/mods`.
* Sistema de login com Microsoft e salvamento automático de sessão (`auth.json`).
* Visualizador de skins 3D interativo com suporte a busca por Nick e envio de `.png`.
* Atualizações automáticas integradas via GitHub Releases.
* Ajuste dinâmico de memória RAM e terminal de logs em tempo real.