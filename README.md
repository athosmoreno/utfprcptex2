# utfprcptex2 - Pacote LaTeX para a UTFPR - CP 
Pacote LaTeX para monografias (proposta, TCC) para a Universidade Tecnológica Federal do Paraná do campus da cidade de Cornélio Procópio.

Esse repositório serve apenas como referencia para quem prefere usar o GitHub. Os desenvolvedores do pacote originais estão listados no começo do arquivo `modelo_dissertacao.tex`.

As instruções a seguir são de minha autoria, sendo uma adaptação das instruções originais. Esse pacote e as instruções são distribuidos sem garantia e é responsabilidade de quem for utilizar o que ocorrer após.

O repositório possui duas pastas: `modelo` e `utfprcptex2`. A pasta `modelo` é um exemplo para que você possa construir sua dissertação em cima. A pasta `utfprcptex2` é o pacote em si.

# Instalação com o MikTeX

Se você utiliza o MikTeX no Windows, é possivel instalar de forma simples o pacote.

No Iniciar, digite `MikTeX Settings`.

![Exemplo de busca](https://vgy.me/qxGyPs.png)

Vá na aba `Roots` e clique no botão `Add`. Selecione a pasta `utfprcptex2`. Escolha com cuidado o diretório, pois não poderá ser deletado. Se você usa mais de um computador, você pode colocar em um serviço de nuvem, como Dropbox ou OneDrive, para manter o pacote sempre com você.

![MikTeX Options](https://vgy.me/y9PTpj.png)

# Instalação em outros sistemas

Leia o metodo 4 dessa resposta no LaTeX Stack Exchange. Se você tiver um passo-a-passo melhor, faça um pull request deste README.

# Uso com o Git

Se você vai fazer sua dissertação no LaTeX com o Git, utilize o arquivo `.gitignore` deste repositório para evitar arquivos desnecessários no seu repositório.

# Renomeação de arquivos

Se você não quer utilizar o nome `modelo_dissertacao` no seu projeto:

Windows: use o seguinte script no PowerShell no diretório do seu projeto LaTeX

`Dir | Rename-Item –NewName { $_.name –replace "modelo_dissertacao","proposta" }`

Sendo `proposta` um exemplo de um nome. Substituia pelo que quiser.

Linux (utilizando o bash): Veja https://www.cyberciti.biz/tips/renaming-multiple-files-at-a-shell-prompt.html








