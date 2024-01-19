# Versionamento de Código com Git e GitHub
- ✅ **1 - Visão Geral do Curso e Ferramentas**
    - Introdução ao Curso
        - Apresentação da professora (Elidiana Andrade - @elidianaandrade)
        - Objetivo geral do curso: introduzir ao versionamento de código com Git e Github
            
            ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/506e0018-f78c-40aa-867b-595e6a7faa6a/Untitled.png)

    ---
    
    - O que é Versionamento de Código
        - É uma maneira de organizar o código compartilhado em projetos de desenvolvimento para que o trabalho possa seguir de maneira mais clara.
        - Sistemas de Controle de Versão
            - Controlam as versões de um arquivo ao longo do tempo.
                
                ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/34793034-4001-409f-8623-721e3c33d7ce/Untitled.png)
                
        - Tipos de Sistemas de Controle de Versão
            - Dentre os Sistemas de Controle de Versão (VCS), temos:
                
                ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/2cf852f3-584d-4264-b592-0ab6e8f12251/Untitled.png)
                
                - VCS Centralizado (CVCS)
                    
                    ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/af7d586c-0caf-4d1d-b396-b0b1910a6e8b/Untitled.png)
                    
                    A desvantagem desse sistema é que, caso o Servidor Central ficasse fora do ar, não seria possível nenhum dos desenvolvedores continuar trabalhando.
                    
                - VCS Distribuído (DVCS)
                    
                    ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/1ca39cb3-b237-4a2f-9b98-af7b816c6203/Untitled.png)
                    
                    Para resolver esse problema, foi desenvolvido o modelo distribuído, onde cada banco de versão é salvo localmente, permitindo que o trabalho continue, mesmo com o Servidor fora do ar.
                    
                    - Clona o repositório completo, o que inclui o histórico de versões.
                        
                        ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/8f736069-de7a-4575-aa05-fea366296915/Untitled.png)
                        
    
    ---
    
    - O que é Git
        - O Git é um dos sistema de controle de versão distribuído, e um dos mais utilizados atualmente no mundo do desenvolvimento. Isso porque:
            
            ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/f855fb1e-70d4-4bd1-8dfe-06e2491b5dfe/Untitled.png)
            
            - Site oficial (e documentação): https://git-scm.com/
                - scm significa Souce Code Manage (Gerenciamento de Código Fonte)
            - 🚨 sempre devemos consultar a documentação durante toda a vida de desenvolvedor, pois precisamos
        - Breve histórico do Git
            
            ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/2d0d020e-98ff-4476-ab59-8be79162490a/Untitled.png)
            
        - Fluxo Básico no Git
            
            ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/6b67929b-165a-4098-b4f9-b14e760ef21f/Untitled.png)
            
            ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/c95cab69-69c0-4eff-bae5-360ea78011c7/Untitled.png)
            
            É importante que saibamos se alguém não fez alguma alteração, para evitarmos conflitos. E para atualizar o nosso repositório:
            
            ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/e52a36ba-d0cf-48b3-b69d-b6577be8642e/Untitled.png)
            
            Ai para enviar:
            
            ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/0d98acd7-1e00-4075-946e-65fa35ec02fa/Untitled.png)
            
            ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/459afe72-c45a-4f9d-879f-1b9ee821e376/Untitled.png)
            
            ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/e25acfff-3824-4bd1-b630-d386210c85ef/Untitled.png)
            
            Essa é uma versão mais simplista e alguns conflito ainda assim podem ocorrer, mas esse são os principais comandos que serão muito importantes no futuro.
            
    
    ---
    
    - O que é GitHub
        
        ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/837116b2-61ac-4002-8d14-3b0d251fbc1d/Untitled.png)
        
        É a famosa “rede social” dos desenvolvedores e programadores
        
        - Breve Histórico:
            
            ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/3880b39b-dc09-427d-a027-6ae33f0b70c1/Untitled.png)
            
        - Git <> GitHub
            
            ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/02817f8b-0cd9-401e-950f-c618259a68f0/Untitled.png)
            
        - Site oficial: https://github.com/
            - Passo-a-passo de como criar uma nova conta

---

