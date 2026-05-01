# 📱 Estudos de Programação para Dispositivos Móveis

Este repositório contém anotações e resumos da disciplina de **Programação para Dispositivos Móveis**, organizados por unidades.

---

# 🧩 Unidade 1 — Fundamentos do Desenvolvimento Mobile

## 📌 Apresentação da Disciplina
- Plano de ensino:
  - Objetivos
  - Conteúdos
  - Estratégias
  - Avaliação
  - Bibliografia

---

## 🚀 Principais Tecnologias para Desenvolvimento Mobile

### 🌐 Progressive Web App (PWA)
- Aplicações web que se comportam como apps
- Executadas no navegador
- Podem ser instaladas no dispositivo
- Tecnologias:
  - HTML
  - CSS
  - JavaScript

---

### 🤖 Android (Desenvolvimento Nativo)
- Sistema operacional do Google
- Presente na maioria dos smartphones e tablets
- Linguagens utilizadas:
  - Java
  - Kotlin

---

### 🍎 iOS (Desenvolvimento Nativo)
- Sistema operacional da Apple
- Presente em iPhones e iPads
- Linguagens utilizadas:
  - Swift (principal)
  - Objective-C (legado / descontinuado)

---

### 🔄 Desenvolvimento Híbrido

#### ⚛️ React Native
- Framework mantido pela Meta (Facebook)
- Permite desenvolvimento para Android e iOS
- Linguagem:
  - JavaScript

---

#### 💙 Flutter
- Framework mantido pelo Google
- Permite desenvolvimento para Android e iOS
- Linguagem:
  - Dart

---

## 🧠 Comparativo Geral

| Tipo | Plataforma | Linguagem |
|------|-----------|----------|
| PWA | Web | HTML, CSS, JavaScript |
| Android | Google | Java / Kotlin |
| iOS | Apple | Swift |
| React Native | Híbrido | JavaScript |
| Flutter | Híbrido | Dart |

---

# 🛠️ Unidade 2 — Criação de Aplicativo Android

## 📲 Criação de Projeto no Android Studio

### 1. Inicialização
- Abrir o **Android Studio**

---

### 2. Criar Novo Projeto
- Selecionar a opção **New Project**

---

### 3. Escolha do Template
- Utilizar o template:
  - **Empty Views Activity**

---

### 4. Configuração do Aplicativo
Definir as seguintes informações:

- Nome do aplicativo
- Nome do pacote (ex: `com.exemplo.app`)
- Local de armazenamento do projeto
- Linguagem:
  - Java ou Kotlin
- SDK mínimo (versão mínima do Android suportada)

---

### 5. Finalização
- Clicar em **Finish**
- Aguardar a criação do projeto

---

# 📌 Observações Gerais

- Aplicações podem ser:
  - Nativas (Android / iOS)
  - Híbridas (React Native / Flutter)
  - Web (PWA)
- A escolha da tecnologia depende do objetivo do projeto
- Kotlin e Swift são as linguagens mais modernas para desenvolvimento nativo

---

# 🧩 Unidade 3 — Execução de Aplicativos e Componentes de Interface

## 📱 Executar um App em Dispositivo Físico

Para executar um aplicativo diretamente em um celular Android, é necessário habilitar o **modo desenvolvedor** e a **depuração USB**.

---

### 🔧 Ativando o Modo Desenvolvedor (Geral)

1. Abrir **Configurações**
2. Acessar **Sobre o dispositivo**
3. Localizar **Número da versão** (ou número da compilação)
4. Pressionar várias vezes até ativar o modo desenvolvedor

---

### 🔌 Habilitar Depuração USB

1. Voltar para **Configurações**
2. Acessar **Opções do Desenvolvedor**
3. Ativar **Depuração USB**

---

### ▶️ Executar o App

1. Conectar o celular ao computador via USB
2. Abrir o projeto no **Android Studio**
3. Selecionar o dispositivo físico
4. Executar o aplicativo

---

## 📲 Procedimento (Celulares mais recentes — Ex: Galaxy S20)

1. Abrir **Configurações**
2. Ir em **Sobre o telefone**
3. Acessar **Informações de Software**
4. Pressionar **7 vezes** em **Número de Compilação**
5. Retornar para **Configurações**
6. Rolar até o final
7. Acessar **Opções do Desenvolvedor**
8. Ativar **Depuração USB**

