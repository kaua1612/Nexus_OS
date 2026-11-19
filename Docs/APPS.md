# NEXUS_OS — Aplicativos padrão

## Gaming Edition 0.1.0

### Objetivo

O NEXUS_OS contará com um conjunto selecionado de aplicativos essenciais para jogos, comunicação, gravação e utilização cotidiana.

A prioridade é manter o sistema leve, evitando inicializações automáticas e processos desnecessários.

### Aplicativos selecionados

| Aplicativo | Finalidade |
|---|---|
| Google Chrome | Navegação |
| Steam | Plataforma de jogos |
| Discord | Comunicação |
| MangoHud | Monitoramento de desempenho |
| Heroic Games Launcher | Gerenciamento de jogos |
| OBS Studio | Gravação e transmissão |
| VLC | Reprodução de mídia |
| Lutris | Gerenciamento de jogos |

### Gerenciamento de pacotes

O projeto utilizará:

- Pacman: repositórios oficiais.
- AUR: aplicativos da comunidade Arch.
- Flatpak: aplicativos em ambientes isolados.

### Diretrizes

1. Evitar aplicativos desnecessários.
2. Não iniciar programas automaticamente sem necessidade.
3. Manter os aplicativos atualizados.
4. Priorizar estabilidade e compatibilidade.
5. Não comprometer drivers ou bibliotecas necessários aos jogos.

### Status

- [x] Seleção dos aplicativos.
- [x] Planejamento inicial dos métodos de instalação.
- [ ] Conferência dos pacotes.
- [ ] Configuração da instalação automática.
- [ ] Testes de funcionamento.
- [ ] Inclusão na ISO do NEXUS_OS.