# **IAB Mob**

### **Uma solução integrada para cálculos de rotas e estimativas de viagem**

---

## **📌 Visão Geral**

O **IAB Mob** é um aplicativo Android projetado para simplificar a navegação e planejamento de viagens. Ele utiliza o **Google Maps** para oferecer um mapa interativo que permite aos usuários calcular rotas, estimar tempos de viagem e identificar o melhor meio de transporte entre dois locais.

---

## **✨ Funcionalidades**

- **🌐 Autenticação:**  
  Sistema de login e registro de usuários para acesso seguro.

- **🗺️ Mapa Interativo:**  
  Visualização de mapas com suporte para traçar rotas personalizadas.

- **📍 Cálculo de Rotas:**  
  Integração com a API do Google Directions para gerar rotas detalhadas.

- **⏱️ Estimativas de Tempo:**  
  Informações sobre o tempo de viagem e sugestões do melhor meio de transporte.

- **🎨 Interface de Usuário Amigável:**  
  Navegação intuitiva com telas organizadas.

---

## **💻 Tecnologias Utilizadas**

- **Linguagem:** Kotlin
- **Arquitetura:** MVVM
- **Bibliotecas:**
    - Android Jetpack (Navigation, ViewModel, LiveData)
    - Google Maps SDK para Android
    - OkHttp para requisições de rede
    - Firebase Authentication (opcional)
- **Plataforma:** Android SDK

---

## **🔧 Pré-requisitos**

- Android Studio Arctic Fox ou superior
- Android SDK compilado para a versão 34 ou superior
- Chave de API do Google Maps

---

## **🚀 Instalação**

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/guifami/projeto-iabmob-kotlin.git
   cd projeto-iabmob-kotlin

2. **Configuração do Projeto:**
    - Abra o Android Studio e importe o projeto.
    - No arquivo `local.properties`, adicione sua chave de API do Google Maps:

      ```properties
      MAPS_API_KEY=**********************************************
      ```

3. **Sincronize o projeto** com os arquivos `build.gradle`.

4. **Execute o aplicativo** em um dispositivo ou emulador Android.

---

## **📖 Como Usar**

1. **Autenticação:**
    - Faça login com suas credenciais existentes ou registre uma nova conta.

2. **Mapa e Cálculo de Rotas:**
    - Insira a localização de partida e destino nos campos apropriados.
    - Clique no botão **"Calcular Rota"** para visualizar as rotas e estimativas no mapa.

3. **Resultados:**
    - Acesse a aba **"Resultados"** para obter detalhes sobre a viagem estimada e sugestões de transporte.
