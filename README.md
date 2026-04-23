# Santos Hub — Site Institucional

Site institucional do Santos Hub, serviço de certificação digital e contabilidade em Brasília.

## Estrutura de Arquivos

```
santoshub/
├── index.html          (site completo, único arquivo)
├── img/
│   ├── hero.png        (imagem principal)
│   ├── icp-brasil.png  (selo ICP-Brasil)
│   ├── e-cnpj.png      (certificado e-CNPJ)
│   ├── e-cpf.png       (certificado e-CPF)
│   ├── e-juridico.png  (certificado e-Jurídico)
│   └── e-saude.jpg     (certificado e-Saúde)
└── README.md           (este arquivo)
```

## Como Publicar de Graça na Internet

### Opção 1: Netlify Drop (mais rápido — 2 minutos, sem cadastro)

O Netlify Drop é a forma mais simples de colocar o site no ar. Você apenas arrasta uma pasta para o navegador e pronto, ele fica publicado.

Passo a passo:
1. Acesse o endereço https://app.netlify.com/drop
2. Compacte a pasta santoshub em um arquivo .zip (clicando com o botão direito, "Enviar para" → "Pasta compactada" no Windows, ou clicando com o botão direito e "Comprimir" no Mac)
3. Arraste o arquivo .zip para a área cinza da página do Netlify
4. Em segundos o site estará no ar com um endereço do tipo algum-nome-aleatorio.netlify.app
5. Para ligar o domínio www.santoshub.com.br depois, basta criar uma conta gratuita e ir em Site Settings → Domain Management

### Opção 2: Vercel (grátis para sempre)

A Vercel oferece hospedagem gratuita com domínio personalizado, SSL automático e atualizações contínuas.

Passo a passo:
1. Crie uma conta em https://vercel.com (pode usar login do GitHub ou Google)
2. Clique em "Add New" → "Project"
3. Escolha "Import Git Repository" se você tiver GitHub, ou use a opção de deploy por linha de comando (mais técnico)
4. Para o caminho mais simples: crie um repositório no GitHub com esses arquivos e depois conecte à Vercel
5. Depois de publicado, em Settings → Domains, adicione www.santoshub.com.br

### Opção 3: GitHub Pages (clássico e confiável)

O GitHub Pages hospeda sites estáticos diretamente de um repositório.

Passo a passo:
1. Crie uma conta em https://github.com
2. Crie um repositório público chamado santoshub (ou qualquer nome)
3. Faça upload de todos os arquivos desta pasta
4. Vá em Settings → Pages
5. Em "Source", escolha "Deploy from a branch" e selecione "main"
6. Em alguns minutos o site estará em https://seu-usuario.github.io/santoshub/

### Opção 4: Cloudflare Pages (ótima performance global)

A Cloudflare Pages oferece hospedagem gratuita com CDN mundial.

Passo a passo:
1. Acesse https://pages.cloudflare.com
2. Faça login ou crie conta gratuita
3. Clique em "Create a project" → "Direct Upload"
4. Arraste a pasta santoshub
5. O site fica disponível em segundos com endereço .pages.dev

## Como Conectar o Domínio www.santoshub.com.br

Depois que o site estiver publicado em qualquer uma das plataformas acima, você precisa apontar o domínio para lá. Isso é feito no painel de administração de onde você comprou o domínio (Registro.br, GoDaddy, Hostgator, etc).

No painel do domínio, você altera os registros DNS:
- Tipo A: aponta o domínio raiz para o endereço IP informado pela plataforma de hospedagem
- Tipo CNAME: aponta o www para o endereço fornecido pela plataforma

Cada uma das plataformas acima tem um tutorial próprio detalhando esses valores exatos. Normalmente eles ficam em uma seção chamada "Custom Domain" ou "Domínio Personalizado".

O prazo médio para o domínio começar a funcionar é de 15 minutos a 24 horas, dependendo do provedor.

## Informações do Site

- Nome: Santos Hub
- Domínio: www.santoshub.com.br
- WhatsApp: (61) 98106-1579
- Endereço: Rua 5 Norte, Águas Claras — Brasília/DF
- Responsável: Jordan Santos, Contador
- Certificados: ICP-Brasil, modelo A1, emissão em 15 minutos
- Valores à vista via Pix, transferência ou dinheiro

## Alterações Rápidas no Site

Para mudar preços, textos ou links do WhatsApp, basta abrir o arquivo index.html em qualquer editor de texto (Bloco de Notas, VS Code, Notepad++) e localizar o trecho desejado. Não é necessário conhecer programação para fazer ajustes simples como trocar um valor ou um número de telefone.

Para trocar o número do WhatsApp em todos os lugares do site de uma vez, use a função "Substituir" do editor (Ctrl+H no Windows) e substitua 5561981061579 pelo novo número.