---

## 🧱 Componente de Interface: ScrollView

### 📌 O que é?

O **ScrollView** é um componente utilizado para permitir **rolagem de tela** quando o conteúdo é maior que o espaço visível.

---

### 🎯 Para que serve?

- Exibir conteúdos longos
- Permitir navegação vertical
- Melhorar a experiência do usuário em telas pequenas

---

### ⚙️ Características

- Permite rolagem **vertical**
- Aceita apenas **um elemento filho direto**
- Usado geralmente com:
  - LinearLayout
  - ConstraintLayout

---

### 💡 Exemplo de uso (conceitual)

Um formulário grande ou uma lista de informações que não cabem na tela.

---

# 📌 Observações Gerais

- A depuração USB é essencial para testes reais no dispositivo
- O uso de dispositivos físicos ajuda a validar desempenho e comportamento do app
- ScrollView deve ser usado com cuidado para evitar problemas de performance

---

# 🧩 Unidade 4 — Recursos de Interface e Conceitos Fundamentais

## 🖼️ Inserir Imagem no Aplicativo

Para adicionar imagens ao projeto Android, utiliza-se o **Resource Manager**.

---

### 📂 Caminho para Importação

- Menu **View**
- **Tool Windows**
- **Resource Manager**

---

### 📥 Parte 1 — Importação

1. No **Resource Manager**
2. Clique em **+**
3. Selecione **Import Drawables**
4. Escolha as imagens desejadas
5. Clique em **OK**

---

### ⚙️ Parte 2 — Configuração

1. Escolher:
   - **Qualifier Type**
   - **Value**
2. Clicar em **Next**
3. Verificar o diretório de destino
4. Clicar em **Import**

---

## 🧱 Exibição da Imagem (ImageView)

Para exibir a imagem no layout:

- Utilizar o componente **ImageView**
- Definir a propriedade:


---

## 📏 Dimensionamento de Layout

### 📌 match_parent

- O elemento ocupa **todo o espaço disponível** do elemento pai

---

### 📌 wrap_content

- O elemento ocupa **apenas o espaço necessário** para seu conteúdo

---

### ⚖️ Diferença entre eles

| Propriedade | Comportamento |
|------------|--------------|
| match_parent | Expande para preencher o container |
| wrap_content | Ajusta automaticamente ao conteúdo |

---

## 🧾 XML no Android

### 📌 O que é?

XML (eXtensible Markup Language) é uma linguagem de marcação utilizada para definir a **estrutura da interface gráfica** no Android.

---

### 🎯 Para que serve?

- Criar layouts (telas)
- Organizar componentes visuais
- Separar a interface da lógica do código

---

## ⚙️ Gradle

### 📌 O que é?

Gradle é um sistema de **automação de build** utilizado no Android.

---

### 🎯 Para que serve?

- Gerenciar dependências (bibliotecas)
- Compilar o projeto
- Configurar versões do SDK
- Gerar o APK/APP final

---

# 📌 Observações Gerais

- Imagens devem ser organizadas corretamente na pasta `res/drawable`
- O uso correto de `match_parent` e `wrap_content` impacta diretamente no layout
- XML define a interface, enquanto a lógica fica nas classes (Java/Kotlin)
- Gradle é essencial para o funcionamento e organização do projeto

---

# 🧩 Unidade 5 — Componentes de Interface e Navegação

## 🔘 Button (Botão)

### 📌 O que é?

O **Button** é um componente de interface utilizado para permitir que o usuário execute uma **ação ao clicar**.

---

### 🎯 Para que serve?

- Navegar entre telas
- Executar funções
- Disparar eventos (ex: abrir outra Activity)

---

## 🖼️ Inserir Ícone em um Button

É possível adicionar ícones ao botão utilizando propriedades específicas.

---

### ⚙️ Exemplo de Button com Ícones

```xml
<Button
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:text="Ir para Segunda Activity"
    android:onClick="abrirSegundaActivity"
    android:drawableLeft="@drawable/icons8_formato_100"
    android:drawableRight="@drawable/icons8_formato_100"
    android:drawableTop="@drawable/icons8_formato_100"
    android:drawableBottom="@drawable/icons8_formato_100"
    android:backgroundTint="#00040D"
/>
```

