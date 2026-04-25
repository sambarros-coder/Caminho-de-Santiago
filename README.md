# Santiago Tracker – PWA

## Como instalar no Android (Chrome)

1. Abra o Google Chrome no seu celular
2. Acesse o arquivo `index.html` localmente ou hospede-o em qualquer servidor
3. Toque no menu ⋮ (três pontos) > "Adicionar à tela inicial"
4. Confirme — o app aparecerá como ícone na tela inicial

## Opção mais simples: hospedar no GitHub Pages (gratuito)

1. Crie um repositório no GitHub (ex: `santiago-treino`)
2. Faça upload dos 3 arquivos: `index.html`, `manifest.json`, `sw.js`
3. Vá em Settings > Pages > Source: main branch / root
4. Em ~1 minuto, o app estará disponível em: `https://SEU_USUARIO.github.io/santiago-treino/`
5. Abra esse link no Chrome do Android e instale

## Funcionalidades

- **Hoje**: treino do dia com descrição completa do plano
- **Calendário**: visão mensal com ícones por tipo de treino
- **Progresso**: aderência, km acumulados, fases do plano
- **Registro**: ✅/❌ execução, km reais, carga×reps (força), notas livres
- **Notificações push**: configurable por horário
- **Offline**: funciona sem internet após primeiro acesso
- **Export**: baixa todos os registros em JSON

## Arquivos

- `index.html` — app completo (single-file)
- `manifest.json` — metadados PWA para instalação
- `sw.js` — service worker (offline + notificações)
