# Política de privacidade da Augusta

Última atualização: 09/10/2026. Responsável: Madja Moura (contato: madjasmoura@gmail.com).

A Augusta é uma extensão independente. Não é produto, serviço nem extensão oficial do Tribunal Regional Federal da 5ª Região (TRF5), do PJe ou do sistema Julia.

## O que a extensão faz com os dados
- Lê o processo aberto na sua aba do PJe (pje2g), usando a sua própria sessão, e consulta o Julia também com a sua sessão.
- Não existe servidor da extensão. Nenhum dado é enviado ao desenvolvedor, e não há analytics, anúncios, rastreadores nem venda de dados.
- Armazena apenas no seu navegador (chrome.storage): preferências, a chave de IA que você colar, o aprendizado de modelos aceitos e recusados e o retrato da sessão de trabalho. Os dados da sessão somem ao fechar o navegador.
- Medição de uso, opcional e local: se estiver ligada (em "Mostrar detalhes"), guarda no navegador apenas as notas de semelhança mostradas, os fatores da nota, o tipo de decisão e o que você fez (usou, recusou, ignorou). Nunca guarda número de processo, nome de parte ou de magistrado, nem texto de peça. Você pode copiar a tabela, desligar o registro ou apagá-lo a qualquer momento.

## Envio a provedores de IA (somente se você configurar)
Se você informar uma chave de API, trechos dos autos e dos modelos são enviados diretamente do seu navegador ao provedor que escolheu (Anthropic, OpenAI, Google Gemini ou endereço compatível, inclusive local). O tratamento passa a seguir a política desse provedor. A extensão só usa a IA com a sua confirmação de que o processo não tem segredo de justiça, mas a responsabilidade de enviar ou não dados processuais a um serviço externo é do usuário, nos termos da Resolução CNJ 615/2025 e das normas do seu órgão.

Antes do envio, a extensão oculta localmente CPF, CNPJ, e-mail, telefone, CEP e nomes de partes e advogados (opção "Ocultar dados pessoais antes de enviar", ligada por padrão) e restaura os dados reais na resposta. É melhor esforço, não garantia.

## Busca semântica e correção de digitação
A comparação de decisões por sentido (sinônimos jurídicos) e a correção de erro de digitação rodam dentro da extensão, no seu navegador. Não há serviço externo de busca semântica nem envio de texto para isso.

## Consulta ao Banco Nacional de Precedentes (opcional)
O botão "Banco de Precedentes" só age quando você clica. Ele envia ao BNP (pangeabnp.pdpj.jus.br) os termos de busca que estão no campo de termos do painel (expressões jurídicas, como "benefício assistencial") e, para conferir citações do texto-base ou da minuta, apenas o número e a espécie de cada citação (por exemplo, "Tema 1124, STJ"). Não envia texto do processo, nome de parte nem dado pessoal, desde que você não digite um no campo de termos. A permissão para esse endereço é pedida no primeiro clique.

## Inserção da minuta no editor do PJe
O botão "Inserir no editor do PJe" escreve a minuta no editor aberto na sua aba, somente depois do seu clique e de uma confirmação, executando um script na própria página do PJe. Nada é enviado a terceiros por esse recurso. Confira e salve a minuta no próprio PJe.

## Permissões do navegador
- Sites do TRF5 (PJe e Julia): ler o processo e pesquisar jurisprudência.
- Sites dos provedores de IA e localhost: chamadas à IA escolhida.
- pangeabnp.pdpj.jus.br: conferência de citações, sob demanda, com a sua autorização.
- Qualquer site https, sob demanda e com a sua autorização: apenas se você indicar um endereço de IA próprio.
- storage, tabs, sidePanel: guardar preferências, identificar a aba do PJe e exibir o painel lateral.
- scripting: inserir a minuta no editor do PJe, após o seu clique e confirmação.

## Seus controles
Apague a chave e os dados locais em "Alterar" no painel de IA ou removendo a extensão. Dúvidas ou pedidos: madjasmoura@gmail.com.
