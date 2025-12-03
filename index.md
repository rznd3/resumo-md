# Resumo dos temas estudados nas matérias de Redes, Git/GitHub e HTML

# Resumo do Módulo - Redes, Git/GitHub e HTML

## Redes de Computadores e Internet

### Conceitos Fundamentais
- **Topologias de Rede**: Estrela, barramento, anel, malha
- **Comunicação em Rede**: Emissor, receptor, protocolos (TCP/IP)
- **Escalabilidade**: Arquitetura adequada, redundância, balanceamento

### História da Internet
- **ARPANET**: Origem nos anos 60
- **TCP/IP**: Protocolo padrão dos anos 80
- **Web 2.0**: Interatividade e redes sociais
- **Web 3.0**: Web semântica, blockchain, IoT

### Protocolos de Comunicação
- **Protocolos de Rede**: TCP/IP, roteamento, endereçamento
- **Protocolos de Transporte**: TCP (confiável), UDP (velocidade)
- **Protocolos de Aplicação**: HTTP, SMTP, FTP
- **RFC**: Documentação de padrões da internet

### Endereçamento IP
- **IPv4**: 32 bits, ~4.3 bilhões de endereços
- **IPv6**: 128 bits, espaço virtualmente ilimitado
- **Máscaras de Sub-rede**: Segmentação de redes
- **Portas**: Identificação de serviços (80-HTTP, 443-HTTPS)

### DNS (Domain Name System)
- **Hierarquia**: TLDs, domínios, subdomínios
- **Servidores**: Resolução, autoritativos, raiz
- **Registros**: A, AAAA, MX, CNAME, TXT, NS, SOA, SRV
- **Cache**: Otimização de consultas

### Arquitetura da Internet
- **Backbones**: Redes de alta capacidade
- **IXPs**: Pontos de troca de tráfego
- **Roteadores**: Encaminhamento de dados
- **QoS**: Qualidade de serviço

### Tipos de Redes
- **LAN**: Área local (casa, escritório)
- **WAN**: Longa distância (cidades, países)
- **MAN**: Área metropolitana
- **PAN**: Área pessoal (Bluetooth, Wi-Fi Direct)

### Segurança
- **Firewalls**: Pacotes, estado, aplicação, NGFW
- **Antivírus**: Proteção contra malware
- **VPN**: Túneis criptografados
- **Criptografia**: SSL/TLS, simétrica, assimétrica
- **Ameaças**: Malware, phishing, DDoS, ransomware

---

## Git e GitHub

### Controle de Versão
- **Git**: Sistema de controle de versão distribuído
- **Repositório**: Pasta com histórico de commits
- **Commit**: Checkpoint do projeto
- **Working Tree**: Arquivos atuais do projeto
- **Index/Staging Area**: Área temporária antes do commit

### Comandos Básicos
- `git init`: Inicializa repositório
- `git status`: Verifica estado dos arquivos
- `git add`: Adiciona mudanças ao Index
- `git commit`: Cria checkpoint
- `git log`: Histórico de commits
- `git diff`: Compara versões

### Branches e Merge
- **Branch**: Marcador móvel sobre commits
- **HEAD**: Branch atualmente selecionada
- `git branch`: Cria branch
- `git checkout`: Troca de branch
- `git merge`: Fusão de branches (fast-forward, three-way)
- **Conflitos**: Resolução manual de diferenças

### Repositório Remoto
- **GitHub**: Plataforma de hospedagem
- `git clone`: Copia repositório remoto
- `git fetch`: Baixa atualizações
- `git push`: Envia commits ao remoto
- `git pull`: Fetch + merge
- **SSH**: Autenticação por chaves
- **Remote-tracking branch**: Representa estado do remoto

### Pull Request
- **PR**: Solicitação de merge via GitHub
- **Review**: Revisão de código
- **Conversation**: Discussão sobre mudanças
- **Merge**: Integração após aprovação

### Comandos Avançados
- `git stash`: Salva mudanças temporariamente
- `git reset`: Move branches e reseta Working Tree
- `git rebase`: Reorganiza histórico
- `.gitignore`: Ignora arquivos específicos

---

## HTML5

### Ferramentas de Desenvolvimento
- **VS Code**: Editor de código principal
- **Extensões**: Auto Close Tag, Live Server, Emmet
- **Navegadores**: Chrome, Firefox, Safari, Edge
- **Atalhos**: Produtividade no editor

### Estrutura Básica
```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>Título</title>
</head>
<body>
    <!-- Conteúdo -->
</body>
</html>
```

### Elementos Fundamentais
- **Estrutura**: `<html>`, `<head>`, `<body>`
- **Texto**: `<h1>`-`<h6>`, `<p>`, `<span>`
- **Links**: `<a href="">`
- **Imagens**: `<img src="" alt="">`
- **Multimídia**: `<audio>`, `<video>`

### Listas
- **Não ordenadas**: `<ul>` + `<li>`
- **Ordenadas**: `<ol>` + `<li>`
- **Definição**: `<dl>`, `<dt>`, `<dd>`

### Tabelas
- **Estrutura**: `<table>`, `<tr>`, `<th>`, `<td>`
- **Agrupamento**: `<thead>`, `<tbody>`, `<tfoot>`
- **Atributos**: `colspan`, `rowspan`

### Formulários
- **Container**: `<form action="" method="">`
- **Inputs**: `type="text"`, `email`, `date`, `password`
- **Outros**: `<textarea>`, `<select>`, `<button>`
- **Agrupamento**: `<fieldset>`, `<legend>`
- **Validação**: Atributo `required`

### Semântica
- **Layout**: `<header>`, `<nav>`, `<main>`, `<footer>`
- **Conteúdo**: `<article>`, `<section>`, `<aside>`
- **Classes e IDs**: Identificação e estilização de elementos

### Elementos
- **Tag de abertura**: `<elemento>`
- **Atributos**: `atributo="valor"`
- **Conteúdo**: Texto ou outros elementos
- **Tag de fechamento**: `</elemento>`
