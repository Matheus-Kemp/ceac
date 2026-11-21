# CEAC

Site do TFG "Entre o Legado e a Continuidade": requalificação do CEAC de Iracemápolis-SP. Matheus Kemp, Arquitetura e Urbanismo, 2026.

No ar em https://matheus-kemp.github.io/ceac/

Fotos: `fotos/matheus-kemp.jpg` e `fotos/daniel-andrioli.jpg` (retrato 4:5).

Galeria (seção 06): duas listas que abrem a mesma tela cheia. `ul.galeria` (Imagens) é o mosaico de renders: o primeiro item tem a classe `destaque`, aparecem seis (cinco no celular) e o último mostra "+N Ver todas". `ul.pranchas` (Pranchas) mostra um quadro por folha: o primeiro desenho de cada folha tem a classe `folha-capa` e uma legenda `<p class="folha"><span>Folha NN</span>Nome</p>`; os outros desenhos da folha ficam escondidos na grade e só aparecem na tela cheia, em sequência. Cada imagem é um `.quadro` com `<img src="galeria/nome-mini.jpg" data-grande="galeria/nome.jpg" alt="...">` e o título em `<span class="titulo-quadro"><strong>...</strong></span>` (só para leitor de tela e para a legenda da tela cheia). `-mini` tem até 1100 px; a versão grande, até 2600 px. Itens com a classe `desenho` aparecem inteiros, sem corte, sobre fundo branco. As imagens de 21/11/2026 vêm dos renders do Lumion de 20/11 e de recortes do PDF final das pranchas (dez folhas).
