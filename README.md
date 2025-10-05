# Jogo da Bolinha 3D

Um pequeno jogo 3D feito no Unity (Windows build). Este repositório/entrega contém o executável e os recursos necessários para jogar, além deste README com **descrição**, **controles**, **história**, **vídeo de gameplay** e **prints**.

---

## 📜 Descrição do Jogo
Controle uma bolinha em um cenário 3D com plataformas e obstáculos. O objetivo é **coletar itens**, **desviar de perigos** e **chegar ao ponto final** no menor tempo possível, mantendo o controle da física da bola em rampas e curvas.

- **Gênero:** arcade / plataforma com física
- **Perspectiva:** câmera em terceira pessoa acompanhando a bolinha
- **Objetivo principal:** concluir a fase coletando todos os itens (ou alcançando a bandeira/final) sem cair

> Observação: se a sua build incluir múltiplas fases, a cada conclusão um novo nível é carregado automaticamente.

---

## 🎮 Controles
- **W, A, S, D** *ou* **Setas** → mover/rolar a bolinha  
- **Mouse** → movimentar a câmera
- **Espaço** → pular (se habilitado)
- **R** → reiniciar a fase (se habilitado)
- **Esc** → pausar/sair do jogo

> Dica: a movimentação é influenciada pela física da Unity. Acelerações bruscas podem fazer a bolinha perder controle em rampas.

---

## 🧭 História (Lore)
Em um laboratório de testes de física, um protótipo de esfera inteligente ganhou consciência e deseja escapar para o mundo exterior. Para isso, ela precisa atravessar pistas de ensaio cheias de **plataformas móveis**, **rampas** e **desafios de equilíbrio**. A cada etapa concluída, a bolinha desbloqueia um novo setor do laboratório, aproximando-se da liberdade.

---

## ▶️ Vídeo do jogo em execução (Gameplay)
Inclua aqui o link para o vídeo de gameplay (YouTube, Google Drive, etc.).

**Link:** _(substitua esta linha pelo URL do vídeo)_

Exemplo de embed Markdown (YouTube):
```
[Assista ao gameplay no YouTube](https://youtu.be/SEU_LINK_AQUI)
```

---

## 🖼️ Prints do Jogo
Coloque suas capturas de tela na pasta `prints/` e mantenha os nomes abaixo (ou ajuste os nomes aqui conforme necessário).

| Cena | Arquivo |
|---|---|
| Menu/Start | `prints/01-menu.png` |
| Jogo (fase) | `prints/02-fase.png` |
| Obstáculo | `prints/03-obstaculo.png` |
| Vitória/Derrota | `prints/04-fim.png` |

Markdown de referência para exibir cada imagem:

```
![Menu](prints/01-menu.png)
![Fase](prints/02-fase.png)
![Obstáculo](prints/03-obstaculo.png)
![Tela de Fim](prints/04-fim.png)
```

---

## 🛠️ Como executar (Windows)
1. **Extraia** todo o conteúdo do `.zip` para uma pasta local (não execute de dentro do OneDrive, se possível).  
2. Dentro da pasta, verifique a estrutura típica de build da Unity:
   ```
   Jogo da Bolinha 3D/
   ├─ Jogo da Bolinha 3D.exe
   ├─ Jogo da Bolinha 3D_Data/
   ├─ UnityPlayer.dll
   └─ UnityCrashHandler64.exe
   ```
3. Execute **`Jogo da Bolinha 3D.exe`**.

> **Importante:** o arquivo `.exe` e a pasta **`Jogo da Bolinha 3D_Data`** devem ficar lado a lado. Não mova apenas o `.exe`.

---

## ❓ Solução de Problemas
- **Erro “There should be 'Jogo da Bolinha 3D_Data' folder next to the executable”**  
  Certifique-se de que a pasta `Jogo da Bolinha 3D_Data/` esteja no **mesmo diretório** do `Jogo da Bolinha 3D.exe`. Refaça o build no Unity (`File > Build Settings > Build`) escolhendo uma **pasta vazia**.

- **Antivírus bloqueando/arquivos faltando**  
  Extraia o `.zip` com o Windows Explorer ou 7-Zip e verifique se todos os arquivos estão presentes. Adicione exceção no antivírus, se necessário.

- **OneDrive/Permissão**  
  Mova a pasta do jogo para algo como `C:\\Jogos\\Jogo da Bolinha 3D\\` e execute a partir daí.

---

## 📦 Estrutura sugerida do pacote
```
Jogo da Bolinha 3D/
├─ Jogo da Bolinha 3D.exe
├─ Jogo da Bolinha 3D_Data/
├─ UnityPlayer.dll
├─ UnityCrashHandler64.exe
├─ README.md
└─ prints/
   ├─ 01-menu.png
   ├─ 02-fase.png
   ├─ 03-obstaculo.png
   └─ 04-fim.png
```
> Obs.: Este README inclui a pasta `prints/` para você colocar as imagens.

---

## ✍️ Créditos
- **Desenvolvimento:** Pedro  
- **Engine:** Unity

---

## 📄 Licença
Defina a licença do projeto conforme sua necessidade (ex.: MIT, CC-BY-NC ou “Todos os direitos reservados”).
