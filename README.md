<h1>
    <img align="center" width="40px" src="https://freesvg.org/img/redhat.png">
    <span> Phishing para captura de senhas do Facebook</span>
</h1>

## Objetivo
Conseguir coletar a credencial de acesso do Facebook.

## Ferramentas
- [Kali Linux](https://www.kali.org/docs/)
- [setoolkit](https://www.kali.org/tools/set/)

## Etapas do projetos

<table>
  <thead>
    <tr align="center">
      <th>Nº</th>
      <th>Etapas</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>01</td>
      <td>Baixar Ferramentas</td>
    </tr>
    <tr>
      <td>02</td>
      <td>Instalação e configuração do ambiente</td>
    </tr>
    <tr>
      <td>03</td>
      <td>Coletando a informação</td>
    </tr>
  </tbody>
</table>

## Instalando as ferramentas

 <td>01</td> - Acessando root

```sh
sudo su
```
<td>02</td> - Iniciando o setoolkit

```sh
setoolkit
```
<td>03</td> - Obtendo o endereço da máquina

```sh
ifconfig
```

## Criando o Phishing 

Selecione a opção 1 - Para definir o tipo de Ataque
<table>
  <tr>
    <td>
      <img src="https://i.ibb.co/fGngxbgF/1.png" alt="1" border="0"></a>
    </td>
</table>

Selecione a opção 2 - De onde vai partir o ataque. 
<table>
  <tr>
    <td>
      <img src="https://i.ibb.co/5WWjjFyq/2.png" alt="2" border="0"></a>
    </td>
</table>

Selecione a opção 3 - Para coletar credenciais
<table>
  <tr>
    <td>
      <img src="https://i.ibb.co/4RVFVnCF/3.png" alt="3" border="0"></a>
    </td>
</table>

Selecione a opção 2 - Para clonar o site
<table>
  <tr>
    <td>
      <img src="https://i.ibb.co/1J7tG2K6/4.png" alt="4" border="0"></a>
    </td>
</table>

Nessa etapa você vai apertar Enter e logo depois vai digitar o site que você vai clonar.  
IMPORTANTE: Alterar alterar rede da máquina para o modo [bridged Adapter]
<table>
  <tr>
    <td>
     <img src="https://i.ibb.co/bRgKqHJF/5.png" alt="5" border="0"></a>
    </td>
</table>

Pronto, agora é só preencher os dados. 
<table>
  <tr>
    <td>
     <img src="https://i.ibb.co/YBjZHbbx/Captura-de-tela-2025-01-29-165315.png" alt="captura tela face" border="0"></a>
    </td>
</table>

## Informações obtidas com êxito
<table>
  <tr>
    <td>
      <img src="https://i.ibb.co/xt3TbkQ7/Captura-de-tela-2025-01-29-134603.png" alt="captura resultado" border="0"></a>
    </td>
</table>

##
<div align="center">Feito por <a href="https://github.com/smarksb">smarksb</a>.</div>
<div align="center">Repositório desenvolvido para fins educativos.</a></div>