### 📌 Outro exemplo simplificado

```xml
<Button
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:drawableLeft="@drawable/icons8_teste_96"
    android:backgroundTint="#7AB7E6"
/>
```

# 📱 Activity e Componentes Relacionados

## 🔘 Observações sobre Button

- `drawableLeft`, `drawableRight`, `drawableTop`, `drawableBottom` definem a **posição do ícone** no botão  
- `backgroundTint` altera a **cor de fundo do botão**  
- `onClick` chama um **método da Activity**  

---

## 📱 Activity

### 📌 O que é?

A **Activity** é o componente responsável por representar uma **tela do aplicativo**.

---

### 🎯 Para que serve?

- Exibir interface ao usuário  
- Receber interações (toques, cliques)  
- Controlar a lógica da tela  

---

### 💡 Exemplos práticos

Em um aplicativo de e-mail:

- Uma Activity → lista de e-mails  
- Outra Activity → visualizar e-mail  
- Outra Activity → escrever novo e-mail  

---

### 🔄 Navegação entre Activities

- Uma Activity pode **iniciar outra Activity**  
- Isso permite a **navegação entre telas do aplicativo**  

---

## 🧱 Criar uma Nova Activity

### 📂 Método 1

1. Clique com botão direito em **app**  
2. Selecione:  
   - **New**  
   - **Activity**  
3. Escolha o tipo:  
   - Ex: **Empty Views Activity**  

---

### 📂 Método 2

1. Menu **File**  
2. **New**  
3. **Activity**  
4. Escolher o modelo desejado  

---

### ⚙️ Configuração da Activity

- Definir nome da Activity  
- Marcar:  
  - **Generate a Layout File**  
- Escolher linguagem:  
  - Kotlin  
- Clicar em **Finish**  

---

## 📁 Estrutura das Activities

### 📌 Onde ficam?

- **Classe da Activity:**  
  - Código (Java/Kotlin)  

- **Layout da Activity:**  
  - Arquivo XML (interface)  

---

## 📌 Observações Gerais

- Cada tela do app geralmente corresponde a uma Activity  
- Activities são responsáveis pela navegação e interação  
- Buttons são frequentemente usados para trocar de Activity  
- A separação entre **lógica (código)** e **interface (XML)** é fundamental  

---

## 🔄 Intent

### 📌 O que é?

Uma **Intent** (intenção) é a descrição de uma **ação a ser realizada** no Android.

---

### 🎯 Para que serve?

A classe **Intent** é utilizada principalmente para:

- Abrir outra tela (Activity)
- Navegar entre partes do aplicativo
- Executar ações do sistema

---

### 💡 Possibilidades de uso

Com uma Intent é possível:

- Abrir outra Activity (com ou sem envio de dados)
- Abrir uma página web no navegador
- Acessar a agenda de contatos
- Realizar uma ligação telefônica
- Interagir com recursos do dispositivo

---

## 📱 Chamar outra Activity

A navegação entre telas é feita utilizando **Intent + startActivity()**

---

### ⚙️ Exemplo (no onClick do Button)

```kotlin
val intent = Intent(this, MainActivity2::class.java)
startActivity(intent)
```

# 🧩 Unidade 6 — Comunicação com Servidores e Processamento de Dados

## 🌐 Visão Geral

Esta unidade aborda como aplicativos Android se comunicam com servidores e processam dados externos.

### 📌 Conteúdo

- Dados JSON no Android  
- Conexão HTTP  
- Classe AsyncTask  
- Integração JSON + HTTP  

---

## 🔄 Revisão — Processamento de Dados

Aplicativos móveis frequentemente:

- Fazem **requisições HTTP**
- Enviam e recebem dados de servidores
- Consomem informações em formatos como:
  - Texto
  - HTML
  - XML
  - JSON  

---

### ☁️ Exemplo de uso

- Firebase Realtime Database  
- APIs externas  
- Serviços web  

---

## 📄 Onde usar XML e JSON?

| Tecnologia | Uso |
|-----------|-----|
| XML | Interface (layouts no Android) |
| JSON | Troca de dados com servidores |

---

## 📦 JSON (JavaScript Object Notation)

### 📌 O que é?

