# Projeto Fourier, FFT, Filtragem e Laplace

**Integrante:** Bruno de Cunto Rezende

Notebook para Google Colab que demonstra:
1. Série trigonométrica e complexa de Fourier para onda quadrada, incluindo fenômeno de Gibbs.
2. FFT de áudio musical real enviado pelo usuário.
3. Filtro passa-baixas Butterworth e reconstrução por IFFT.
4. Modelo analógico H(s), polos, zeros, resposta em frequência e estabilidade.

## Como executar
1. Abra `Projeto_Fourier_FFT_Laplace.ipynb` no Google Colab.
2. Execute as células em ordem.
3. Na etapa 2, envie um arquivo WAV. Se necessário, converta o áudio para WAV com o Audacity.
4. Observe os gráficos e personalize as interpretações com os valores obtidos no seu áudio.
5. A etapa 3 gera `audio_filtrado.wav`.

## Arquivos
- `Projeto_Fourier_FFT_Laplace.ipynb`: notebook executável.

## Observação
O áudio deve ser próprio ou ter licença que permita o uso e a redistribuição. O filtro pode remover harmônicos musicais úteis, além de ruído. Escolha a frequência de corte após inspecionar o espectro.
