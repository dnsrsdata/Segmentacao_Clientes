<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a id="ir-para-o-topo"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]](https://github.com/dnsrsdata/Segmentacao_Clientes/graphs/contributors)
[![Forks][forks-shield]](https://github.com/dnsrsdata/Segmentacao_Clientes/network/members)
[![Stargazers][stars-shield]](https://github.com/dnsrsdata/Segmentacao_Clientes/stargazers)
[![Issues][issues-shield]](https://github.com/dnsrsdata/Segmentacao_Clientes/issues)
[![MIT License][license-shield]](https://github.com/dnsrsdata/Segmentacao_Clientes/blob/main/LICENSE)
[![LinkedIn][linkedin-shield]](https://linkedin.com/in/daniel-soares-ti/)



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/dnsrsdata/Segmentacao_Clientes">
    <img src="reports\figures\sprocket_central_logo.png" alt="Logo" width="400" height="200">
  </a>

<h3 align="center">Segmentação de clientes</h3>

  <p align="center">
    Esse é um projeto proposto pela KPMG no seu programa de estágio virtual, 
    <a href="https://www.theforage.com/virtual-internships/theme/m7W4GMqeT3bh9Nb2c/KPMG-Data-Analytics-Virtual-Internship?ref=f4zKKwjBnfFejpimF">
        confira aqui
    </a>
    <br />
    <a href="https://github.com/dnsrsdata/Segmentacao_Clientes"><strong>Explore a documentação »</strong></a>
    <br />
    <br />
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Conteúdo</summary>
  <ol>
    <li>
      <a href="#descrição-do-problema">Descrição do Problema</a>
      <ul>
        <li><a href="#tecnologias-utilizadas">Tecnologias utilizadas</a></li>
      </ul>
    </li>
    <li>
      <a href="#começando">Começando</a>
      <ul>
        <li><a href="#pré-requisitos">Pré-requisitos</a></li>
        <li><a href="#instalação">Instalação</a></li>
      </ul>
    </li>
    <li><a href="#resultados">Resultados</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#licença">Licença</a></li>
    <li><a href="#contato">Contato</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## Descrição do problema
[![Product Name Screen Shot][product-screenshot]](reports\figures\analysis-gf95ba779d_640.jpg)

A Sprocket Central Pty Ltd, uma organização de bicicletas e acessórios de ciclismo de tamanho médio, 
precisa de ajuda com seus dados de clientes e transações. A organização tem um grande conjunto de dados relacionados a seus clientes, 
mas sua equipe não sabe como analisá-lo efetivamente para ajudar a otimizar sua estratégia de marketing.

A Sprocket Central Pty Ltd também possui uma lista de 1.000 clientes em potencial com seus dados demográficos e atributos. 
No entanto, esses clientes não têm histórico de transações anteriores com a organização.
A equipe de marketing da Sprocket Central Pty Ltd tem certeza de que, se analisados ​corretamente, 
os dados revelariam informações úteis sobre os clientes que poderiam ajudar a otimizar a alocação de 
recursos para marketing direcionado, concentrando-se em consumidores que poderiam dar um alto retorno.
    
Além disso, a empresa espera a exibição dos resultados da análise em um painel com no máximo de 3 visualizações/guias.

<p align="right">(<a href="#ir-para-o-topo">Ir para o topo</a>)</p>



### Tecnologias utilizadas

* [![Python][Python]][Python-url]
* [![PBI][PowerBI]][pbi-url]
* [![VSCode][vscode]][vscode-url]

<p align="right">(<a href="#ir-para-o-topo">Ir para o topo</a>)</p>



<!-- GETTING STARTED -->
## Começando

Siga os passos para conseguir reproduzir o projeto localmente.
Para conseguir uma cópia do mesmo, siga os passos abaixo.

### Pré-requisitos

A versão Python utilizada neste projeto é a 3.9.13.
* Pip (Windows)
  ```sh
  py get-pip.py
  ```
* Virtual Env (Opcional)
  ```sh
  pip install virtualenv
  ```

### Instalação

1. Crie e ative um ambiente virtual (Opcional)
2. Clone o repositório
   ```sh
   git clone https://github.com/dnsrsdata/Segmentacao_Clientes.git
   ```
3. Instale os pacotes
   ```sh
   pip install -r requirements.txt
   ```

<p align="right">(<a href="#ir-para-o-topo">Ir para o topo</a>)</p>



<!-- ROADMAP -->
## Roadmap

- [✔️] Entendimento dos dados e do problema de negócio
- [✔️] Análise exploratória
- [✔️] Limpeza dos dados
- [✔️] Feature Engineering
- [✔️] Construção do modelo
- [✔️] Aplicação de rótulo nos dados dos potenciais clientes
- [✔️] Construção de dashboard no PowerBI
- [❌] Modularização do código
- [❌] Deploy do modelo



<p align="right">(<a href="#ir-para-o-topo">Ir para o topo</a>)</p>



<!-- USAGE EXAMPLES -->
## Resultados

Durante a análise dos dados dos clientes fornecidos pela empresa, foram produzidas algumas visualizações tendo como base os dados dos clientes que podem auxiliar o time de Marketing da Sprocket Central Pty Ltd na otimização da sua estratégia. atráves do gráfico abaixo, onde temos a quantidade de compras por idade, podemos perceber um volume maior de compras entre pessoas com idade entre 41 a 50 anos, mostrando que os clientes da empresa que estão nessa faixa de idade são mais ativos. 

[![chartAge][chart-age]](reports\figures\agexpast3ypurchases.png)

Já em relação ao segmento de indústria que os clientes participam, foi possível notar que o setor de manufatura, seguido pelo de serviços financeiros são onde estão os clientes que mais compraram produtos de ciclismo nos ultimos 3 anos, onde a quantidade de compras nesses dois setores somados representam 47% de todas as vendas nesse período. Se levassemos em consideração o setor da saúde, o terceiro maior, a representação passa a ser de 66% no número total de vendas, como pode ser visto abaixo.

[![chartSeg][chart-segment]](reports\figures\industcategoryxpast3ypurchases.png)

Ainda em relação ao cliente, mas dessa vez, relacionando o mesmo com o estado em que reside, percebemos que o estado de New South Wales é onde 53% de todas as vendas ocorreram nos últimos 3 anos, onde mesmo somadas, as vendas que ocorreram em outros estados ainda são inferiores em 15% se compradas com o mesmo. 

[![chartStt][chart-state]](reports\figures\statexpast3ypurchases.png)

Tirando um pouco o foco do cliente e olhando para o produto, conseguimos ver que a marca Solex é a mais popular, vendendo em média 36% a mais do que as outras marcas.

[![chartBrd][chart-brand]](reports\figures\purchasesperbrand.png)

Além das visualizações oriundas dos dados fornecidos, também foi desenvolvido um modelo para a clusterização dos consumidores atuais da Sprocket Central Pty Ltd, onde houve uma divisão dos mesmos em dois grupos, sendo registrado um número de compras 170% maior do grupo 1 em relação ao grupo 2 e uma quantidade de custos necessários para a fabricação dos itens 10% menor do primeiro grupo em relação ao segundo, mostrando que o grupo 1, além de consumir bem mais (1,7X) do que o grupo 2, também mostrou ser melhor em relação aos custos de fabricação dos itens. A construção de tal modelo teve como objetivo segmentar uma lista de clientes em potencial, buscando aqueles com características semelhantes aos consumidores do primeiro grupo, que foi julgado ser o melhor. Da lista com 1000 pessoas, 506 foram identificadas como clientes com características semelhantes ao do melhor grupo. O resumo apresentado em uma Dashboard pode ser conferido abaixo.

[![chartpbi][chart-pbi]](reports\figures\dash_pbi.PNG)


<p align="right">(<a href="#ir-para-o-topo">Ir para o topo</a>)</p>

<!-- LICENSE -->
## Licença

Distribuído sob a licença MIT. Veja `LICENSE.txt` para mais informações.

<p align="right">(<a href="#ir-para-o-topo">Ir para o topo</a>)</p>



<!-- CONTACT -->
## Contato

Daniel Soares -  danielsoares.data@outlook.com

Outros projetos: [https://github.com/dnsrsdata?tab=repositories](https://github.com/dnsrsdata?tab=repositories)

<p align="right">(<a href="#ir-para-o-topo">Ir para o topo</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/dnsrsdata/Segmentacao_Clientes.svg?style=for-the-badge
[contributors-url]: https://github.com/dnsrsdata/Segmentacao_Clientes/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/dnsrsdata/Segmentacao_Clientes.svg?style=for-the-badge
[forks-url]: https://github.com/dnsrsdata/Segmentacao_Clientes/network/members
[stars-shield]: https://img.shields.io/github/stars/dnsrsdata/Segmentacao_Clientes.svg?style=for-the-badge
[stars-url]: https://github.com/github_username/repo_name/stargazers
[issues-shield]: https://img.shields.io/github/issues/dnsrsdata/Segmentacao_Clientes.svg?style=for-the-badge
[issues-url]: https://github.com/github_username/repo_name/issues
[license-shield]: https://img.shields.io/github/license/dnsrsdata/Segmentacao_Clientes.svg?style=for-the-badge
[license-url]: https://github.com/dnsrsdata/Segmentacao_Clientes/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/daniel-soares-ti
[product-screenshot]: reports\figures\como-segmentar-leads.jpg
[Python]: https://img.shields.io/badge/Python-000000?style=for-the-badge&logo=python&logoColor=yellow
[Python-url]: https://www.python.org/
[PowerBI]: https://img.shields.io/badge/Power_BI-000000?style=for-the-badge&logo=powerbi&logoColor=yellow
[pbi-url]: https://powerbi.microsoft.com/pt-br/
[vscode]: https://img.shields.io/badge/Visual_Studio_Code-000000?style=for-the-badge&logo=visualstudiocode&logoColor=blue
[vscode-url]: https://code.visualstudio.com/
[chart-age]: reports\figures\agexpast3ypurchases.png
[chart-segment]: reports\figures\industcategoryxpast3ypurchases.png
[chart-state]: reports\figures\statexpast3ypurchases.png
[chart-brand]: reports\figures\purchasesperbrand.png
[chart-pbi]: reports\figures\dash_pbi.PNG