- ✅ **2 - Instalação, Configuração e Autenticação**
    - Instalando o Git no Windows (sem notas)
    
    ---
    
    - Instalando o Git no Linux (Ubuntu) (sem notas)
    
    ---
    
    - ➕ Configurando o Git
        - `git config --global [user.name](http://user.name/) "Sérgio Leitão"` - salvando o nome do usuário de maneira global para todos os commits da sua máquina
        - `git config --global user.email [sergiomiranda86@gmail.com](mailto:sergiomiranda86@gmail.com)` - salvando o e-mail do usuário de maneira global para todos os commits da sua máquina.
        - `git config --global init.defaultBranch main` - alterando de maneira global a branch padrão do Git para todos os repositórios criados
        - Com o comando `git config --global --list` conseguimos ver a lista de configurações, mas basicamente, dessa maneira, conseguimos seguir com os ensinamentos do curso. Mais detalhes, só acessar a documentação.
    
    ---
    
    - ➕ Autenticando via Token
        - Com essas configurações, podemos já fazer o versionamento localmente. Mas vamos linkar ele ao GitHub para poder compartilhar ele com outras pessoas.
        - Atualmente, o GitHub mudou a autenticação para acesso aos repositórios, para aumentar a segurança. (Benefícios apresentados no blog do GitHub).
        - Criado um repositório privado para fins didáticos: ‣
        - Feita a tentativa de clonar o repositório sem a autenticação (não deu certo comigo, pois já tenho minha máquina atual como segura).
            - Para criar um novo token, clicamos onde tem nossa foto >>> Settings >>> Developer settings >>> Personal access token >>> Generate new token >>> Generate new token (classic)
                - Damos um nome em “Note” e definimos o tempo de expiração em dias:
                    
                    ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/8db32da5-0d03-440c-91c6-7385059d042e/Untitled.png)
                    
                - Definimos o escopo selecionando as opções de permissão do Token:
                    
                    ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/b1e82551-d4ab-4b41-8c1d-c2529be1f060/Untitled.png)
                    
                    ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/bc98c0d8-b4a5-4c1f-9662-88f867a4a05b/Untitled.png)
                    
                - Após gerar o token, precisamos salvar o código gerado, pois ao sair da página em que ele será apresentado, não poderemos mais vê-lo:
                    
                    ![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](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/c4883c25-0e27-4cec-844e-2ddda694e8b0/Untitled.png)
                    
                    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
                    
                - Após isso, ao tentar clonar o repositório, devemos utilizar o Token no lugar da senha. Para que não tenhamos que sempre gerar um novo Token, podemos:
                    - utilizar `git config --global credential.helper store` (`cache` caso seja uma máquina compartilhada)
                    - ao tentar clonar, é possível observar que ele não pede mais o Token (a minha máquina está definida como gerente (manager) por isso, não preciso dessa configuração toda.
                    - Conseguimos dessa forma observar que o Token já autoriza agora sem precisar de novas verificações.
                - Para finalizar, veremos sobre o armazenamento de credenciais
                    - Na documentação do GIT, temos a citação dos protocolos HTTP e mais detalhes sobre o que - já fizemos - pode ser configurado.
                    - Para configurar qual helper foi feito, utilizamos o `git config --global credential.helper`  e temos onde está. Podemos ver também onde estão salva as informações com o comando `git config --global --show-origin credential.helper`
                        
                        ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/f56da15e-4280-480a-a75d-62e51a8b21b7/Untitled.png)
                        
                        Podemos ver nesse caminho o arquivo .gitconfig e nele todas as configurações feitas:
                        
                        ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/b7926a30-298e-427e-8fd7-80decdd7c16d/Untitled.png)
                        
    
    ---
    
    - ➕ Autenticando via Chave SSH
        - SSH >> Security Shell
            - Protocolo de rede para conexão criptografada entre o nosso computador com o servidor (no caso, o GitHub)
        - Primeiro passo é verificar se há alguma chave SSH já salva e para isso, vamos seguir os passos pelo próprio GitHub.
            - Em Settings >>> SSH and GPG keys*, observamos que temos um link para o guia na documentação (generating SSH keys) onde temos alguns tópicos para leitura futura, mas o que iremos verificar é o processo para essa verificação de chave SSH no nosso computador.
                
                *(atualização: na atualização do GitHub, agora a opção está em **Deploy keys**)
                
            - O SSH funciona com um par de chaves (pública e privada). Ao se conectar, o nosso computador tem a chave privada. Contudo, para a conexão utilizamos a chave pública
            - Seguimos a documentação para criarmos uma chave nova.
            - Abrimos o terminal na pasta padrão do usuário (C:/Users/leitao) e digitamos o comando `ls -a ~/.ssh` para listar os arquivos ssh que temos. Como referenciada na documentação, devemos ter alguns dos seguintes arquivos:
                - id_rsa.pub
                - id_ecdsa.pub
                - id_ed25519.pub
                (o .pub é referencial para public)
                
                Como não temos nenhum deles, seguimos os passos da documentação:
                
                - Colamos o comando abaixo, substituindo o endereço de e-mal pelo nosso do GitHub:
                `ssh-keygen -t ed25519 -C “sergiomiranda86@gmail.com`
                - `ssh-keygen` >>> comando responsável por gerar a nova chave e configurar a criptografia que é especificada pelo comando à seguir:
                - `-t ed25519` >>> comando que é a alternativa mais recente do protocolo de criptografia da chave
                - `-C ”email”` >>> comando de comentário que recebe o nosso e-mail para referenciar o proprietário da nova chave.
                    
                    ![passphrase: seralterego](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/dd998651-8771-4431-b1c2-3bf1cdb17b54/Untitled.png)
                    
                    passphrase: seralterego
                    
                    Isso cria uma nova chave SSH, usando o nome de e-mail fornecido como uma nova etiqueta no caminho .ssh e agora devemos inseri-la no ssh-agent, criando o ssh-agent primeiro, com o comando abaixo:
                    (MAAAASSS PRIMEIRO, seguimos a solução do Stack Overflow, para resolver um erro que aconteceu, “habilitando” o ssh-agent com o seguinte):
                    
                    ```
                    # link: https://stackoverflow.com/questions/65741816/error-connecting-to-agent-no-such-file-or-directory-adding-key-to-ssh-agent/74879997#74879997
                    #########################################################
                    # Start Windows PowerShell with Run as Administrator mode.
                    # Follow these commands there...
                    
                    Get-Service ssh-agent | Set-Service -StartupType Automatic
                    # By default the ssh-agent service is disabled. Configure it to start automatically.
                    # Make sure you're running as an Administrator.
                    
                    Start-Service ssh-agent
                    # Start the service
                    
                    Get-Service ssh-agent
                    # This should return a status of Running
                    
                    ssh-add C:/Users/leitao/.ssh/id_ed25519
                    # Now load your key files into ssh-agent
                    ```
                    
                    `eval “$(ssh-agent -s)”` >>> Comando não funciona…tive que fazer o seguinte:
                    
                    ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/6c4329c0-fe13-42f5-8917-800ac69423c0/Untitled.png)
                    
                    Após isso devemos entrar com o comando para inserir a chave privada:
                    `ssh-add ~/.ssh/id_ed25519`
                    
                - ~~Inserimos agora no GitHub, em **Deploy keys >>> Add deploy key >>> e preenchemos os campos:~~**
                ⚠️ ~~ALGO DEU ERRADO COMIGO….PQ EM SETTINGS NÃO CONSIGO VER, a tela que a professora mostrou, aparece no link: https://github.com/settings/ssh/new~~
                ⚠️ ACHEI O ERRO…eu estava indo no caminho errado…é na nossa foto >>> SETTINGS >>> SSH and GPG keys…ai vemos a mesma tela:
                    
                    ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/aee72449-3fdb-454c-9a2d-1b9c0043d98d/Untitled.png)
                    
                    Title: Meu notebook (Windows)
                    Key: ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAIA3Z3YYWEYySaTeuJvE+J5vcLdxfPELxT1lpyXRf2hSZ “sergiomiranda86@gmail.com
                    
                    ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/2cc1681f-7a01-48c1-a295-7c13b3afb721/Untitled.png)
                    
                    Para acessar a chave, devemos voltar no terminal, e ir no caminho em que ela está salva (vimos mais acima) com o comando:
                    `cd ~/.ssh`
                    
                    Depois disso, listamos os arquivos com o comando `ls` e observamos que agora temos os arquivos que criamos com o `id_ed25519`:
                    
                    ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/0844b60c-53f5-4874-bd21-f409262e4804/Untitled.png)
                    
                    Iremos então ver o conteúdo da public (`.pub`)
                    
        - Depois disso, conseguimos clonar o repositório com a validação da SSH:
            
            ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/f99f176c-af17-4ba6-bd58-272cdc24f7bc/Untitled.png)
            
            Por ser o primeiro acesso, preenchemos com yes para continuar o processo:
            
            ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/c0295a31-abc2-45af-ac3c-fe25e2848197/Untitled.png)
            

