# 🌤️ Widget de Previsão do Tempo - Santo Amaro, SP

Este projeto incorpora um **widget de clima interativo** para exibir a **previsão atual** da região de **Santo Amaro, São Paulo - SP**.

## 🔗 Widget ao vivo

Confira o widget em funcionamento aqui:  
👉 [Santo Amaro - Previsão do Tempo](https://forecast7.com/pt/n23d65n46d71/santo-amaro/)

## 🧩 Tecnologias

- [WeatherWidget.io](https://weatherwidget.io/) para exibição da previsão do tempo.
- HTML + JavaScript.

## 🛠️ Como incorporar

Para incorporar esse widget em qualquer site, use o seguinte trecho de código:

```html
<a class="weatherwidget-io" 
   href="https://forecast7.com/pt/n23d65n46d71/santo-amaro/" 
   data-mode="Current" 
   data-theme="dark" 
   data-basecolor="#1F222C">
   Santo Amaro, São Paulo - State of São Paulo, Brazil
</a>
<script>
!function(d,s,id){
  var js,fjs=d.getElementsByTagName(s)[0];
  if(!d.getElementById(id)){
    js=d.createElement(s);js.id=id;
    js.src='https://weatherwidget.io/js/widget.min.js';
    fjs.parentNode.insertBefore(js,fjs);
  }
}(document,'script','weatherwidget-io-js');
</script>
