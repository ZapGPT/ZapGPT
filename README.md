### Sobre

Dify é uma plataforma de desenvolvimento de aplicativos LLM (Modelo de Linguagem de Grande Escala) de código aberto. Sua interface intuitiva combina fluxo de trabalho de IA, pipeline RAG, capacidades de agentes, gerenciamento de modelos, recursos de observação e muito mais, permitindo que você vá rapidamente do protótipo à produção.

Aqui estão algumas das principais funcionalidades:

1. **Fluxo de Trabalho:** Construa e teste fluxos de trabalho de IA poderosos em um canvas visual, aproveitando todos os recursos a seguir e muito mais.

2. **Suporte abrangente a modelos:** Integração perfeita com centenas de LLMs proprietários e de código aberto de diversos fornecedores de inferência e soluções auto-hospedadas, cobrindo modelos como GPT, Mistral, Llama3 e qualquer modelo compatível com a API OpenAI.

3. **IDE de Prompt:** Interface intuitiva para criar prompts, comparar desempenho de modelos e adicionar recursos adicionais, como conversão de texto para fala, a um aplicativo baseado em chat.

4. **Pipeline RAG:** Capacidades extensivas de RAG que cobrem desde a ingestão de documentos até a recuperação, com suporte pronto para extração de texto de PDFs, PPTs e outros formatos de documentos comuns.

5. **Capacidades de agentes:** Você pode definir agentes baseados em Chamada de Função LLM ou ReAct, e adicionar ferramentas predefinidas ou personalizadas para o agente. O Dify fornece mais de 50 ferramentas integradas para agentes de IA, como Pesquisa Google, DALL·E, Stable Diffusion e WolframAlpha.

6. **LLMOps:** Monitore e analise logs de aplicativos e desempenho ao longo do tempo. Você pode melhorar continuamente prompts, conjuntos de dados e modelos com base em dados de produção e anotações.

7. **Backend como Serviço:** Todas as ofertas do Dify vêm com APIs correspondentes, permitindo que você integre o Dify de forma eficiente à sua própria lógica de negócios.

### Comparação de Recursos

| Recurso                          | Dify.AI          | LangChain       | Flowise         | OpenAI Assistants API |
|----------------------------------|------------------|-----------------|-----------------|-----------------------|
| Abordagem de Programação         | API + Orientado a Apps | Código em Python | Orientado a Apps | Orientado a API       |
| LLMs Suportados                  | Grande Variedade | Grande Variedade | Grande Variedade | Apenas OpenAI         |
| Motor RAG                        | ✅                | ✅               | ✅               | ✅                     |
| Agente                           | ✅                | ✅               | ❌               | ✅                     |
| Fluxo de Trabalho                | ✅                | ❌               | ✅               | ❌                     |
| Observabilidade                  | ✅                | ✅               | ❌               | ❌                     |
| Recursos Empresariais (SSO/Controle de Acesso) | ✅                | ❌               | ❌               | ❌                     |
| Implantação Local                | ✅                | ✅               | ✅               | ❌                     |

### Usando o Dify

**Cloud:** Nós hospedamos um serviço Dify Cloud para qualquer pessoa experimentar sem necessidade de configuração. Ele oferece todas as capacidades da versão auto-hospedada e inclui 200 chamadas gratuitas ao GPT-4 no plano sandbox.

**Auto-hospedagem Dify Community Edition:** Configure rapidamente o Dify no seu ambiente com este guia inicial. Use nossa documentação para referências adicionais e instruções mais detalhadas.

**Dify para empresas/organizações:** Oferecemos recursos adicionais focados em empresas. Agende uma reunião conosco ou envie um e-mail para discutir as necessidades da sua empresa.

**Para startups e pequenas empresas usando AWS:** Confira o Dify Premium no AWS Marketplace e implante-o no seu próprio VPC da AWS com um clique. É uma oferta AMI acessível com a opção de criar aplicativos com logotipo e marca personalizados.

### Mantendo-se Atualizado

Dê uma estrela ao Dify no GitHub e seja notificado instantaneamente sobre novos lançamentos.

### Início Rápido

Antes de instalar o Dify, certifique-se de que sua máquina atende aos seguintes requisitos mínimos de sistema:

- CPU: 2 Núcleos ou mais
- RAM: 4GB ou mais

A maneira mais fácil de iniciar o servidor Dify é executando nosso arquivo `docker-compose.yml`. Antes de executar o comando de instalação, certifique-se de que o Docker e o Docker Compose estão instalados na sua máquina:

```bash
cd docker
docker compose up -d
```

Após a execução, você pode acessar o painel do Dify no seu navegador em `http://localhost/install` e iniciar o processo de inicialização.

### Próximos Passos

Se precisar personalizar a configuração, consulte os comentários em nosso arquivo `docker-compose.yml` e configure manualmente o ambiente. Após fazer as alterações, execute novamente `docker-compose up -d`. Você pode ver a lista completa de variáveis de ambiente aqui.

Se quiser configurar uma instalação altamente disponível, há Helm Charts e arquivos YAML contribuídos pela comunidade que permitem implantar o Dify no Kubernetes.

### Contribuindo

Para aqueles que desejam contribuir com código, veja nosso Guia de Contribuição. Considere também apoiar o Dify compartilhando-o nas redes sociais e em eventos e conferências.

Estamos buscando colaboradores para ajudar a traduzir o Dify para idiomas além do mandarim ou inglês. Se estiver interessado, veja o README de i18n para mais informações e deixe um comentário no canal global-users do nosso servidor Discord.

### Comunidade e Contato

- **Discussão no GitHub:** Melhor para compartilhar feedback e fazer perguntas.
- **Problemas no GitHub:** Melhor para bugs encontrados ao usar o Dify.AI e propostas de funcionalidades. Veja nosso Guia de Contribuição.
- **E-mail:** Melhor para perguntas sobre o uso do Dify.AI.
- **Discord:** Melhor para compartilhar suas aplicações e interagir com a comunidade.
- **Twitter:** Melhor para compartilhar suas aplicações e interagir com a comunidade.

Ou agende uma reunião diretamente com um membro da equipe:

| Ponto de Contato    | Propósito                           |
|---------------------|-------------------------------------|
| Enquiries & Feedback| Consultas comerciais e feedback de produto |
| Contributions       | Contribuições, problemas e solicitações de funcionalidades |

### Divulgação de Segurança

Para proteger sua privacidade, evite postar problemas de segurança no GitHub. Em vez disso, envie suas perguntas para `security@dify.ai` e forneceremos uma resposta mais detalhada.

### Licença

Este repositório está disponível sob a Licença de Código Aberto Dify, que é essencialmente Apache 2.0 com algumas restrições adicionais.
