# docs.pologos.com

## Przeszłość

text-to-image czy text-to-video to zbyt mało, istotne z punktu widzenia kontroli naszego technologicznego środowiska jest oprogramowanie, które sztuczna inteligencja powinna najpierw napisać, uruchomić, przetestować i zintegrować z już istniejącym systemem, żadna aktualnie firma nie oferuje takiego rozwiązania, jest pewien wyjątek... 


## Teraźniejszość 

w systemach opartych o AI trzeba rozróżnić:
 
1. System operacyjny, który zawiera zestaw narzędzi do tworzenia modeli, oprogramowania z użyciem AI
 
2. System operacyjny, który wykorzystuje AI jako interfejs do komunikacji 
 
3. System operacyjny, który zawiera interfejs do komunikacji z człowiekiem i maszynami, który nie wymaga znajomości technologi a generuje/strumieniuje/personalizuje oprogramowanie w czasie rzeczywistym
 
Tym ostatnim będzie #pologos https://www.pologos.com


## Przyszłość 

Przyszłość zmierza nie tylko do produkcji oprogramowania w ciągu sekund, ale programowaniu całych ekosystemów technologicznych, zastępowanie nie pojedynczych specjalistów, ale całych zespołów.


## Ograniczenia AI

Mimo wielu zalet, AI jest na zbyt niskim poziomie możliwości, zużywa za dużo energii i znacznie taniej jest wytwarzać oprogramowanie ograniczając AI

AI ma tylko przetwarzać dane wejściowe na format języka APIDSL


## Jak działa pologOS

### Dostęp do systemu jest możliwy poprzez:

+ port 21 - dostęp do systemu danych
+ port 22 - standardowy shell
+ port 23 - shell typu text to software - poloSHELL

+ port 80 - widok aplikacji wytworzonej za pomocą pologOS, dostęp dla klienta

dostęp dla developera TextToSoftware:

+ port 8023 - shellUI z dostępem do webowej wersji poloSHELL, 
+ port 8080 - webowe logi, debugowanie aplikacji,


### Terminal

Na porcie 22 mozesz aie polaczyc do normalnego shell a na porcie 23 do poloSHELL-a przygotwanego pod komunikację TextToSofwtare.

po zalogowanie do konsoli poloShell mozliwa jest interakcja ze sztuczną inteligencją.
Możliwe jest wygenerowanie aplikacji w kilku krokach, po podaniu danych potrzebnych do jej utworzenia i konfiguracji.

Na porcie 80 bedzie dostepna wygenerowana apke webowa.


### Cloud

Fizycznie to bedzie mozliwe do uruchomienia w dockerze do testow ale tez na chmurze

Kazdy user bedzie mial swoj VPS z tM systemem
Chodzi o to by pisac jak na chat, zadajac pytania i dajac odpowiedzi
Taki interaktywny chat
Bez kommend bash
Sam tekst


## Interfejsy komunikacyjne

### klawiatura - poloSHELL

W pierwszej kolejności dostępny jest poloSHELL, gdzie na porcie 23 można się zalogować i prowadzić interakcję w celu wygenerowania aplikacji za pomocą klawiatury

### myszka - ShellUI

Poprzez port 8023 można za pomocą przeglądarki połączyć się z system w sieci lokalnej i używając bardziej interaktywnego interfejsu używać na mobilnych urządzeniach

### Głos - SpeechCli

Interfejs głosowy będzie dostępny na SpeechCli, poprzez mikrofon i głośnik na urządzeniu, gdzie został zainstalowany system pologOS



## LFS

### distribution


### localization


### configuration


## Shell client connection

### Install et
et


### Install mosh 



## Shell server

etserver
mosh



## Shell manager

+ poloshell
+ zsh
+ 

## Virtualization

+ docker
+ ansible
+ Oracle VM


## http application, 

### services: ports - name

+ 22 ssh connection based on et/mosh
+ 80 http - chat client on browser
+ 8080 - http web application on browser
+ 8081 - debug info
+ 8082 - orchestration panel






[Best Tools To Create Your Own Custom Linux OS In 2022 | Itsubuntu.com](https://itsubuntu.com/tools-create-custom-linux-os/)

> ## Tools To Create Your Own Custom Linux OS In 2022
> 
> ### 1) Linux From Scratch:
> 
> It is one of the most important collections of tools and resources to create your own custom Linux. It is popular for its step-by-step instructions to build a custom Linux.
> 
> [Linux From Scratch](http://www.linuxfromscratch.org/)
> 
> ### 2) Ubuntu Imager
> 
> A useful tool to create your own Ubuntu-based Linux operating system.
> 
> [Ubuntu Imager](https://github.com/Distroshare/distroshare-ubuntu-imager)
> 
> ### 3) Linux Respin
> 
> Linux Respin is a tool to create a custom distro based on Debian or Ubuntu operating system.
> 
> [Linux Respin](http://www.linuxrespin.org/)
> 
> ### 4) Linux Live Kit
> 
> Linux Live Kit is a set of shell scripts. You can create your own Linux from an already installed Linux.
> 
> [Linux Live Kit](https://www.linux-live.org/)
> 
> ### 5) Live Magic
> 
> Live Magic is a GUI-based tool to create a Debian-based Linux operating system. It’s a pretty simple tool in comparison to other Linux distro creators.
> 
> [Live Magic](https://chris-lamb.co.uk/projects/live-magic)
> 
> ### 6) Slax Modules Tool
> 
> An online tool from Slax which lets you create your own flavor of Slax Linux with your own set of applications.
> 
> [Slax Modules Tool](https://www.slax.org/modules.php)
> 
> ### 7) Cubic
> 
> A GUI-based amazing tool to create a customized bootable Ubuntu Live CD (ISO) image.
> 
> [Cubic](https://launchpad.net/cubic)
> 
> This much for now as you can try to build your own Linux operating system with the help of these tools. Let us know if we forget to mention some important must-have tools to create custom Linux.

## Download ISO arch

[Index of /archlinux/iso/2022.12.01/](https://mirror.eloteam.tk/archlinux/iso/2022.12.01/)
