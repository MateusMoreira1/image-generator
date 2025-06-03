# 🤖 AI Image Generator

Este é um aplicativo Flutter que gera imagens a partir de descrições em texto (**prompts**) utilizando o modelo **Stable Diffusion** da Hugging Face. Com uma interface moderna e responsiva, o app oferece suporte a temas claro e escuro, personalização de parâmetros de geração e é compatível com Flutter Web.

---

## 📁 Estrutura do Projeto

```
lib/
├── main.dart                 # Arquivo principal do app
├── screens/
│   └── home_screen.dart      # Tela principal com a interface e botões
└── services/
    └── api_service.dart      # Lógica de requisição à API de geração
```

---

## 📦 Instalação e Execução

### 1. Clone o repositório

```bash
git clone https://github.com/MateusMoreira1/image-generator.git
cd image-generator
```

### 2. Instale as dependências

```bash
flutter pub get
```

### 3. Execute no emulador ou dispositivo físico

```bash
flutter run
```

### 4. Execute como app web (Flutter Web)

```bash
flutter run -d chrome
```

💡 **Dica**: Para gerar a build web (pasta `build/web`):

```bash
flutter build web
```

Essa versão pode ser hospedada em:

- GitHub Pages  
- Vercel  
- Netlify  
- Firebase Hosting  

---

## ⚙️ Funcionalidades

- ✅ Entrada de texto para **prompt** da imagem  
- ✅ Ajuste de parâmetros como `guidance_scale` e `negative_prompt`  
- ✅ Alternância entre tema claro e escuro  
- ✅ Geração de imagem com feedback visual  
- ✅ Interface moderna e responsiva
- ✅ Compatível com Flutter Web  

---

## 📷 Como Usar

1. Digite um prompt (ex: *"A fantasy castle in the clouds"*)  
2. Ajuste os parâmetros de geração, se desejar  
3. Toque em **Gerar Imagem**  
4. Visualize a imagem gerada diretamente no app  

---

## 🛠 Tecnologias Utilizadas

- Flutter 3.x  
- Dart  
- Hugging Face API  
- Modelo: Stable Diffusion (via Diffusers)  
- Flutter Web  

---

## ✅ Requisitos

- Flutter SDK (versão 3.10 ou superior recomendada)  
- Acesso à internet  
- Chave de API válida da Hugging Face (já configurada no código)  

---

## 📼 Demonstração em Vídeo

🎥 Assista à demonstração do app no vídeo abaixo:

https://github.com/user-attachments/assets/9391c5ff-6acc-4f47-a1a2-4fd40ca01e71


---

## 🌍 Teste Online

Você pode testar a aplicação diretamente no navegador:

🔗 [Acessar versão web](https://image-generator-seven-vert.vercel.app/)

---

## 🧠 Sobre o Projeto

Este projeto foi desenvolvido por **Mateus Moreira** como parte de um estudo prático sobre:

- Desenvolvimento mobile e web com Flutter  
- Integração com APIs externas  
- Inteligência Artificial Generativa  
- Boas práticas de UI/UX com Material Design 3  

---

## 📜 Licença

Este projeto é de uso livre para fins educacionais.  
Para fins comerciais, consulte os termos de uso da Hugging Face e do modelo Stable Diffusion.
