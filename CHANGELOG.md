# Changelog

## [0.3.0]

### Adicionado

- Adicionada nova release de teste para versões instáveis
- Adicionada trait para iniciar o tswaiter junto com o programa
- Adicionado carregamento automático e configuração do tswaiter.ini

### Corrigido

- Melhorado o uso de memória para os scripts de criptografia e descriptografia

### Alterado

- Adicionadas extensões recomendadas para o VSCode
- Reescrita do conector do banco de dados
- Reescrita do carregador inicial de configuração (config init loader)

## [0.2.6] - 23/04/2026

### Adicionado

- Adicionado novo manual em HTML
- Adicionada criptografia
- Adicionada atualização automática para apihost no cfgini
- Adicionada verificação do endereço IP atual
- Melhorias no instalador e desinstalador
- Atualização do NSI com novo README
- Adicionadas Actions de workflow
- Adicionada chave hash de criptografia/descriptografia ao ambiente (env)
- Adicionadas novas validações para o instalador durante o build
- Adicionada criação de log para atualização do nome da tabela
- Adicionado ao NSIS o início junto com o Windows e validação de diretório
- Novos instaladores MSI e NSIS
- Novas validações de log para rotas PUT e POST
- Adicionada rota para alterar nome da mesa/tabela
- Implementada a mesclagem (merge) de mesas
- Adicionado novo arquivo DTO para a API de comida
- Configuração .ini agora está funcional
- Novo validador de regras de firewall
- Controle de iniciar e parar o serviço do servidor agora é alternável (toggle)
- Controle da janela via bandeja (Tray) concluído!

### Corrigido

- Removidos alguns `expect` para evitar pânico (panic) em funções não críticas
- Correções menores no instalador
- Workflow de release e versão
- Erro de build devido aos recursos (resources)
- Release configurada para rodar apenas se autorizada
- Importação global para `super`
- Corrigido gerador de log
- Corrigido ícone na bandeja (tray)
- Removidas algumas variáveis redundantes
- Removidas algumas conversões de string para u16
- Refatoração de clones desnecessários e campos opcionais (Opt) em DTOs
- Nova criação de pedido para testes
- Alterada a thread para o runtime do Tauri e Tokio
- Controle de log com Enum para melhor controle de códigos de status
- Controle de thread sobre a instância do banco de dados

### Alterado

- Adicionados logs para configuração do host da API
- Adicionada validação de compilador para funções que rodam apenas no Windows
- Atualização de algumas configurações de build
- Atualizações menores em tipos
- Atualização das rotas de teste no justfile
- Implementado o restante da antiga API de comida
- Início da adaptação da API antiga no novo servidor
- Implementada configuração via arquivo .ini
- Movida toda a build principal do app para lib
- Início da implementação de atualização automática
- Atualizações menores
- Início da implementação do WiX para o builder
- Teste de nova mesclagem de mesas
- Início da adaptação do servidor e banco de dados
- Adicionado controlador de firewall para ser implementado

### Removido

- Script antigo de regras de firewall
- Atualização de dependências para SQLx e Actix RT
- Removidos pacotes não utilizados