JSON é um formato leve de troca de dados, baseado em texto.

---

### 🎯 Características

- Fácil de ler e escrever (humanos)  
- Fácil de processar (máquinas)  
- Independente de linguagem  
- Muito utilizado em APIs  

---

## 🧱 Estrutura do JSON

Um JSON pode conter:

- **Objetos** → `{ }`  
- **Arrays (vetores)** → `[ ]`  
- **Pares chave-valor** → `"chave": valor`  

---

### 💡 Exemplo conceitual

```json
{
  "funcionarios": [
    {
      "id": "01",
      "nome": "Prof. Lucas",
      "salario": 5000.0,
      "disciplinas": [
        {"cod": 1001, "nome": "Disciplina 1"},
        {"cod": 1002, "nome": "Disciplina 2"}
      ]
    }
  ]
}
```

# 🔄 Continuação — Unidade 6

## 🧵 AsyncTask (Execução Assíncrona)

### 📌 O que é?

A classe **AsyncTask** permite executar tarefas em **segundo plano** de forma simples, sem precisar gerenciar threads manualmente.

---

### 🎯 Para que serve?

- Executar operações demoradas (ex: HTTP)
- Evitar travamentos na interface (UI)
- Atualizar a tela após o processamento

---

### ⚙️ Funcionamento

Uma classe derivada de `AsyncTask` possui dois métodos principais:

---

#### 🔹 doInBackground

- Executa fora da thread principal (background)
- Responsável por:
  - Fazer requisições HTTP
  - Aguardar resposta do servidor
  - Processar dados recebidos
- É iniciado ao chamar o método:


---

#### 🔹 onPostExecute

- Executado após o término da tarefa
- Roda na thread principal (UI)
- Responsável por:
  - Atualizar a interface
  - Exibir os dados processados

---

### ⚠️ Observação Importante

- A classe **AsyncTask foi descontinuada (deprecated)** a partir da API 30 (Android 11)
- Alternativas modernas:
  - `java.util.concurrent`
  - Recursos de concorrência do Kotlin (coroutines)

---

## 📚 Bibliotecas para HTTP e JSON

Para facilitar o desenvolvimento, é comum utilizar bibliotecas prontas.

---

### 📌 Exemplo: Volley

- Biblioteca oficial do Google
- Facilita requisições HTTP
- Suporte nativo para JSON
- Integração com componentes visuais

---

### 🎯 Vantagens

- Código mais simples
- Melhor gerenciamento de requisições
- Menos controle manual de threads

---

## 🧱 Exibição de Dados

### 📌 RecyclerView

- Componente utilizado para exibir listas de dados
- Muito usado com dados vindos de APIs (JSON)

---

## 🖼️ Exemplo Adicional

Aplicativo que:

- Realiza requisições HTTP
- Recebe imagens de um servidor remoto
- Exibe imagens na tela
- Atualiza a imagem a cada clique no botão

---

## 📦 Exemplos Práticos da Unidade

### 📌 Processamento de JSON

- **ExemploJSON (ExJSON)**
  - Processa JSON local dentro do app

---

### 🌐 Requisições HTTP

- **ExemploHTTP1 (ExHttp1)**
  - Utiliza Thread
  - Retorna texto simples

- **ExemploHTTP2 (ExHttp2)**
  - Utiliza AsyncTask
  - Solução mais estruturada

---

### 🔄 Integração JSON + HTTP

- **ExemploJSON_HTTP (ExJSONHttp)**
  - Requisição HTTP
  - Retorno em JSON

- **ExemploJSONObjDentroDeObj**
  - JSON com objetos aninhados

---

### 🧪 Exercícios

- **Exercicio_aula_json (ExercJSON)**
  - Manipulação de JSON retornado por servidor

---

### 🖼️ Conteúdo Remoto

- **App1ImagemRemota**
  - Carrega imagens de um servidor web
  - Exibição dinâmica na tela

---

## 📌 Observações Gerais

- AsyncTask simplifica o uso de threads, mas está obsoleta  
- Bibliotecas como Volley facilitam muito o desenvolvimento  
- JSON é o principal formato de dados em APIs  
- Requisições HTTP devem sempre ser feitas em segundo plano  
- RecyclerView é essencial para exibir listas dinâmicas  

---
