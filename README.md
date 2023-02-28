
<h1>Detecção de objetos usando Mask R-CNN</h1>
<p>Mask R-CNN é um modelo de detecção de objetos baseado em redes neurais convolucionais profundas (CNN)..</p>

<h2>Mascaramento </h2>
<p>é uma maneira de dizer camadas de processamento de sequências que certos Timesteps em uma entrada estão em falta, e, portanto, devem ser ignoradas ao processar os dados.</p>

<h2>Estofamento </h2>
<p> é uma forma especial de mascaramento em que os passos são mascarados no início ou no fim de uma sequência. O preenchimento vem da necessidade de codificar dados de sequência em lotes contíguos: para fazer com que todas as sequências em um lote se ajustem a um determinado comprimento padrão, é necessário preencher ou truncar algumas sequências.</p>

<h2>Exemplo</h2>
<p>Uso do banco dados publico do TensorFlow.</p>

<img src="https://user-images.githubusercontent.com/67292251/221888189-fd5eadd9-ec10-4411-a7d7-727f45b934ec.png" alt="Example Image">

<h2>Predição da Mask</h2>
<img src="https://user-images.githubusercontent.com/67292251/221888646-b0aec970-1af3-4258-8e0f-ba4df7520c37.png" alt="Example Image">


<h2>Treinamendo e Validação de perda </h2>
<img src="https://user-images.githubusercontent.com/67292251/221889280-1ef242a1-7188-4939-a38d-fd558a483bff.png" alt="Example Image">


<h2>Aplicação em imagens aleatórias</h2>

<p>2/2 [==============================] - 1s 704ms/step</p>
<img src="https://user-images.githubusercontent.com/67292251/221893293-822bf0c0-865b-490f-ad36-f1f6c700de05.png" alt="Example Image">
<p>2/2 [==============================] - 2s 821ms/step</p>
<img src="https://user-images.githubusercontent.com/67292251/221893545-913b3717-6084-4b40-ae62-a84d3691dc64.png" alt="Example Image">
<p>2/2 [==============================] - 2s 881ms/step</p>
<img src="https://user-images.githubusercontent.com/67292251/221893700-347a639d-e888-4021-889b-98351092151e.png" alt="Example Image">


