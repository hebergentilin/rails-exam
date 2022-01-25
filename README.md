# Summary
Repo to qualify the candidates

# Objetivo do Repositório
Na tentativa de encontrar um profissional com conhecimento básico na stack desejável que se aplique à vaga da empresa Traus, preparamos esse repositório como condição técnica para a próxima fase: a entrevista.

# O que fazer?
Faça um fork desse repositório para seu perfil e implemente, no mínimo, todos os requisitos obrigatórios.
Os requisitos extras implementados, terão pontuações e pesos diferentes dos demais.
### ATENÇÃO
O prazo final para entrega é de 20 dias a partir da data do fork do repositório.

# Requisitos Obrigatórios
Siga rigorosamente a stack a seguir:
  - Ruby 2.7
  - Rails 6.1.1
  - Framework Javascript: Stimulus
  - Banco de Dados: Postgresql
  - Background Processing: Sidekiq

Regras de Negócio:
  - Com ou sem ajuda de alguma gem, desenvolva um sistema de autenticação de usuários;
  - Todo usuário do sistema, deverá fazer parte de uma empresa;
  - O acesso ao projeto pela URL, só se dará pelo subdomínio cadastrado na empresa. As demais URL, não terão acesso ao sistema.
Ex: a empresa XPTO Company tem cadastrado o subdomínio ```xpto-company```. Os usuários da empresa XPTO, só poderão se autenticar se acessar a URL ```xpto-company.traus.com.br```. O sistema de autenticação deve bloquear um usuário da empresa Big Tech, por exemplo, quando tentar se autenticar através da URL de outra empresa.
  - Ao se autenticar, apenas exiba as seguintes informações:
    - Nome da Empresa
    - Nome do Usuário
    - Email do Usuário
    - Data de Login
    - Link para Logout

# Requisitos Extras
  - Todo commit deve ser feito em inglês
  - Evite "commitar" na master
  - Faça a validação no formulário de cadastro de usuário, para identificar possível e-mail duplicado pelo stimulus.
  - Mesma validação pode ser feita no cadastro de empresa, pra identificar subdomínio repitidos.
  - Adeque o projeto ao rubocop
  - Cubra pelo menos 88% do código com testes
  - Onde podemos aplicar o Sidekiq?

Lembre-se, não se sinta pressionado a realizar todas as atividades.
Cada um tem seus compromissos e afazeres e se você pondera que a vaga não é interessante para você, não siga em frente para evitar qualquer desconforto.

Boa Sorte!
