# aula_bootstrap
Projeto desenvolvido como aula prática no curso de Bootstrap da Digital Innovation One.

### O que é Bootstrap?

De acordo com o site WIKIPÉDIA:
>Bootstrap é um framework web com código-fonte aberto para desenvolvimento de componentes de interface e front-end para sites e aplicações web usando HTML, CSS e JavaScript, baseado em modelos de design para a tipografia, melhorando a experiência do usuário em um site amigável e responsivo.

Bibliotecas e tecnologias utilizadas:
- Bootstrap;
- HTML5;
- CSS3;

```html
<body>

        <nav class="navbar navbar-expand-lg navbar-light" margin>
            <a class="navbar-brand" href="#">
                <img src="img/globallabs.jpg" width="220" height="80">
            </a>
            <div class="collapse navbar-collapse">
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <a class="nav-link" href="#quemsomos">Quem somos</a>
                    </li>

                    <li class="nav-item">
                        <a class="nav-link" href="#parceiros">Parceiros</a>
                    </li>

                    <li class="nav-item">
                        <a class="nav-link" href="#servicos">Serviços</a>
                    </li>
                </ul>
                        
             
            </div>
           
                   
        </nav>   
```

```css
body{
    font: 20px Arial, sans-serif
}

.navbar {
    background-color: rgb(255, 255, 255);
}

.quem-somos{
    background-color: #848484;
    color: white;
}

.margin{
    padding-bottom: 50px;
    padding-top: 10px;
}

.parceiros{
    background-color: #5882FA;
    color: white;
}

.servicos{
    background-color: white;
    color: #5882FA;
}

.bg-footer{
    background-color: tomato;
    color: white;
}
```
### Telas do Projeto

#### Topo da Página
![](https://i.imgur.com/uo5DTuA.png)

#### Corpo da Página
![](https://i.imgur.com/8OezfkO.png)

#### Rodapé da Página
![](https://i.imgur.com/XxdkVFG.png)