---

- ✅ **3 - Primeiros Passos com Git e GitHub**
    - ➕ Criando e Clonando Repositórios
        - Existem duas formas de obter um repositório Git na sua máquina:
            
            ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/ad44e089-af1a-4dea-9cfc-b207bf6f0c22/Untitled.png)
            
        - Revendo conceitos de clone de repositório
            - Vamos seguir o primeiro passo, e transformar uma pasta local em um repositório Git…dentro de uma pasta local (criamos a repo-local), pelo terminal, inserimos o comando `git init`:
                
                ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/2ebf1858-4a3c-4834-9718-ae4f89782733/Untitled.png)
                
            - O `git clone` foi o que já fizemos anteriormente, e podemos ainda ter um novo nome para a pasta clonada. Para isso, devemos apenas colocar o nome logo depois da url que copiamos lá do GitHub:
                
                ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/bf69ac36-3332-4b9f-8ce8-22048735d5a7/Untitled.png)
                
                O pasta com o clone do repositório então terá o nome de `repo-clonado`
                
            - Comparação entre o arquivo config da pasta .git de um repositório local, com o Git iniciado x um repositório clonado:
                
                ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/25a1da64-2943-438c-a7b7-d147014119c6/Untitled.png)
                
                Podemos observar que o clonado tem mais informações, sendo a mais importante o `remote` que indica a “origem” da url do repositório.
                
            - Para transformar uma pasta local em uma pasta sincronizada com o repositório online, seguimos com o comando `git remote add origin`
            - `origin` é o nome padrão, então é indicado deixar dessa forma, mas depois do add podemos colocar qualquer nome para identificar o repositório.
        - 🚧 Criando um novo repositório no GitHub
            - Como já tenho esse conhecimento, não segui os passos.
    
    ---
    
    - ➕ Salvando Alterações no Repositório Local
        - Criando uma nova pasta para demonstrar mais comandos
            - `git status`
            - `git add`
            - `git log`
        - Explicação sobre `markdown`
            - Na documentação do GitHub temos um breve resumo sobre como escrever markdown no GitHub
        - Subindo as alterações para identificarmos na área de preparação
            - O Git não reconhece pastas vazias, para isso, precisamos ter dentro dele algum arquivo
        - Criando um arquivo `.gitignore`
        - Criando um arquivo `.gitkeep`
            - Podemos nos deparar com pastas vazias com apenas esse arquivo. E ele serve ao propósito de justamente deixarmos uma pasta “vazia”, mas sendo reconhecida pelo Git
        - Comando `git add .`
    
    ---
    
    - ➕ Desfazendo Alterações no Repositório Local
        - Caso tenhamos iniciado um repositório em uma pasta incorreta, pasta seguirmos com o comando `rm -rf .git` para remover recursivamente (rm) e forçando (-rf) a exclusão de todo o conteúdo da pasta .git que foi criada dentro da pasta errada
            
            ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/f8904559-5ca6-48ec-a9fb-796892b97992/Untitled.png)
            
            Ele deixa de indicar a branch `main` e quando rodamos o `git status` ele retorna um erro, dizendo que não temos um repositório git
            
            ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/1c76add0-287b-441c-b4c5-5f89a161072c/Untitled.png)
            
        - Caso tenhamos que recuperar um arquivo alterado incorretamente, fazemos o seguinte:
        `git restore <nome-do-arquivo>`
        Assim recuperamos o conteúdo do arquivo alterado, e ele volta ao último estado que estava na árvore.
        Mas deve ser feito com cuidado!
        - Alterar a mensagem do último commit feito.
            - `git commit --amend -m "mensagem nova"`
            - Dessa maneira, a mensagem do último commit que era “criando gitignore, gitkeep e conteudo de resumo das aulas”, mudou para “mensagem nova”
                
                ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/002de8e2-9a2e-4cc2-aaa1-0a6720afe002/Untitled.png)
                
                ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/022c86cb-35c5-4a53-94c7-e674a77b818c/Untitled.png)
                
            - Com o `git commit --amend` fazendo com que o Git abra seu editor padrão (VS Code no meu caso) e podemos alterar por ele a mensagem, salvar e fechar o arquivo para as alterações terem efeito.
        - Desfazendo o último commit com `git reset`
            - Utilizamos o `git log` para vermos o último commit feito e termos acesso ao *hash code* do commit, que nada mais é do que o identificador dele:
                
                ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/81425d59-4404-4728-bdc4-05065e1ab618/Untitled.png)
                
            - Temos três maneiras de utilizar o `git reset`,
            - `git reset --soft` >>> apenas recoloca os arquivos de volta ao estado de commit na área de preparação
                
                ![Utilizando o `git commit -m "mensagem de commit"`, conseguimos voltar os arquivos para o commit, com a mesma ou uma nova mensagem](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/9b4658fd-39c2-4c20-8fa7-df9c3b4ca29c/Untitled.png)
                
                Utilizando o `git commit -m "mensagem de commit"`, conseguimos voltar os arquivos para o commit, com a mesma ou uma nova mensagem
                
                ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/cf703d37-28c2-4480-9db6-57ad8858a520/Untitled.png)
                
                ---
                
            - `git reset --mixed` >>> é o comportamento padrão do git reset, recoloca os arquivos de volta ao estado de commit na área de preparação, mas como untracked files
                
                ![Nesse caso, podemos adicionar novos arquivos ao commit, e seguimos com `git add .`, para adicionar novamente os arquivo ao estado de preparação para o commit e depois o `git commit -m "mensagem de commit"`](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/980a2d68-9436-4013-ace9-e8582a2dfdb6/Untitled.png)
                
                Nesse caso, podemos adicionar novos arquivos ao commit, e seguimos com `git add .`, para adicionar novamente os arquivo ao estado de preparação para o commit e depois o `git commit -m "mensagem de commit"`
                
                ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/7479a716-b7a8-43b3-9cba-7b2cfa01d1ba/Untitled.png)
                
                ---
                
            - `git reset --hard` >>> é o deve ser usado com mais cuidado…pois ele apaga definitivamente os arquivos do commit, voltando para o commit que utilizamos de referência (o hash code)
                
                ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/b86ee96a-65ca-4eae-9db1-d89a29040a9b/Untitled.png)
                
                ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/3d576ff1-4357-48a3-bb86-f484ab12ccda/Untitled.png)
                
                😳: copiar os arquivos em um “local seguro” seria uma boa antes de seguir com esse comando, pois caso seja necessário, só recolocamos os arquivos no lugar em que estavam
                
        - Para termos mais detalhes sobre o histórico de commits, utilizamos o comando `git reflog`
            
            ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/1ee914bd-d4ce-4eb2-8fca-f3cc409d9823/Untitled.png)
            
        - Outro uso do comando `git reset` é o de retirar arquivos que não queremos da área de preparação. Seguindo o exemplo:
            
            ![Criamos uma nova pasta e nela incluímos dois arquivos (aula01 e aula02). Ao verificamos com `git status`, vemos que os arquivos estão como “untracked”.
            Adicionamos ao estado de preparo do commit  e vemos os dois arquivos criados.](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/83dcb808-febb-4a36-b95a-ae45b2aa340d/Untitled.png)
            
            Criamos uma nova pasta e nela incluímos dois arquivos (aula01 e aula02). Ao verificamos com `git status`, vemos que os arquivos estão como “untracked”.
            Adicionamos ao estado de preparo do commit  e vemos os dois arquivos criados.
            
            ![Utilizamos então o `git reset` para retirar somente um dos arquivos, e quando rodamos `git status` podemos ver que o arquivo retirado, ficará novamente como “untracked”](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/a654300d-85d1-4deb-941f-507642d583c8/Untitled.png)
            
            Utilizamos então o `git reset` para retirar somente um dos arquivos, e quando rodamos `git status` podemos ver que o arquivo retirado, ficará novamente como “untracked”
            
            Para tirar o outro arquivo “trackeado”, só seguimos o que o Git indica com o comando `git restore --staged <file>`, no nosso exemplo, `resumos/aula01.md`
            
            ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/be758f78-9733-4d27-9cb0-935503581926/Untitled.png)
            
    
    ---
    
    - ➕ Enviando e Baixando Alterações com o Repositório Remoto
        
        (como já tenho um repositório, não criei o novo da aula)
        
        - Depois de criado o repositório remoto (vazio), podemos seguir os passos que o próprio GitHub, utlizando os comandos:
            - `git remote add origin <url-do-repositório>` >>> esse comando faz o “alinhamento” entre a pasta local e a url do repositório onde iremos subir nossas alterações
            - `git branch -M main` >>> renomei a branch principal para main (não utilizado no exemplo, pois já estamos na brach main
            - `git push -u origin main` >>> `git push` é responsável por “empurrar” nossas alterações do ambiente local para o remoto. `-u`  é a abreviação de *set upstream* que vai alinhar o `origin` do `git remote` com a branch `main`.
            
            ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/120e7a66-16e1-49f7-8ffb-85b668d58b74/Untitled.png)
            
        - Editando arquivo no repositório remoto
            - sem notas (Já sei fazer)
            - MAS, temos a possibilidade de utilizar o “VS Code” do GitHub, simplesmente apertando a tecla `.` (ponto) do teclado:
                
                ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/49e11055-cf58-4e01-8b91-bf72db89423f/Untitled.png)
                
                Mesma coisa que o local!
                
        - Baixando do remoto para o local
            - Utilizamos o comando `git pull`
                
                ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/7a425b46-2905-440f-9d6e-40b0f88f58ce/Untitled.png)
                
    
    ---
    
    - ➕ Trabalhando com Branches - Criando, Mesclando, Deletando e Tratando Conflitos
        
        > De maneira simplista, uma Branch (em tradução, “Ramo), é uma ramificação do seu projeto.
        > 
        
        ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/f2305428-410c-4e65-96f4-82e90d4ab52c/Untitled.png)
        
        - Utilizamos o conceito de braches para que possamos fazer alterações no nosso projeto, sem comprometer  o projeto principal (branch main):
            
            ![Criamos uma nova branch à partir do commit 2 da main, para fazemos os testes e implementações necessárias, assim, o próximo commit não afetará a branch main, que ficará no commit 2, até que passemos as informações da nova branch pra ela.](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/27296a95-b2c7-4de9-b295-1acb3f96eb5d/Untitled.png)
            
            Criamos uma nova branch à partir do commit 2 da main, para fazemos os testes e implementações necessárias, assim, o próximo commit não afetará a branch main, que ficará no commit 2, até que passemos as informações da nova branch pra ela.
            
            ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/9e4e14fb-a167-4997-9f39-0d81e51b6682/Untitled.png)
            
        - Criamos dois commit (era pra ser 1 e 2, ficou l e 2 kkk) para exemplificar esse processo:
            
            ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/edb6530d-0718-4625-92c8-f391b1feba57/Untitled.png)
            
            ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/dac41c9c-c688-4668-8fba-a6b3c1f0cc62/Untitled.png)
            
            Depois disso, criaremos a nova branch com o comando `git checkout -b teste`
            
            ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/2ca82bfc-7f60-4610-93c7-fa2f54a5bdfc/Untitled.png)
            
            É importante observar que a nova branch está apontando para o mesmo commit feito na `main`:
            
            ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/a31b1092-4b53-43f5-8a55-15c14705e011/Untitled.png)
            
            Criamos agora um novo commit, na nova branch:
            
            ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/74e6014a-51ac-49a5-9415-0d497dd42fd0/Untitled.png)
            
            Podemos observar que o commit-3 está apontando apenas para teste agora, enquanto a `main`, ficou no commit 2.
            
            Voltamos pra branch `main` com o comando `git checkout main`   e podemos observar que o arquivo criado, não está nela, conforme podemos ver na pasta de arquivos abaixo:
            
            ![branch teste](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/0d0a34ac-0872-47a3-9d7f-e35937ae469a/Untitled.png)
            
            branch teste
            
            ![branch main](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/0db3a665-5623-4db4-a5f6-8407cbfd2b8d/Untitled.png)
            
            branch main
            
            Com o comando `git branch -v` podemos observar a lista de branchs e seus estados atuais:
            
            ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/a27fabd0-37a0-449b-930e-373a58045832/Untitled.png)
            
            Para que as branches fiquem com as mesmas informações, utilizamos o comando `git merge <nome-da-branch-onde-pegaremos-as-novas-informações>`, no nosso caso `git merge teste`
            
            ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/0bf1f5b7-31a2-4bff-b110-7d9e5e510183/Untitled.png)
            
            Como não vamos mais utilizar a branch de teste, vamos exclui-la. Primeiro, passamos o comando `git branch` para listar as branchs. O `*` mostra qual a branch que estamos atualmente:
            
            ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/b1d5b10b-e954-4348-80e8-e336dcbe5dc9/Untitled.png)
            
            E para excluir a branch de teste, passamos o comando `git branch -d <nome-da-branch-que-será-excluída>`, no noso exemplo `git branch -d teste`.
            Assim, quando rodamos `git branch`, vemos que ela não aparece mais:
            
            ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/450b5726-ec52-4cef-99db-a7c580ecbafb/Untitled.png)
            
        - É IMPORTANTE se atentar as convenções de criação de branches, para que possamos seguir as diretrizes do projeto que iremos trabalhar e TAMBÉM não esquecer de subir par o repositório remoto essas novas branches, para que todos fiquem à par do que está sendo desenvolvido.
        - Agora resolveremos conflitos, algo comum trabalhando em equipe.
        (vou seguir o mesmo processo, mas criando só um novo arquivo para gerar o conflito)
            - Crio um arquivo para deixar claro que ele foi criado antes de ser gerado o conflito:
                
                ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/8635214b-3e1d-4784-bb64-bd2c1aa24fd7/Untitled.png)
                
                Segui um caminho diferente, mas que gerou o mesmo conflito:
                - Na branch remota, alterei o arquivo criado (commit-conflito.txt) para o seguinte:
                
                ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/dbf85309-ac78-4e67-8fdd-fe37e76788b9/Untitled.png)
                
                E commitei:
                
                ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/3786da92-c921-482d-9a70-a50ec73b7679/Untitled.png)
                
                Depois fiz a alteração local e também commitei (mas como fiz o remoto antes, ele gerou até um erro diferente da aula, pedindo que eu commitasse o local antes de fazer o `git pull` para pegar o remoto…
                
                ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/0dde0faf-ddc1-4bce-b8bc-cc2c4200c3df/Untitled.png)
                
                ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/8a8a47e0-a722-4bcf-8282-d10676941bc3/Untitled.png)
                
                Ai depois disso, sim, gerou o conflito.
                
                Então, com o git log, vemos que o commit está diferente do remoto:
                
                ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/506ff8ba-c003-46be-bef5-9aca84808a22/Untitled.png)
                
                ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/d471338d-acee-4614-83fa-1867cde3e823/Untitled.png)
                
                Resolvendo isso direto no arquivo, podemos então commitar e subir pro repositório remoto a alteração que queremos que permaneça:
                
                ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/8834afdf-17c8-4819-9d53-271e8d615e10/Untitled.png)
                
                ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/32ca9518-fcb2-4867-a35a-fc39cdcd28ba/Untitled.png)
                
                ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/872210ab-b017-41c9-b2df-6a6975f1a8cf/Untitled.png)
                
                ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/66bbd799-d7a7-4c3e-b6fc-a132948776c5/Untitled.png)
                
                Ai vemos que ambos os ambientes estão no mesmo commit:
                
                ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/4bd60bd1-5ded-4c44-b175-fe71877dd2dc/Untitled.png)
                
                ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/6b9288f3-4f62-4367-8965-cf22d99c1acb/Untitled.png)
                
    
    ---
    
    - ➕ Trabalhando com Branches - Comandos Úteis no Dia a Dia
        - Aproveitando o ~~repositório~~ arquivo criado, vamos aprender novos comandos muito úteis, como o `git fetch`
            - Quando fizemos o `git pull` no conflito, ele gerou uma mensagem de erro no merge. O `git pull` é nada mais do que a junção entre `git fetch` (que baixa as alterações) e `git merge` (que mescla as alterações).
            - Para exemplificar, criamos um novo commit pela branch remota, incluindo um [arquivo.md](http://arquivo.md) e a mensagem “conteúdo de arquivo ‘commitado’ na branch remota.”
                
                ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/877f0473-3ebd-4d92-a7b2-552aeb1dcedc/Untitled.png)
                
            - Indo no repositório local, com o `git log,` vemos que esse commit não existe:
                
                ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/428d4ebb-8a9b-4cd9-b250-f5d70c3fdb83/Untitled.png)
                
            - Para baixar essas alterações sem mesclar com o repositório local…ai que entra o `git fetch`, com o comando `git fetch origin main`
                
                ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/a5afc383-2dc8-4654-bea9-ade3f6f7497f/Untitled.png)
                
                Observe abaixo que o último commit local não está mais alinhado com o remoto…mas não temos ainda o conteúdo da branch remota:
                
                ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/1e4cd5d8-90a5-480e-b5b5-4cf164f475da/Untitled.png)
                
            - Se quiseremos comparar a branch local com a remota, utilizamos o comando `git diff <branch-local> origin/<branch-remota>`. Ai sim, somos apresentados ao que efetivamente está diferente:
            `git diff main origin/main`
                
                ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/4fbf7f89-1024-4323-b7f2-34fca8a18f59/Untitled.png)
                
            - Para trazermos elas pro ambiente local, utilizamos o comando `git merge origin/<branch-remota>`:
            `git merge origin/main`
                
                ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/1430ec7f-945b-40f9-b9d2-a5efa6f42ea9/Untitled.png)
                
        - Para clonarmos apenas uma branch especifica de um repositório remoto, utilizamos `git clone <url-do-repositório-remoto> --branch <nome-da-branch> --single-branch`
        `git clone https://github.com/seralterego/dio-potenciatechifood.git --branch teste --single-branch`
            
            ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/9610f198-ef1b-4828-aad3-bb6e2fab0430/Untitled.png)
            
            ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/90c88bb7-a218-41b4-9223-5bd516875527/Untitled.png)
            
            ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/5d761bb9-6bd2-4f89-8ace-dc37845dbc06/Untitled.png)
            
        - Seguindo o exemplo na branch teste, excluímos um arquivo, e vamos ter que passar essa branch para uma outra, mas não queremos que essa exclusão siga para a nova branch. Utilizamos então o git stash para “salvarmos” essa alteração
        `git stash`
            
            ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/099b6994-c237-45f8-be6c-0b3b9a44c8bc/Untitled.png)
            
            - Com o `git stash list` conseguimos ver a modificação arquivada.
                
                ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/c8330b32-316e-4f90-a521-f354dfdc995a/Untitled.png)
                
                Podemos então criar uma nova branch (teste-2)…fazemos o que precisamos e voltamos para a branch teste.
                Listamos a modificação arquiva e podemos com o comando `git stash pop`, para trazer de volta a modificação e **excluir ela da pilha** criada e vista no `git stash list`, ou `git stash apply`, para trazer de volta a modificação, mas **manter a modificação na pilha** para algum uso futuro.
                
                ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/eb390e95-16f8-497c-b0eb-e33c72801b24/7abeab65-18cf-4d9f-a6e0-69bc3f143812/Untitled.png)
                
        - Para mais: https://git-scm.com/doc
            - https://git-scm.com/docs/git#_git_commands
            - https://git-scm.com/book/en/v2

---

- ✅ **4- 📚 Dicas e Materiais de Apoio**
    - Dicas e Materiais de Apoio
        - Repositório no GitHub: https://github.com/elidianaandrade/dio-curso-git-github
        - Links de referências
    - Materiais de Apoio
        - Slides - Versionamento de Código com Git e GitHub: https://academiapme-my.sharepoint.com/:p:/g/personal/renato_dio_me/EYjkgVZuUv5HsVgJUEPv1_oB_QWs8MFBY_PBQ2UAtLqucg?e=262HGK

---

## 🎉 Certificado
![Certificado de Conclusão](https://hermes.digitalinnovation.one/certificates/cover/96FEC40F.jpg)