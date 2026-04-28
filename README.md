<div align="center">
<img src="https://raw.githubusercontent.com/SAWARATSUKI/KawaiiLogos/refs/heads/main/Rust/png/Rust_Transparent.png" width="60%"/>
</div>

# Foods API
> Servidor HTTP local para aplicações TS Foods

## API TS Foods

*... Em andamento ...*

## Serviço Food Server

API versão antiga *1.0.9* para usar com aplicativo *TechSoft Food*

### Caracteristicas

- Instalação simplificada com adição do programa ao contexto do Windows
- Configuração automática
  - IP dinâmico
  - Integração com *TSWaiter*
- Menor consumo de recursos
  - Quantidade menor de consultas no banco de dados
  - Menor quantidade de conexão abertas
- Maior validação de erros
  - Validação nas quantidades e valores de produtos e suas composições
  - Previne comportamentos incorretos no agrupar e desagrupar mesas.
- Melhoria nos logs gerados
- Maior segurança prevenindo
  - Vazamento de senhas
  - Vazamento de comportamentos de decriptografia

### Como funciona

O programa instalado de maneira padrão sempre irá inicializar juntamente com o *Windows*,
e irá utilizar o arquivo de configuração padrão do sistema para se conectar ao banco de dados
sem a necessidade de configurações adicionais. Assim como criar a configuração inicial do
*TSWaiter* e inicializar automaticament com

O programa também irá controlar e verificar a própria regra de firewall a modo de garantir que
pode ser acessado mesmo de fora do computador.

### Como instalar

Execute o instalador do programa na raiz do sistema *TechSoft* onde se encontra o *sistema.exe*
e o *config.ini*

> [!IMPORTANT]
> O instalador não permitirá instalação do programa o sistema techsoft já não estiver préviamente
> instalado e ocnfigurado, sendo necessário que o arquivo *config.ini* exista na pasta onde está instalado


### Atualizações

[Log de Atualizações](CHANGELOG.md)