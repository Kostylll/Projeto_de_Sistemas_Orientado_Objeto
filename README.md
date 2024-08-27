Nesta parte contém todas as Classes,Atributos e Métodos do Sistema

Usuário

Atributos: id, nome, email, senha, tipo (Admin, Padrão)
Métodos: autenticar(), registrar(), atualizarPerfil()
Relatório

Atributos: id, nome, data_criacao, autor (Usuário), status (Em Progresso, Concluído)
Métodos: gerar(), exportar(), compartilhar(), deletar()
Dados (DataSource)

Atributos: id, tipo (Banco de Dados, CSV, API), configuracao, ultimo_acesso
Métodos: conectar(), desconectar(), atualizarDados()
Template

Atributos: id, nome, estrutura, tipo (Gráfico, Tabela, Texto)
Métodos: criarTemplate(), editarTemplate(), aplicarTemplate()
Permissão

Atributos: id, tipo (Leitura, Escrita, Admin), descrição
Métodos: definirPermissao(), atualizarPermissao()
Configuração

Atributos: id, tema, idioma, notificacoes
Métodos: salvarConfiguracao(), carregarConfiguracao(), resetarParaPadrao()
