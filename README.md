# 🛠 Tecnologias Utilizadas (ASP.NET)

## Gerenciador de Dependências
- **NuGet** (Gerenciador de pacotes padrão para .NET)
- **Paket** (Alternativa para projetos complexos com dependências compartilhadas)

## Disparador de Emails
- **MailKit** (Biblioteca .NET moderna para SMTP, AWS SES, etc.)
- [SendGrid](https://sendgrid.com/) (API com templates e analytics)
- [Amazon SES](https://aws.amazon.com/ses/) (Custo-efetivo para grandes volumes)
- **FluentEmail** (Biblioteca .NET para emails com templates embutidos)

## Orquestrador de Containers
- [Kubernetes (K8s)](https://kubernetes.io/) (Padrão para escalabilidade e alta disponibilidade)
- [Docker Swarm](https://docs.docker.com/engine/swarm/) (Alternativa simples para projetos menores)
- **IIS (Internet Information Services)** (Para hospedagem tradicional em Windows Server)

## Ferramentas Adicionais
- [Terraform](https://www.terraform.io/) (Infraestrutura como código para Azure/AWS)
- [Azure Monitor](https://azure.microsoft.com/pt-br/services/monitor/) + [Application Insights](https://docs.microsoft.com/pt-br/azure/azure-monitor/app/app-insights-overview) (Monitoramento nativo no ecossistema .NET)
- [Helm](https://helm.sh/) (Gerenciamento de pacotes no Kubernetes, se aplicável)
- **Entity Framework Core** (ORM para acesso a bancos de dados)
- **Dapper** (Micro-ORM para consultas SQL otimizadas)
- **Serilog** (Logging estruturado para .NET)
- **Azure DevOps** ou **GitHub Actions** (CI/CD para pipelines de deploy)

## Extras para ASP.NET
- **Swagger/OpenAPI** (Documentação de APIs)
- **AutoMapper** (Mapeamento entre objetos)
- **MediatR** (Padrão mediator para CQRS)
- **IdentityServer4** (Autenticação e autorização)
- **Hangfire** (Processamento de jobs em background)
