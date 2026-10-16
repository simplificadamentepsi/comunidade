# Comunidade Simplificadamente para Psicólogas

Site estático em HTML, CSS e JavaScript. Os arquivos podem ser enviados diretamente à raiz de um repositório no GitHub.

## Arquivos

- index.html: landing page e formulário integrado.
- obrigada.html: segunda página e acesso ao grupo do WhatsApp.
- inscricao.html: versão independente do formulário.
- privacidade.html: página de privacidade em preparação.
- styles.css: estilos responsivos.
- form.js: validação e fluxo do formulário.
- config.js: configuração do destino das inscrições.
- assets/: logo e fotos originais.

## Visualização

Abra index.html no navegador. Mantenha os arquivos e a pasta assets na mesma estrutura. Para hospedagem estática, index.html deve estar na raiz da pasta publicada. Não é necessário instalar dependências ou executar uma compilação.

## Formulário

O recebimento automático dos leads ainda NÃO está ativo. O campo formEndpoint em config.js está vazio. Nesse estado, o formulário apenas encaminha para a segunda página em modo de teste, sem armazenar nem enviar respostas.

A integração com a planilha depende da ativação do serviço de recebimento. A Política de Privacidade também precisa ser finalizada antes de receber inscrições reais.

Se utilizar a integração preparada com Google Apps Script, será necessário atualizar a origem permitida no serviço para corresponder ao endereço definitivo do site após a mudança de hospedagem.

## Imagens

As fotos em assets foram copiadas dos arquivos originais, sem recompressão. O enquadramento e o tamanho exibidos são definidos no CSS.
