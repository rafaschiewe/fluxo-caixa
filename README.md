# Instruções para Hospedagem Permanente do Sistema de Fluxo de Caixa

Este documento contém instruções detalhadas para hospedar o sistema de Fluxo de Caixa em diferentes plataformas de hospedagem gratuitas.

## Opção 1: GitHub Pages

O GitHub Pages é uma forma gratuita e simples de hospedar sites estáticos diretamente de um repositório GitHub.

### Passo a passo:

1. Crie uma conta no GitHub (https://github.com) se ainda não tiver uma
2. Crie um novo repositório público (por exemplo, "fluxo-caixa")
3. Faça upload dos arquivos do sistema (extraídos do arquivo ZIP)
4. Vá para "Settings" > "Pages"
5. Em "Source", selecione "main" (ou "master") e a pasta raiz "/"
6. Clique em "Save"
7. Após alguns minutos, seu site estará disponível em `https://seuusuario.github.io/fluxo-caixa`

## Opção 2: Netlify

O Netlify oferece hospedagem gratuita com recursos adicionais como domínio personalizado e HTTPS.

### Passo a passo:

1. Crie uma conta no Netlify (https://netlify.com)
2. Na dashboard, clique em "Add new site" > "Import an existing project"
3. Você pode conectar com GitHub ou fazer upload direto dos arquivos
4. Para upload direto:
   - Clique em "Deploy manually"
   - Arraste a pasta com os arquivos do sistema (extraídos do ZIP)
   - Aguarde o upload e deploy
5. Seu site estará disponível em um domínio aleatório como `https://random-name.netlify.app`
6. Você pode personalizar este domínio nas configurações do site

## Opção 3: Vercel

O Vercel é outra excelente opção para hospedagem gratuita de sites estáticos.

### Passo a passo:

1. Crie uma conta no Vercel (https://vercel.com)
2. Na dashboard, clique em "Add New" > "Project"
3. Você pode conectar com GitHub ou fazer upload direto
4. Para upload direto:
   - Clique em "Upload" na seção "Import Git Repository"
   - Selecione os arquivos do sistema (extraídos do ZIP)
   - Clique em "Deploy"
5. Seu site estará disponível em um domínio como `https://fluxo-caixa.vercel.app`

## Considerações Importantes

- **Dados Locais**: O sistema utiliza localStorage para armazenar os dados, o que significa que:
  - Os dados são armazenados apenas no navegador do usuário
  - Diferentes dispositivos terão conjuntos de dados separados
  - Limpar o cache do navegador apagará os dados

- **Backup de Dados**: Utilize regularmente a função de exportar CSV para fazer backup dos seus dados

- **Segurança**: O sistema de login implementado é simples e os dados são armazenados localmente. Para um ambiente de produção com dados sensíveis, considere implementar um backend com autenticação mais robusta.

## Personalização

Você pode personalizar o sistema editando os seguintes arquivos:

- `css/styles.css` - Para alterar cores, fontes e estilos
- `index.html` - Para modificar a estrutura da página principal
- `js/app.js` - Para ajustar o comportamento do sistema

## Suporte a Navegadores

O sistema foi desenvolvido para funcionar em navegadores modernos:
- Google Chrome (recomendado)
- Mozilla Firefox
- Microsoft Edge
- Safari

## Contato e Suporte

Se precisar de ajuda adicional ou tiver dúvidas sobre a implementação, entre em contato.
