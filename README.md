# Plataforma VidFlow

Projeto desenvolvido durante o curso da Alura, formação em JS, onde é possível navegar em uma plataforma de vídeos de tecnologia, buscar vídeos através da barra de pesquisa e filtrar através dos botões por categorias.

A partir de um HTML e CSS bases, foi utilizado o **JSON Server** para servir uma **API fake** e consumir os dados referentes aos vídeos para o projeto, indicandos ao servidor que deveria ficar observando o arquivo .json referenciado.

    `json-server --watch backend/videos.json`

Além disso, foi feita captura e tratamento de erros com **try/.catch** e o código assíncrono foi refatorado com `Async/await`