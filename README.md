# RecuperacaoRMI

IDE utilizada :  Intellij Community
Versão Java : SDK-19, apesar da IDE ter instalado java SDK - 23.0.2
///////////////////////////////////////////////////////////////////////////////////////////////////////

Etapas da recuperação : 

Assuntos vistos no processo da recuperação - 
Proc, stub, Server, RMI,  interface, Cliente, abstração, portas 
|||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||
RMI -  Recuperação 
- licença do RMI (ela diz que posso usar sem problemas como direitos autorais)
- postar no GitHub o código
- postar o README no GitHub
- postar o código no GitHUB
- Explicação do código 
- Explicação do porquê fez de tal jeito
- Fontes (bibliografia)
- Citação(Se tiver, no caso tenho uma do Moodle )

Tarefas pessoais sobre conceitos :
Foi utilizada interface 
Separar os códigos em suas respectivas classes.
Reler o que é Proc (no artigo)   
Descobrir quem é a interface para o servidor chamar
Descobrir quem é a interface para o cliente
Proxy(Se tiver)


Dificuldades situacionais :
O SDK instalado estava com o Path sem ser prioridade em Variáveis de Ambiente -> Sistema

No que impactou : o rmiregistry não era encontrada, porque uma variável de ambiente, relacionada a Oracle, estava sendo lida, e tinha outra versão
do Java, mais antiga.

JAVA_HOME , uma variável de ambiente, fora de Path, não existia nas variáveis de ambiente -> sistema, no meu computador.
-------------------------------------------------------------------------------------------------------------------------------------------
Foi utilizado, com autorização do professor, um vídeo sobre implementação de RMI. 
Esse vídeo contém um versão mais antiga, a qual a classe stub ainda precisa ser inicializada pelo usuário, e que também aparece.
Configuração do cliente.policy e server.policy.

Eu percebi apenas com auxílio que ambos os arquivos citados, são um arquivo de texto, e não jar.

Com a versão 19 do Java, e com apoio do Intellij(o qual instalei hoje, 15/020/2025), o stub foi gerado, debaixo dos panos. 
Precisei consultar o ChatGPT e o Gemini, para saber
porque não aparecia o stub(por mais que eu não tivesse de mexer nele). Pensei que era essencial ele aparecer na IDE.
Minha primeira vez me aprofundando no assunto.
-------------------------------------------------------------------------------------------------------------------------------------------
Observações pessoais : 
Temas a serem aprendidos : 
Configurações de execução(principalmente remover da lista de execução outros códigos de projetos diferentes).
VM path
Atualização de versões do java
RMI e RMI registry
Arrays em Java


Bibliografia : 

1 -
Arquivo
Seção 5.4 - Invocação de Métodos Remotos (RMI)Arquivo
 Atividades de Aprendizage
https://moodle.ifsc.edu.br/mod/resource/view.php?id=198910

2 - 
Exemplos práticos do uso de RMI em sistemas distribuídos
Elder de Macedo Rodrigues, Guilherme Montez Guindani, Leonardo Albernaz Amaral, Fábio Delamare
Pontifícia Universidade Católica do Rio Grande do Sul (PUCRS)
Faculdade de Informática Programa de Pós-Graduação em Ciência da Computação
Sistemas Distribuídos
Porto Alegre/RS – Brasil – CEP 96616-900
https://www.inf.pucrs.br/gustavo/disciplinas/sd/material/Artigo_RMI_Pratico.pdf

