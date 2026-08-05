# Caixa Pulante

Caixinha de música interativa em [p5.js](https://p5js.org/) + [p5.play](https://p5play.molleindustria.org/): uma bolinha pula sobre blocos coloridos ao som de uma música.

## Como ver

Abra `index.html` no navegador — não precisa de instalação nem servidor.

## Estrutura

- `sketch.js` — física dos blocos, colisão da bolinha e trilha sonora
- `music.mp3` — trilha sonora
- `index.html` — carrega p5.js, p5.play, p5.sound e o sketch

## Rodando localmente

Nenhuma dependência externa: as bibliotecas já estão incluídas no repositório. Basta abrir `index.html` direto no navegador ou servir a pasta com qualquer servidor estático (ex: `npx serve .`).

> O arquivo `ssrdarsfahTemplate-main.zip` no repositório não é usado pelo projeto (é o template original ainda compactado) e pode ser removido.
