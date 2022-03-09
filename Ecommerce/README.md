
# E-Commerce Django
## 👋🏼 Introdução
Esse repositório tem por objetivo armazenar o estudo da implementação do Projeto de E-commerce em Django do Professor Fábio Ruicci.

A autoria desse projeto é totalmente destinada ao Fábio Ruicci, podendo ser vista detalhadamente em:
>  [ Tutorial e-commerce com Django – Parte 1 - Fábio Ruicci ](https://www.youtube.com/watch?v=NZd386TfzcM&t=1367s&ab_channel=FabioRuicci)
>  [ Repositório do Tutorial ](https://github.com/fabioruicci/tutorial-e-commerce-django/tree/parte-1/setup-e-catalogo)

É válido ressaltar que houveram e haverão outras fontes ao longo desses estudos, são eles:
> [Guia Documentado do Framework Django](https://www.djangoproject.com/)
> [StackOverflow - Fórum para solução de Issues e Bugs](https://www.stackoverflow.com/)

## ✋🏽 Requisitos
Abaixo estão listado a versão Python e algumas Bibliotecas/Frameworks utilizadas no desenvolvimento dessa aplicação, não se limitando a estas: 
- Python >= 3.10.1
- Django >=3.1.3
- Factory-Boy >=3.1.0
- ipython==7.19.0
 - pytest-cov==2.10.1
 > Mais bibliotecas podem ser encontradas no arquivo " *requirements.txt* " na base do repositório.
> Para instalação de todas as blibliotecas requisitadas nesse projeto recomendo utilizar o seguinte comando:
> `$ pip install -r requirements.txt`

## 🏃🏼‍♂️ Como Rodar a Aplicação
Antes de iniciar a aplicação confira se você ja tem todos os requisitos desse repositório, você pode encontra-los em [Requisitos](#Requisitos)

Todos os requisitos satisfeitos, voce já pode iniciar o servidor desse projeto a partir do comando:
`$ python manage.py runserver`
> Verifique se você está no diretório Ecommerce deste repositório.

Pronto, você está rodando um servidor Django em sua máquina, e pode ser visto atraves da URL: 
	- https://127.0.0.1:8000/

O projeto está configurado para especificações pessoais que podem variar entre os desenvolvedores, por isso é recomendado criar seu próprio *"SuperUser(ADMIN)"* para manipulação dos Dados dos Produtos, Categorias, Preços , Moderadores , etc. Para isso utilize o seguinte comando:
`$ python manage.py createsuperuser`
`<< Username: <Seu Username>`
`<< Email: <Seu Email>`
`<< Password: <Sua Senha>`
