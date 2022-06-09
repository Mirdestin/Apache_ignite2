# Apache_ignite2
Exercice2 
L'application est pour la gestion des stagires codé en php.
Pré-requis pour l'utiliser avec Ignite :

JDK ;Oracle JDK 8 or 11, Open JDK 8 or 11, IBM JDK 8 or 11

OS :Linux (any flavor), Mac OSX (10.6 and up), Windows (XP and up), Windows Server (2008 and up), Oracle Solaris

ISA : x86, x64, SPARC, PowerPC

Network :No restrictions (10G recommended)

and: PHP Version 7.2 or higher and Composer Dependency Manager. PHP Multibyte String extension. Depending on your PHP configuration, you may need to additionally install/configure it.

Une fois INGITE installez, installez PHP Thin Client en tant que package Composer à l'aide de la commande ci-dessous :
composer require apache/apache-ignite-client.

Pour utiliser le client dans l'application, incluez le fichier vendor/autoload.php, généré par Composer, dans le code source

Avant de vous connecter à Ignite à partir du client Thin PHP, vous devez démarrer au moins un nœud de cluster Ignite.
Sur Windows : 
1 cd {IGNITE_HOME}\bin\
2 ignite.bat ..\examples\config\example-ignite.xml
Ouvrez un autre onglet à partir de votre shell de commande et exécutez à nouveau la même commande.


