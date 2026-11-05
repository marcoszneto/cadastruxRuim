# 🎃 Bazar do Além — Cadastrux Ruim

Página de **login e cadastro** de um e-commerce de Halloween feita para ter a **pior interface de usuário possível**, mas que ainda pode ser usada até o fim.

Tecnologias: HTML, CSS e JavaScript puro, num único arquivo (`index.html`). Não precisa de servidor nem de instalação.

## Como abrir

- Dê dois cliques no `index.html`, ou
- Publique com o **GitHub Pages**: *Settings → Pages → Branch `main` / pasta `/ (root)` → Save*.

Conta de teste para o login: `dracula@castelo.ro` / `boo123`.

## Crimes contra a usabilidade

### Página inteira
- Cores berrantes, Comic Sans, layout torto, texto piscando e faixa de promoção correndo.
- **Morcego ladrão** (inspirado no Desktop Goose): voa pela página, rouba o cursor e carrega as caixas de texto. Clique nele ou aperte Esc para espantá-lo.
- **Cores invertidas** a cada 30 segundos.
- **Teste de digitação surpresa** a cada 1 minuto: 12 segundos para digitar uma frase. Quem falha perde tudo o que preencheu no cadastro.
- **Modo Escuro de Verdade**: a página fica preta e o cursor vira uma lanterna.
- **Acessibilidade para cegos**: troca todo o texto da tela por braille.
- **TAB desativado** e **colar bloqueado** em todos os campos.
- Pop-up de cupom com o "x" minúsculo num canto aleatório.

### Login ("Portal dos Já")
- Botão de entrar minúsculo que foge do mouse; "CANCELAR TUDO" gigante.
- Olho que mostra a senha por meio segundo.
- Carregamento falso e mensagens de erro sem sentido.

### Cadastro ("Portal dos Ainda Não")
| Campo | Como é preenchido |
|---|---|
| Nome | Autocompleta com nomes de famosos (ou nomes comuns) a cada letra digitada |
| E-mail (rotulado "celular") | Câmbio de marchas: arraste a manopla pelos trilhos e aperte TYPE. Validado por regex |
| Celular (rotulado "e-mail") | Uma barra deslizante com 88 bilhões de números, com setinhas por dígito |
| CPF | Informe em qual posição do número π o seu CPF aparece (precisa ser um CPF válido) |
| Data de nascimento | Consulta astral em 7 perguntas (signo, ascendente, decanato, grau, horóscopo chinês...) |
| País | Desenhe a bandeira em pixels e o sistema tenta adivinhar |
| Senha | Regras que surgem uma a uma (estilo *The Password Game*) |
| Confirmação de senha | Repetir a senha inteira, sem colar |

- **Captcha ao terminar cada campo**: contar emojis, palavra ao contrário, conta de vampiro, grade de imagens ou escrever "i am not a robot" à mão.
- **Confirmação final decidida por um Plinko**: a bolinha escolhe se o cadastro é finalizado.

## Dicas para conseguir se cadastrar
- Senha que passa em todas as regras: `Outubro vampiro Nepal🎃🦇 2026 3!` (emojis pelo seletor do sistema: `Win + .` no Windows, `Ctrl + Cmd + Espaço` no Mac).
- Posições do π que formam um CPF válido: 107, 323, 357, 461, 548.
- Os cadastros ficam salvos só no navegador (localStorage).
