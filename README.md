# Tradutor Sagui / Humano 🐵🎙️

Um projeto de Ciência de Dados e Bioacústica Computacional estado-da-arte, criado para classificação, mapeamento 3D e **tradução em tempo real** de vocalizações de saguis (*Callithrix jacchus*).

## O Grande Desafio (A Ciência SOTA - State of the Art)
Ao contrário de abordagens clássicas baseadas apenas em visualização de espectrogramas e Deep Learning bruto (que falharam devido ao Overfitting intenso na densidade local de ruídos naturais), nós re-projetamos a modelagem sônica do zero.

Para quebrar o teto da "Acurácia Média", combinamos:
- **Extração Rítmica Musical:** 100 Super-Features focadas na densidade dos pixels invisíveis de áudio (MFCCs, Chromagramas Musicais e Espectrogramas de Contraste).
- **Escalonamento Esculpido:** Normalização padronizada (`StandardScaler`) crucial para o *Support Vector Machine (SVM)* digerir as métricas.
- **Biologia Evolutiva:** Agrupamento nativo de sub-classes (ex: Phee_2 com Phee_3) baseadas na mesma classe de emoção do macaco, destruindo o t-SNE cego anterior.
- **Gravidade Direcional (LDA):** Máquina de achatamento preditivo que afasta magicamente os áudios e amontoa as emoções parecidas isoladamente no espaço visual em 3D.

## O Produto: Tradutor Símio ao Vivo 📱
Livre das abstrações de tabelas de avaliação métrica, incorporamos um aplicativo interativo dentro de nosso fluxo Python:
Ao rodar as bibliotecas gráficas `ipywidgets`, e ligar módulos como o `sounddevice`, nós transformamos nosso Notebook em um gravador real. \nVocê consegue falar no Microfone da Máquina, aplicar um **Filtro de Ruído Interno da Placa (Noise Gate)** e assistir as ondas do gogó serem traduzidas pra sentenças símias na tela!

<img width="1007" height="183" alt="Captura de Tela 2026-03-27 às 13 33 50" src="https://github.com/user-attachments/assets/e3f4894d-27e5-4766-aedb-2ed70dc2ecdc" />

<img width="989" height="550" alt="Captura de Tela 2026-03-27 às 13 33 06" src="https://github.com/user-attachments/assets/31a16e62-2422-4285-b6b6-c30772a456bb" />

## Estrutura do Repositório
- `audios/`: Classes originais separadas em 11 diretórios brutais (*Tsik, Trill, Alarm, etc*).
- `dataset_split/`: Balanceamento limpo de validação cruzada para testes robustos.
- `notebooks/04_Kaggle_Professional_Grade.ipynb`: Pipeline Principal, Storytelling e Terminal Vivo. Este é todo o ecossistema necessário pra dominar o repo.
- `estrutura_projeto.json`: Meta-data base geradora do overview de pastas originárias.

---
_A natureza não fala em binário, mas agora a gente escuta a matemática dela. 🏆_
