### 🚀 **Automação de Configuração de Servidor Apache com Deploy de Site**

Criei um script que automatiza a instalação do servidor web Apache, faz o download e publica um site estático em uma máquina Linux, facilitando o deploy de aplicações web. 

#### **O que o script faz:**

1. **Atualiza o sistema**: Garante que o servidor tenha os pacotes mais recentes e o sistema esteja atualizado.
   
2. **Instala o Apache**: Configura o servidor web Apache para hospedar o site.

3. **Instala o Unzip**: Baixa e extrai os arquivos do site a partir de um repositório GitHub.

4. **Publica o Site**: Copia os arquivos extraídos para o diretório padrão do Apache, tornando o site acessível publicamente via navegador.

#### **Tecnologias Usadas**:
- **Linux (Ubuntu)**: Sistema operacional de base.
- **Apache**: Servidor web.
- **GitHub**: Fonte do site estático para deploy.
- **Bash**: Linguagem de script para automação.

#### **Requisitos**:
- Sistema baseado em Linux
- Acesso root ou permissões de superusuário

#### **Resultado Esperado**:
Após executar o script, o servidor Apache estará em funcionamento e o site estará disponível para acesso via IP público no navegador.
