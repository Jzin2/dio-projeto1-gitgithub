# Vantagens do versionamento

-Registra o histórico de alterações completo e a longo prazo de todos os arquivos;
-Gerencia as alterações como criação e exclusão de arquivos e edições em seus conteúdos como data, autor, etc.;
-Organização, controle e segurança.

# [Vantagens dos sistemas de controle de versão](https://www.atlassian.com/br/git/tutorials/what-is-version-control#:~:text=O%20controle%20de%20vers%C3%A3o%20protege,e%20modificando%20c%C3%B3digo%2Dfonte%20existente.)

# Tipos de sistema de controle de versão

-VCS Centralizado (CVCS)
 ##### Ex.: [CVS](https://savannah.nongnu.org/projects/cvs/), [Subversion](https://subversion.apache.org/).

Como característica principal, possui apenas um servidor central que guarda todas as informações do repositório central.

Sua maior desvantagem ocorre caso este servidor fique offline, impossibilitando salvar as alterações.

Outro problema acontece quando algum arquivo é corrompido ou tem perda de dados; você pode acabar perdendo seu projeto caso não tenha feito um backup de segurança.

-VCS Distribuído (DVCS)
 ##### Ex.: [Git](https://git-scm.com/about), [Mercurial](https://www.mercurial-scm.org/about)

Como característica principal, possui os repositórios duplicados localmente, ou seja, os computadores terão cópias dos arquivos do servidor principal.

Isso permite a edição mesmo com o servidor offline.

Neste sistema, é possível clonar o repositório completo, o que inclui o histórico das alterações.

Cada clone funciona como um backup, possibilitando um fluxo de trabalho mais flexível.
