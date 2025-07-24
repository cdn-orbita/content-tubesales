# 📄 Descrição
Content Delivery Network (cdn) para Órbita Marketing Digital Ltda. servindo a Tube Sales.

> Para acessar as imagens, utilizamos jsDelivr: https://www.jsdelivr.com/
> 
> Documentação: https://www.jsdelivr.com/documentation

# ⚠️ Requisitos
> Conta autorizada para modificar o repositório local (content-viviane). Contate um programador para lhe dar permissões.
> 
> O repositório precisa ser público para que isto funcione.

# 📌 Tutorial (em inglês)
```
https://www.youtube.com/watch?v=aBzhq9V2WAg
```

# 📂 Inserindo imagens
### </> Vincule uma pasta dedicada para conter um acesso ao repositório.
Exemplo:
```
F:/Desktop/git/repositorio
```

### </> Vincule pelo console cmd usando:
```
git init
git remote add origin https://github.com/cdn-orbita/content-viviane.git
```

Faça login no github para confirmar permissões e poder começar a enviar imagens.

Insira a imagem a ser enviada na pasta dedicada mencionada anteriormente.

### </> Agora dê upload utilizando:
```
git add nome-da-imagem.ext
git commit -m "mensagem teste de commit"
git push
```

### </> Atualização: se o GitHub estiver usando a branch master ao invés da main:
Para ver qual é o nome da sua branch:
```
git branch
```

Caso sua branch esteja na master ao invés da main (note que o repositório atual está na branch main e não master!):
- Defina o nome da branch atual de master para main, e dê push para a branch main.
```
git branch -m master main
git push -u origin main
```

# 🔭 Acessar imagens do repositório
### 🔗 Link rápido:
```
https://cdn.jsdelivr.net/gh/cdn-orbita/content-tubesales/nome-do-audio.ext
```

### 🔗 Modelo do link para acessar a imagem do repositório:
```
https://cdn.jsdelivr.net/gh/username/repositorio/nome-do-audio.ext
```
