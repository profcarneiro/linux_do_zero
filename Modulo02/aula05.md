# 🐧 MÓDULO 02 – PRIMEIROS PASSOS NO LINUX

# 🟢 Aula 05 – Entendendo Arquivos e Pastas no Linux

---

## 📌 Descrição Geral

Uma das primeiras dificuldades de quem migra do Windows para o Linux não é instalar programas ou configurar o sistema.

É encontrar as coisas.

Muitos usuários ficam perdidos ao abrir o gerenciador de arquivos pela primeira vez e perceber que não existe:

```text
C:
D:
E:
```

como no Windows.

Nesta aula vamos entender como o Linux organiza arquivos e diretórios, conhecer as principais pastas do sistema e aprender a navegar pelo Linux Mint de forma natural e segura.

---

## 🎯 Objetivos de Aprendizagem

Ao final desta aula você será capaz de:

- Entender como o Linux organiza seus arquivos
- Navegar pelas pastas do sistema
- Identificar sua pasta pessoal
- Conhecer as principais pastas Linux
- Trabalhar com arquivos ocultos
- Utilizar dispositivos externos
- Compactar e descompactar arquivos
- Organizar melhor seus documentos

---

# 🤔 Como o Linux Organiza os Arquivos?

No Windows normalmente trabalhamos com algo parecido com:

```text
C:\Usuários\Jorge
```

ou

```text
D:\Filmes
```

No Linux a lógica é diferente.

Tudo começa em um único ponto chamado:

```text
/
```

Esse símbolo é conhecido como:

> Diretório raiz (root)

Ele é o topo da estrutura de pastas.

Tudo o que existe no sistema fica dentro dele.

---

# 🌳 A Estrutura em Árvore

O Linux organiza os arquivos como uma árvore.

Exemplo:

```text
/
├── home
│   └── jorge
│       ├── Documentos
│       ├── Downloads
│       └── Imagens
│
├── boot
├── etc
├── usr
├── var
└── media
```

Observe que:

- A raiz é o ponto inicial
- Todas as demais pastas ficam abaixo dela
- Não existem várias unidades independentes como no Windows

---

# 🏠 Sua Pasta Pessoal

A pasta mais importante para o usuário comum é:

```text
/home
```

Ela funciona de forma semelhante a:

```text
C:\Users
```

do Windows.

Dentro dela ficam os usuários do sistema.

Exemplo:

```text
/home/jorge
```

ou

```text
/home/aluno
```

---

## O que fica na sua pasta pessoal?

Praticamente todos os seus arquivos.

Exemplo:

```text
Documentos
Downloads
Imagens
Vídeos
Músicas
Área de Trabalho
```

É aqui que você deve trabalhar na maior parte do tempo.

📌 Regra simples:

> Se você está começando no Linux, praticamente tudo o que precisa fazer estará dentro da sua pasta pessoal.

---

# 📂 Conhecendo as Pastas do Usuário

## 📄 Documentos

Armazena:

- Trabalhos
- PDFs
- Planilhas
- Arquivos do LibreOffice

---

## ⬇️ Downloads

Armazena:

- Arquivos baixados da internet
- Instaladores
- Imagens ISO

---

## 🖼️ Imagens

Armazena:

- Fotos
- Wallpapers
- Capturas de tela

---

## 🎵 Músicas

Armazena:

- MP3
- Áudios
- Podcasts

---

## 🎞️ Vídeos

Armazena:

- Filmes
- Gravações
- Vídeos pessoais

---

## 🖥️ Área de Trabalho

Equivale ao Desktop do Windows.

Tudo que aparece visualmente sobre a área de trabalho é armazenado nesta pasta.

---

# 🧭 Navegando com o Nemo

O Linux Mint utiliza o gerenciador de arquivos chamado:

```text
Nemo
```

Ele é equivalente ao:

- Windows Explorer
- Explorador de Arquivos

Com ele você pode:

✅ Criar pastas

✅ Copiar arquivos

✅ Renomear documentos

✅ Excluir arquivos

✅ Conectar pendrives

✅ Compactar arquivos

---

# 📍 Barra Lateral do Nemo

Na lateral esquerda normalmente encontramos:

```text
Pasta Pessoal
Documentos
Downloads
Imagens
Vídeos
Lixeira
Dispositivos
Rede
```

Esses atalhos facilitam o acesso aos arquivos mais utilizados.

---

# 🔧 Pastas do Sistema

Além da sua pasta pessoal existem diretórios que pertencem ao sistema operacional.

Você verá eles ao acessar a raiz:

```text
/
```

---

## 🚀 /boot

Contém arquivos necessários para iniciar o Linux.

Exemplo:

- Kernel
- Configurações de inicialização

⚠️ Não altere esta pasta.

---

## ⚙️ /etc

Contém configurações do sistema.

Exemplos:

- Rede
- Usuários
- Serviços

Muitos arquivos importantes do Linux ficam aqui.

---

## 📦 /usr

Contém programas instalados.

É uma das maiores pastas do sistema.

Quando você instala softwares, muitos arquivos acabam armazenados aqui.

---

## 📊 /var

Armazena dados que mudam frequentemente.

Exemplos:

- Logs
- Cache
- Bancos de dados
- Serviços do sistema

---

## 🗑️ /tmp

Armazena arquivos temporários.

O sistema frequentemente limpa seu conteúdo.

---

## 💾 /media

Utilizada para montar:

- Pendrives
- HDs externos
- Cartões 