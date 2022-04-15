# Welcome

It is a POC for injecting assembled C code to website.

# Requirements

- git
- nodejs
- installed `emcc` ~ https://emscripten.org/docs/getting_started/downloads.html

# How To

- clone this project and inside project dir run:
- `npm install` ~ installs http server needed to bypass local hosting cors block
- `emcc main.c -o index.html` ~ creates template html with out code injected
- `npm start` ~ starts the server on `http://127.0.0.1:8080`
