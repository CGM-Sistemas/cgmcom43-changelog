# 📦 CHANGELOG
🔹 Issue: número da tarefa no GitHub  
🔧 Chamado: número do ticket interno

---

## [v4.3.0.007] - 19-11-2025

### ✨ Novidades
- 🔹#87 | 🔧 #165052 - Inclusão do cadastro para os tipos de notas de débito.
- 🔹#88 | 🔧 #165052 - Inclusão do cadastro para os tipos de notas de crédito.
- 🔹#92 | 🔧 #165052 - Inclusão do cadastro das classificações tributárias do IBS e da CBS.
- 🔹#94 | 🔧 #165052 - Implementada funcionalidade para importação da planilha com os dados das classificações tributárias do IBS/CBS.
- 🔹#99 | 🔧 #165700 - Disponibilizado o projeto `CGMCOM43.Api` para instalação nos ambientes dos clientes.

### 🐞 Correções
- 🔹#101 | 🔧 #165052 - Corrigido erro que impedia o carregamento da versão mais recente do registro nas telas de cadastro.

### 🔧 Alterações
- Nenhuma alteração nesta versão.

### 🛠️ Melhorias internas
> Ajustes técnicos e estruturais que não impactam diretamente o uso do sistema, mas contribuem para sua estabilidade, desempenho e manutenção.

- 🔹#84 | 🔧 #164918 - Atualização das versões das bibliotecas de terceiros utilizadas no projeto.

---

## [v4.3.0.006] - 18-09-2025

### ✨ Novidades
- 🔹#68 | 🔧 #164575 - Inclusão do cadastro dos países.
- 🔹#68 | 🔧 #164575 - Inclusão do relatório dos países.
- 🔹#76 | 🔧 #164575 - Adicionadas teclas de atalho aos botões principais do sistema para melhorar a navegação e a acessibilidade.
- 🔹#76 | 🔧 #164575 - Adicionados tooltips aos botões principais do sistema para melhorar a orientação do usuário.

### 🐞 Correções
- 🔹#61 | 🔧 #164496 - Implementado mecanismo de contingência com uso de arquivo local para garantir funcionamento em casos de falha no download via nuvem. A funcionalidade está disponível ao acessar CGMCOM43 pelo menu de relatórios em instalações novas.

### 🔧 Alterações
- 🔹#70 | 🔧 #164575 - Padronização dos títulos das janelas para melhorar a clareza e o reconhecimento do contexto em uso.
- 🔹#70 | 🔧 #164575 - Agora é possível abrir múltiplas janelas de edição a partir da listagem dos cadastros, com títulos identificando a chave primária de cada registro.

### 🛠️ Melhorias internas
> Ajustes técnicos e estruturais que não impactam diretamente o uso do sistema, mas contribuem para sua estabilidade, desempenho e manutenção.

- 🔹#72 | 🔧 #164575 - Melhorias na geração automática de código (Source Code Generator), otimizando a criação de classes.

---

## [v4.3.0.005] - 09-09-2025

### ✨ Novidades
- 🔹#49 | 🔧 #163689 - Inclusão do cadastro para os feriados.
- 🔹#22 | 🔧 #164044 - Inclusão da tabela `UsuariosConfiguracoes` para receber parâmetros específicos do computador.
- 🔹#24 | 🔧 #164044 - Inclusão de estrutura de suporte na tabela `UsuariosConfiguracoes` para leitura de parâmetros por máquina.

### 🐞 Correções
- Nenhuma correção nesta versão.

### 🔧 Alterações
- 🔹#44 | 🔧 #164216 - Validação aplicada aos campos dos cadastros existentes.
- 🔹#42 | 🔧 #164216 - Tratamento de erros centralizado no projeto.
- 🔹#41 | 🔧 #164216 - Tamanho máximo de caracteres definido em campos existentes.
- 🔹#25 | 🔧 #164044 - Métodos no `CGMCOM42` ajustados para leitura dos parâmetros de computador via banco de dados.
- 🔹#23 | 🔧 #164044 - Parâmetro "Nome da impressora que será utilizada automaticamente na impressão dos espelhos dos orçamentos em formato REPX" migrado do Registro do Windows para a tabela no banco de dados.

### 🛠️ Melhorias internas
> Ajustes técnicos e estruturais que não impactam diretamente o uso do sistema, mais contribuem para sua estabilidade, desempenho e manutenção.

- 🔹#16 | 🔧 #164040 - Formulário principal refatorado para adoção de ViewModel.
- 🔹#30 | 🔧 #164040 - Source Code Generator implementado para geração automática de classes em tempo de compilação.

---

## [v4.3.0.004] - 29-08-2025

### ✨ Novidades
- 🔹#13 | 🔧 #163882 - Inclusão do menu "Configurações" exclusivo ao usuário Administrador.
- 🔹#10 | 🔧 #163882 - Inclusão do menu "Parâmetros" dentro do menu "Configurações" (tela contendo os parâmetros do sistema).

### 🐞 Correções
- Nenhuma correção nesta versão.

### 🔧 Alterações
- Nenhuma alteração nesta versão.

---
