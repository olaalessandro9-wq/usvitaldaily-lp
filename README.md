# Clone do Site US Vital Daily

## Conteúdo do Arquivo

Este arquivo ZIP contém uma cópia completa do site **usvitaldaily.online**, incluindo:

- **index.html** - Página principal do site
- **assets/css/** - Arquivos de estilo (CSS)
  - bootstrap.css
  - page.css
  - custom.css
  - fbcomments.css
  - vsl.css
- **assets/img/** - Imagens do site
  - profile.webp
- **cdn-cgi/** - Arquivos de cache/CDN
- **robots.txt** - Arquivo de configuração para buscadores

## Instruções de Instalação

### 1. Extrair os arquivos
```bash
unzip usvitaldaily_clone.zip
```

### 2. Estrutura de Diretórios
Após extrair, você terá a seguinte estrutura:
```
usvitaldaily.online/
├── index.html
├── robots.txt
├── assets/
│   ├── css/
│   │   ├── bootstrap.css
│   │   ├── custom.css
│   │   ├── fbcomments.css
│   │   ├── page.css
│   │   └── vsl.css
│   └── img/
│       └── profile.webp
└── cdn-cgi/
    └── content.html
```

### 3. Upload para sua Hospedagem

#### Via FTP/SFTP:
1. Conecte-se ao seu servidor via FTP/SFTP
2. Faça upload de todos os arquivos mantendo a estrutura de diretórios
3. Certifique-se de que o arquivo `index.html` está na raiz do seu domínio

#### Via cPanel/Hosting:
1. Acesse o gerenciador de arquivos
2. Extraia o arquivo ZIP diretamente no servidor
3. Mova os arquivos para o diretório público (geralmente `public_html`)

#### Via Git/GitHub:
1. Crie um repositório no GitHub
2. Faça upload dos arquivos
3. Configure o deploy automático se necessário

### 4. Verificação

Após o upload, acesse seu domínio no navegador para verificar se o site está funcionando corretamente.

## Notas Importantes

- Verifique se todas as permissões de arquivo estão corretas (geralmente 644 para arquivos e 755 para diretórios)
- Se o site não carregar corretamente, verifique os caminhos relativos nos arquivos HTML
- Alguns recursos podem estar vinculados a CDNs externas - verifique a conectividade

## Suporte

Se encontrar problemas durante a migração, verifique:
- Permissões de arquivo no servidor
- Configuração do `.htaccess` (se aplicável)
- Logs de erro do servidor
- Compatibilidade do navegador

---
**Data de Clone:** 20 de Abril de 2026
**Versão:** 1.0
