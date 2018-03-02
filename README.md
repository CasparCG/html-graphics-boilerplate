# html-graphics-boilerplate

## Setup new project

- `git clone git@github.com:CasparCG/html-graphics-boilerplate`
- `cd html-graphics-boilerplate`
- `git remote set-url origin https://github.com/USERNAME/REPOSITORY.git`
- modify `package.json`
- `npm i`

## Development

- `npm run dev`
- `open http://localhost:8080` or `CG 1 ADD http://localhost:8080/index.html 1`

## Building

- `npm run build` 
- Files are written to `dist`

## Emulating Caspar

Templates in Caspar will ignore web security features, such as blocking responses with empty `Access-Control-Allow-Origin` headers from being handled in code. To emulate this, you can disable web security features in your local browser using e.g. `--args --disable-web-security`.
